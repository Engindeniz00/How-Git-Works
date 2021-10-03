# Merge Types

## There are two type of merge operations.

1. **Forward Merge**
2. **3 Way Merge**

---

# Forward Merge

It is the easiest way to find target brach location from master branch. It just carrys the head pointer directly from master branch to the target branch pointer except there is no gap and seperation between branch arms. 

> Here is chart example of forward merge. (Branch names : 'SD' and 'auth')
> 

![Untitled](Source/Merge%20Types%2043dbb8d171424fe0979b25ec4b258d56/Untitled.png)

# 3 Way Merge

Usually we faced with this situation when merging another branch if it is not the case of direct passage between last merged branch and targe branch. To solve that git looks at three commit.

- **First looks at base commit where two branches started from**

![Untitled](Source/Merge%20Types%2043dbb8d171424fe0979b25ec4b258d56/Untitled%201.png)

- **Then last commit of each branch**

![Untitled](Merge%20Types%2043dbb8d171424fe0979b25ec4b258d56/Untitled%202.png)

- **Finally merge successfully auth to master branch with SD branch.**

![Untitled](Source/Merge%20Types%2043dbb8d171424fe0979b25ec4b258d56/Untitled%203.png)

[]()
