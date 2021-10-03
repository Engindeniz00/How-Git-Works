# How Git works?

In first, we should ask what is git? Git is an version control system that gives teams opportunities to work together.  For instance lets we have jack and jannie.

There is a source code and code need to some development on it. So jack and jannie should work together on project. But how?  Here comes the git system that can possible projects to develop on their own pc of developers in seperate. In conclude they can merge their developed projects on main project together again.

# Here is a chart explanation of git projects

![Untitled](Source/How%20Git%20works%2099dcc4a137eb4249b71aff12422f2803/Untitled.png)

I hope it would be more clear on your mind.

# Ok dude what now?

Now we can start to implement the git on our instance projects.

First we should create a folder on desktop or whatever is it located it is your own decision.

```bash
$ mkdir Git_Example
```

Then we can open git bash terminal window and configurin our path just where our project located in our pc system.

```bash
$ cd Desktop/'Git Example'
```

**As you can see we are in path where our project is located**

```bash
Angel Diesel@DESKTOP-CBIBIGI MINGW64 ~/Desktop/Git Example
```

Here is the crucial part. We need to initialize git in our project to track our project files.

```bash
Angel Diesel@DESKTOP-CBIBIGI MINGW64 ~/Desktop/Git Example
$ git init
Initialized empty Git repository in C:/Users/Angel Diesel/Desktop/Git Example/.git/
```

You can see the message bottom of code that mean successfully created git direc

---

Lets create some text files to see changes and implement git repo system on it.

```bash
Angel Diesel@DESKTOP-CBIBIGI MINGW64 ~/Desktop/Git Example (master)
$ echo file1 test text > file1.txt

Angel Diesel@DESKTOP-CBIBIGI MINGW64 ~/Desktop/Git Example (master)
$ echo file2 test text > file2.txt
```

To see if files created we can just check the directory typing

```bash
Angel Diesel@DESKTOP-CBIBIGI MINGW64 ~/Desktop/Git Example (master)
$ ls
file1.txt  file2.txt
```

> **You can see the files that we have created**
> 

### When we initialize git repository we can simply explain what is going on here by using charts.

- First we are creating a track system that can detect all changes in our project files on local. And we call that local enviroment as 'Working Tree' where our projet located on our local pc.

![Untitled](Source/How%20Git%20works%2099dcc4a137eb4249b71aff12422f2803/Untitled%201.png)

- We can see the status of files as untracked by using this code

```bash
**$ git status**
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        file1.txt
        file2.txt
```

- So need to track those files to create commit logs and we call 'Stagin Area' where the tracked files is stored. To track files we need:

```bash
$ git add file1.txt file2.txt
```

> or just simply type this to add all files
> 

```bash
$ git add .
```

- Then we can see files just tracked on git repository.
- $ git status
    
    ```bash
    On branch master
    
    No commits yet
    
    Changes to be committed:
    (use "git rm --cached <file>..." to unstage)
    new file:   file1.txt
    new file:   file2.txt
    ```
    
- If we want the symbolize the moment we can just explain it like that

![Untitled](Source/How%20Git%20works%2099dcc4a137eb4249b71aff12422f2803/Untitled%202.png)
