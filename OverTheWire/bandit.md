# bandit
overthewire website contain alotes of challenges bandit is one of those it is simple or i say easy to solve then rest of the linux based challenges , so lets begin

## 1) bandit0

- login ssh using given username and password
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
```
- password--> bandit0
- the password to next level is in readme file use cat command 
```
cat readme
```
## 2) bandit1 
- bandit1 is little tricky as we get file named "-" which cant be read using cat so lets try realpath to get full path then use it to cat the password
```
realpath '-'
cat {realpath}
```
## 3) bandit2
- bandit3 
