# Samara Augustin IS117-001 A03
## Part One
### Directions on Using Webstorm/Git/Github
1. In order to use Webstorm, it must first be downloaded on your computer. 
To use several of the benefits that Webstorm provides you must have the professional version rather than the community version. 
In order to acquire a professional license, use the following link to apply for a student license which will allow you to download the professional version of webstorm. 

1. Fill out the necessary information and once 
your account has been created you can now install webstorm on your computer.
Link: https://www.jetbrains.com/community/education/#students 

1. Go to the Github website to create your account. Use the following link to access the website: https://github.com/ 

1. Go to the downloads page of Git to install Git on your computer, use the following link:
https://git-scm.com/downloads

1. Now that you have Git and Webstorm installed on your computer and your Github account is set up, let's connect Git to Webstorm. First open up Webstorm, 
then go to Webstorm’s settings which can be accessed by pressing the (Ctrl+Alt+S).

1. Afterwards, go to Version Control and press Git then choose the location where the git.exe file is located.

1. In order to ensure that Git is successfully connected to Webstorm, after completing the previous steps there should be a message that is displayed, “Git Executed Successfully”.

1. Exit settings.

1. Once Git is successfully connected to Webstorm, let's make a new project. Press the “Create New Project” button on Webstorms intro page and choose the file location. 

1. Make changes to the folder by adding/removing/editing files. 

1. Once your work is ready to be committed to Github, access your Github account and create a repository that you want to store your code in.

1. Go back to your Webstorm and open up your terminal and make sure that you are in the folder where your files are located.

1. Use the command “git init” to initialize git in your project folder.

1. Github provides a git link to the repository, which can come in the format of 
“https://github.com/username/repositoryName.git”. 
Copy that extension and use the following command in the terminal to 
connect your webstorm project to your repository “git remote add origin https://github.com/username/repositoryName.git”. 

1. Use the command “git add .” to prepare to add all of the files in your folder to your repository. If you want to add only specific files then use the command “git add filename” .

1. Use the command “git commit -m “message””  to commit the changes that you made to your files.

1. To officially process your files to github use the following command “git push”, if your current branch does not have an upstream branch use the following command to push your files to github "git push --set-upstream origin master".


## Part Two
- __Branch__\
A branch is a copy of a program, which allows for a user to work on a program without altering the original source code.
- Clone\
In terms of computing, a clone is a product (hardware or software) that performs in the exact same way as another product. In Github, cloning is to copy all of the content/data from a repository.
- __Commit__\
In computing, to commit is to process the current state of code including recent changes to a record history of changes.
- Fetch\
To fetch is to retrieve data from a location. In Git, to fetch is to retrieve commit history, resources, and files from the remote repository to a local repository.
- __GIT__\
Git is an open source software used to track the distribution and movements of a file(s). It is commonly used alongisde platforms such as Github to help manage the location and changes made to programs/data.
- __Github__\
Github is a platform that stores and manages data and information in repositories through the use of Git.
- Merge\
To merge is to combine several products/systems into one. In Git, to merge is to integrate/combine several branchs of development into one. This causes for progress made on various branches to be combined and saved to a repository.
- Merge Conflict\
A merge conflict occurs when programs aren't combining seamlessly. In Git, a merge conflict occurs when after attempting to merge several branches Git is unable to fix the differences that the various branches has (1).
- __Push__\
To push is to exert force on something. In Git, to push is to process or upload changes in a local repository to a remote repository, this entails uploading recent commit history to your remote repository (2).
- Pull\
In Git, to pull is to gather the current data or changes in a remote repository and combines/merges the changes with a local repository (2).
- __Remote__\
Remote is the ability to connect to a system through a network link or another source (3).
- __Repository__\
A place where information is stored. In terms of Computer Science, a repository is a place where data/code/information is stored or managed.

References:
(1) https://www.gitkraken.com/learn/git/tutorials/how-to-resolve-merge-conflict-in-git#:~:text=What%20is%20a%20Git%20merge%20conflict%3F&text=A%20merge%20conflict%20is%20an,merge%20commits%20without%20your%20help. \
(2) https://learn.sparkfun.com/tutorials/using-github-to-share-with-sparkfun/all \
(3) https://www.techopedia.com/definition/23696/remote-computer#:~:text=A%20remote%20computer%20is%20a,is%20used%20to%20access%20it.
