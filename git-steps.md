Project/Group Setup:
- Team Lead will create a reposoitory 
- Every member will fork and clone the repo
<!-- - git remote -v  -->

Step 1:
- Ensure you are in the correct folder
- Set up upstream:
- (ONLY ONCE) git remote add upstream
```<url of upstream>```

Step 2:
- (EVERYDAY) Make sure you are up to date .
- Command : git pull upstream main.

Step 3:
- Create a new branch
- Command: git checkout -b
```<your branch name>``` eg. Sharifa-create-md-file

Step 4:
- Work on the feature
- Make changes .
- Code

Step 5:
- Once you are done, push your changes 
```git add .```
```git commit -m "message" ```
``` git push origin <my branch name> ```

Step 6:
- Delete your branch from your terminal
- git checkout main
- git branch - D 
``` <your branch name>```

Step 7:
- (Repeat 2-7)