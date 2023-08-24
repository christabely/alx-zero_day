

INTRODUCTION TO GIT ❤️ 

![1000045803](https://github.com/christabely/alx-zero_day/assets/129256391/7c20b9b4-004d-4416-a484-d42e94d9155a)


Q0. Create a github repository with the required name and description.
Go to your terminal and clone your repository with the ff command: git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/alx-pre_course.git
Note - Do not include the curly bracket
After cloning, change directory to the repository created: cd repository_name
Now create a README.md with the required content. 
Configure your user email using: git config --global user.email 'you@example.com'
configure your name using: git config --global user.name 'Your Name'
To push your README.md to your github repository, first, type: git add .
then: git commit -m 'A commit message' then: git push

Q1. To create a directory, we use the command mkdir. 
mkdir 0x01-git
After creating the directory, you move into it using the command: cd 0x01-git
In the 0x01-git create a README.md file with a content. 
(Don't forget to add, commit and push)

Q2. Still in your 0x01-git directory, create the required directories with the command: mkdir bash c js
Now move into the individual directories to create the required files inside them. The command to create an empty file is "touch". 
cd c (now we are in the "c" directory)
touch c_is_fun.c
cd .. (we are moving from the "c" directory back to the 0x01-git directory)
cd js (we move to the "js" directory to create the empty files)
touch main.js index.js
cd .. (back to the 0x01-git directory)
cd bash (we move to the bash directory)
(Because the files we are creating insde the "bash" directory has contents, we shall not use the "touch" command. We shall create them automaticallywith either Emacs or Vi)
echo '#!/bin/bash' > alx
echo 'echo "ALX"' >> alx
(We've created the above contents for the alx file using Emacs)
vi school
(type "i" to enter into insert mode and paste the required statements for the school file. Enter Esc:wq to save and exit vi) So these are two ways to create contents for a file using either Emacs or Vi.
git add .
git commit -m 'commit_message'
git push

Q3. To create a branch and move into it automatically, use: git checkout -b name_of_branch
git checkout -b update_script
cd bash
touch 98
vi alx (make the necessary changes)
vi school (make the necessary changes)
cd .. (return to the 0x01-git dir)
git add .
git commit -m 'required_commit_message)
git push

Q4. Go to Github, click on README.md, update it with a new statement', commit with a statement, save changes
move to the alx-pre_course repo usin:
cd .. 
or cd alx-pre_course
type: git pull (to get changes made on git)
Alternatively, move to the alx-pre_course repo, update the README.md, add, commit and push. 
vi up_to_date
content of the "up_to_date" file should be "git pull"
git add, commit and push

Q5. To change to your main branch, use the command: git checkout main
or: git checkout master
cd bash (make the necessary changes)
cd .. (return to the 0x01-git dir)
Use "rm -r" command to delete an non empty directory. So: rm -r js
git add .
git commit -m (required_commit_mssage)
git push

Q5. git merge update_script 
conflict. change directory to the bash directory with the conflict. Both version if the main branch and update_script brack would appear. You're supposed to resolve this conflict by choosing the version if the update_script. Update the version of the main branch to be the same as that of the update_script. 
git merge update script
(it will merge this time around with no iusses)
add required commit message
git push

Q6. vi .gitignore
cat .gitignore 
~ Emach file
Esc:wq
