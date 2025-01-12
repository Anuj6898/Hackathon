# Top Issues
1. No delete button for tasks
1. UI of settings page is overflowing
1. Responsiveness is not proper
1. My profile page is still incomplete
1. Set wallpaper has dummy values for tasks
1. Find more on [issues page](https://github.com/Algorithmics001/Hackathon/issues)


# Steps to contribute to this Project:
## 1. Install Git & Github
You can do it by following this [video tutorial](https://www.youtube.com/watch?v=MFtsLRphqDM)

## 2. Fork this repositry to your own Github account by:
-Create a 'fork' of Algorithmics/Hackthon.
![alt text](./ImagesForREADME/fork.png?raw=true)
Or use gh for forking
```
gh repo fork Algorithmics/Hackthon --clone
```

## 3. Clone your forked repositery
- Goto your own github page and you will see repo named hackathon
```
github/YourUserName/Hackathon
```
- Copy the URL and run the following command on your cmd:
```
git clone URL
```

## 4. Set up development environment
- Install choco, jdk11 and android studio+sdk by reading [this documentation](https://reactnative.dev/docs/environment-setup) with react native CLI ***not expo***

- Change your directory to the directory where you have cloned the repo
```
cd /your-directory-path/Hackathon/code
```

- Now run the the follwing command to install the required modules for this react native app
```
npm install
```

## 5. Run this app on emulator or android device
- Now run the command
```
npm start
```
- Now press a for running it on android emulator

## 5. Make the required changes you want
- **Always sync fork** on your cloud github repo and run git pull command if any changes are there in remote but not on system
- It is suggested to create a new branch for new change 
- If you are not comfertable with branching process you can do it directly
- Just make the require changes and run the following commands
```
git add .
git commit -m "Write about what changes you have made"
git push
```

## 6. Pushing to the origin or original project repo
- Goto you github hackathon repositry
- Press contribute button
- Write about the changes you have made or issue you have solved
- and create pull request
![alt text](./ImagesForREADME/sync%26pull.png?raw=true)
- We will examine for any discrepensies or any conflicts before merging your pull request.

## Congratulation!!! you have made up to so far if you are still reading


# Tech-Stack 
1. React Native(frame work)
1. Android Studio
1. Github desktop
1. Visual Studio code
1. iconkitchen(for generating app icon)

## Requirements
1. node
1. Git CLI & Git Bash
1. run this command if error about react-scripts occur 
  ```
  npm install react-scripts --save
  ```




### Refer to the following for more instructions.
1. [GitHub CLI](https://cli.github.com/manual/gh_repo_sync)
1. [Git Bash](https://git-scm.com/docs)

## PRECAUTIONS
1. Never push or commit changes directly in main branch.
1. Never push or commit changes without checking status and fetching origin.
1. Check your branch before push or commit. (use git reset * command if commited in wrong branch, this will undo the git add .).

# IDEA

### The idea is to devolop a smart to-do application using React Native
The user, after downloading the application will first answer a questionaire. And input the tasks that he wants to do. The app will suggest the best time to start the task. 

### Following features are to be included in the below versions:



## Version - 1
1. <u>Desgine UI/UX:</u> The UI for the app will be very minimalist and easy to use. This will reduce the friction of interacting with the app. The UI will have:
    1. Welcome/Get-Started page
    2. Questionaire page
    3. Add task page

1. In this version we will only ask 10 questions to the user.
1. This will allow user to add, edit, delete tasks.
1. The task list will be shown on the wallpaper of your android device (in case there are too many tasks the wallpaper will be scrollable, User will have the option to keep or remove this)

## Version - 2
1. UI will be improved and new features will be added.
1. Impliment the algorithm that will take into account these following factors:
    1. Daily activities (asked in questionaire) 
    2. Duration of task 
    3. Prioratize tasks based on user's input (there will be three level user can choose when writing a task: 1, 2, 3)
    4. User will have the ability to over-write any suggestions.

## Version - 3
1. Task will be automatically prioratized based on their type (Ex: It is more important to finish a pending report at work than getting a haircut)

## Version - 4
1. <u>Task Prep feature:</u> Before doing a task the app will notify you to perform some simple preprations (Ex: The task is to study for math exam at 5 P.M. the app will notify you at 4 P.M. to keep your books, notebook and pen on the table.)
1. App will also take into account any holidays and weekends and suggest tasks based on the data (App will have a calander with all the important holidays etc.)

## Version - 5
1. A screen monitor will be added to monitor user's screen time and alert him if he is spending more time than the set limit.
1. App will be made cross-platform and will be automatically synronised on all devices.

