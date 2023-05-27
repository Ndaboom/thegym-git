# Exercise 1 - Bundle 1
```sh
 PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git init
Reinitialized existing Git repository in D:/Documents Ext/The Gym/Preparatory training/thegym-git/.git/

 PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git branch -m master main

 PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git add .

 PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git commit -m "Index.html file created"
[main 85a046c] README.md file created
 1 file changed, 2 insertions(+)  

 PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git push origin main
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 2 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 928 bytes | 232.00 KiB/s, done.
Total 7 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Ndaboom/thegym-git.git
   3285b93..85a046c  main -> main

 PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git checkout -b dev      
Switched to a new branch 'dev'

 PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git checkout -b test
Switched to a new branch 'test'

 PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git checkout dev        
Switched to branch 'dev'
M       README.md

PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git branch -d test       
Deleted branch test (was 85a046c).
```

# Exercise 2 - Bundle 1
```sh
PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git add .

PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git commit -m "Work in progress - Home page" 
[dev e338673] Work in progress - Home page
 2 files changed, 17 insertions(+)        
 create mode 100644 home.html

PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git stash


git add .
PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git commit -m "Work in progress - About page"
[dev ec85df1] Work in progress - About page      
 2 files changed, 20 insertions(+), 1 deletion(-)
 create mode 100644 about.html
PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git stash


PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git add .
PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git commit -m "Work in progress - Team page"
[dev 63811ec] Work in progress - Team page
 2 files changed, 22 insertions(+), 1 deletion(-)
 create mode 100644 team.html
PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git stash

PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git stash pop
```

# Exercise 1 - Bundle 2
```sh
PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git add .
PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git commit -m "Services page added"
[ft/bundle-2 feb3a12] Services page added        
 3 files changed, 23 insertions(+), 1 deletion(-)
 create mode 100644 services.html
PS D:\Documents Ext\The Gym\Preparatory training\thegym-git> git push origin ft/bundle-2
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.    
Delta compression using up to 2 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 751 bytes | 15.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0       
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Ndaboom/thegym-git/pull/new/ft/bundle-2
remote:
To https://github.com/Ndaboom/thegym-git.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
```