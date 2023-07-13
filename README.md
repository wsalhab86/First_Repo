# Git Hub
**Example of table**
Tables
---------------------------

Item | Value
-------- | -----
Computer | $1600
Phone | $12
Pipe | $1 

| Column 1 | Column 2 |
|:--------:| -------------:|
| centered | right-aligned |

- step 1: **creating a local re**
```
cd my_app
```
- step 2: ***Initialize a new git session***
``` 
git init 
```

- step 3: **Adding files to the Repository**
```
git add .
```
- step 4: **commit changes**
```
git commit -m "virsion 0"
```

- step 5: **Create a remote repo**
this is done on GitHub

- setp 6: **Connect my local repo to the remote repo**

```
git branch -M main
```
```
git remote add origin https://github.com/wsalhab86/First_Repo.git
```
```
git push -u origin main
```

- step 7: **Update on code or README file need to re-add on updates on my local machine, then commit back with updates notes**

```
git add .
```
```
git commit -m "Note for updates"
```
```
git push -u origin main
```