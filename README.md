# How to work with GitHub


## First


1. Go to your directory using **_cd_** _your directory
2. Type in terminal **_git init_** to initialize a repository
  *Create some files using **_touch_** _filename_
3. Type **_git add -all_** to choose all files in the directory
4. Type **_git commit -m '_** _your message_
  *You can check your _log_ using **_git log_**


### Second


1. Go to [GitHub](github.com)
2. Register
3. Create a new repository
4. Create a SSH-key
  1. Go to **_cd ~_**
  2. Type **_ssh-keygen -t ed25519 -C_** _your email_
  3. Make sure you did well using **_ls -a ~/.ssh_**
5. Type **_pbcopy < ~/.ssh/id_ed25519.pub_** to copy text in the file
6. Go to GitHub and paste your key using _Add SSH_
7. Go to your directory and type **_git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git_**
  *Make sure you did well using **_git remote -v_**
8. Send your file to GitHub using **_git push -u origin main_** 





