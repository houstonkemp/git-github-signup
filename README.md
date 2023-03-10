# git-github-signup

Hi, new HKer!

We use Git for managing our code files, which helps us keep track of changes we make as well as share changes with others.
 
We use Github to store those files. When you get a chance, please sign up [here](https://github.com/signup) (using your work email address). (let [Nick](mailto:nick.twort@houstonkemp.com) know if you have any questions).
 
We can then add you to the [houstonkemp](https://github.com/houstonkemp) group and to any required repositories for project work.
 
Please also install git from [here](https://git-scm.com/download/win) – you can just accept all the default settings. Once you have installed it, open the Git Bash shell (click Windows and type git bash). In the shell, enter (with the quotes but without the triangle brackets):
 
 ```
git config --global user.name "<your name>"
git config --global user.email "<your e-mail>"
```

Once you have done that, open RStudio, then select “Tools” > “Global Options” > Git/SVN > 
and ensure that the Git executable is pointing to where Git was installed. It was probably installed at `C:\Users\yourname\AppData\Local\Programs\Git\bin`.
 
Then in the same settings window, click view public key (click create SSH Key if there is no ssh key there – you don’t need a passphrase). Copy the public key.
Now go to [here](https://github.com/settings/ssh/new) and paste in the key section.

When you’ve done this and we've added you to the houstonkemp group, see if you can install [this R package](https://github.com/houstonkemp/hkverse) (which contains 3 packages) following the instructions in the readme (noting the bit about creating a personal access token). Note that you won't be able to access that URL unless you're signed in to GitHub and you have been added to the group.
