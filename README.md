# housingExercise
To Pull the repo first time :
Go to the directory and write the following command :
    1. git clone https://github.com/ykb95/housingExercise.git (Go to github repo and copy the clone with HTTPS)
To push the repo:
    2. The above command will clone the entire repo so go to the repo by cd reponame
    3. git add . (adding all types of file)
        3a. If email and name asked : git config --global user.email "ykbnitjsr13@gmail.com"
                                    : git config --global user.name "kryog"
    4. git commit -m "commit_message"
        
        So far, the above steps is what you would do even if you were not using github. They are the normal steps to start a git repository. Remember that git is distributed (decentralized), means you don't need to have a "central server" (or even a network connection), to use git.

Now you want to push the changes to your git repository hosted with github. To you this by telling git to add a remote location, and you do that with this command:

git remote add origin https://github.com/yourusername/your-repo-name.git

*Note: your-repo-name should be created in GitHub before you do a git remote add origin ... Once you have done that, git now knows about your remote repository. You can then tell it to push (which is "upload") your commited files:
        
    5. [Optional Step (Sometime)] git remote add origin https://github.com/yourusername/your-repo-name.git
    6. git push -u origin master

Reference: https://stackoverflow.com/questions/12799719/how-to-upload-a-project-to-github
