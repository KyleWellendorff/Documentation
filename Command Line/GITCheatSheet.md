### GIT ### 

1. General WorkFlow  
   1. Create a new direcotory locally or clone an existing Remote Directory from GitHub
   --Can create folder in windows and GIT BASH there. Or can create in GitHub and then clone it onto your local machine

    ```GIT CLONE https://github.com/KyleWellendorff/Documentation.git```

2. To switch which branch you ar going to be working on: ```RUN git checkout dev```

    You should get output similar to the following. you are now in the 'dev' branch
    >root@LAPTOP-BF177J00:~/real-markets-management/real-markets# git checkout dev

    >Switched to branch 'dev' 
 
3. When you add a file, Run: ``` git add .```
    >this adds all files that are in your working directory into the staging area of GIT. same 'Stage All Files' in SourceTree

4. Once they have been staged, you need to commit your changes: ```git commit -m "This is a test Commit"```

    >This commits the changes. Now you need to Push them to Remote Repo (now that the coede is working, duh).  When working with a lot of people,. you will also need to pull fdown therir changes to your LOCAL repo