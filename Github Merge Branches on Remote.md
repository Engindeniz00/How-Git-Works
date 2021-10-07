# Github mergin branches

```bash
git checkout master
git pull origin master
git merge test
git push origin master

First we have to come in the branch
which we want to merge the codes in. 
It means generally we should come
into master branch in this case.
- git checkout master ==>
                now you are in master branch
- git pull origin master ==> 
              We are pulling recent code from master branch 
                                                    on GitHub
- git merge develop -m "your message here" ==> 
            to merge a develop branch into master branch 
- git add . 
- git commit -m "final commit"
- git push origin master
- now when other team members pull master
they will see what you sent
*** git rebase LoginFeatureBranch ==>
                This will merge Login with Master but 
closes the LoginFeatureBranch for good (completely).
```

![Untitled](Source/Github%20mergin%20branches%20bf2e4342d90b43ee980a751acee96667/Untitled.png)

![Untitled](Source/Github%20mergin%20branches%20bf2e4342d90b43ee980a751acee96667/Untitled%201.png)
