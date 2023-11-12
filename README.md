# How to work with GitHub


## First


1. Go to your directory using **_cd_** _your directory_


```
cd dir
```


2. Type in terminal **_git init_** to initialize a repository

```
git init
```

  * Create some files using **_touch_** _filename_
  
  ```
  touch file.txt
  ```
  
  
3. Type **_git add -all_** to choose all files in the directory

```
git add --all
```


4. Type **_git commit -m '_** _'your message'_

```
git commit -m 'Mark1'
```


  * You can check your _log_ using **_git log_**
  
  
  ```
  git log
  ```


### Second


1. Go to [GitHub](github.com)
2. Create an account
3. Create a new repository
4. Create a SSH-key
  1. Go to root directory
  
  ```
  cd ~
  ```
  
  
  2. Type **_ssh-keygen -t ed25519 -C_** _'your email'_
  
  ```
  ssh-keygen -t ed25519 -C ivanivanov@gmail.com
  ```
  
  
  3. Make sure you did well using **_ls -a ~/.ssh_**
  
  ```
  ls -a ~/.ssh
  ```
  
  
5. Type **_pbcopy < ~/.ssh/id_ed25519.pub_** to copy text in the file


```
pbcopy < ~/.ssh/id_ed25519.pub
```


6. Go to GitHub and paste your key using _Add SSH_


7. Go to your directory and type **_git remote add origin git@github.com:%profilename%/first-project.git_**


```
git remote add origin git@github.com:ivanov/reposytory-name.git
```


  *Make sure you did well using **_git remote -v_**
  
  ```
  git remote -v
  ```
  
  
8. Send your file to GitHub using **_git push -u origin main_** 


```
git push -u origin main
```


### Errors

If you deal with errors just follow hints below your commands. Goodbye!


