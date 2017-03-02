## Welcome to Git-Tutorial

This is a sample repository just for tutorial purpose owned by Mobile Development RISTEK 2017.

#### Why Git ?
Some of us perhaps try to complete a project. Most of time, we will work on it with our team. If we do the traditional way to collaborate with team, we usually found an incident which lead us to depression. I can say some problems that might be found below.

- We find some files saved in portable storage is corrupt and must ask for the new one
- We do copy partner's code, yet our works is replaced :(
- We need to backup our files with different version because of our company's vision going change. Then, a year later we are instructed to continue the project, but we don't know which version has the function A, B or C. As a result, we need to learn it one by one and got blamed by the Manager because we can't deliver the product on time. Finally, **get fired** :((
- We get partner's code to be merged with our works. However, it is corrupted and we don't know about it; copy that merged files on server. Server is down because we has messed it up. Get blamed by the other engineers, then **friendship is broken and get fired** :'((

Therefore, Git is important for us even we only work alone. It prevent your files to get corrupt, containing virus, and forget to have any changes.

#### Basic Usage of Git
Git provide us ease to do synchronization with others' works. On Git, we know three level of directory : Working Directory, Staging, and Git Repository. Actually, Working Directory and Staging are placed on your local machine. Staging section is ready to be synchronized to Git Repository online. Here are some basics of Git command. Hope you get a better insight.

- ``` git clone ```
This command has purpose to initiate your project on local machine. Duplicating them on local machine so you can edit it later.

- ``` git pull ```
this pulling command is to synchronize your local machine to Git Repository. We can say, it download the changes on the current branch on Git.

- ``` git add ```
git commit let you to move any changes, addition, and removing action from working directory to staging. It is still located on local machine.

- ``` git commit ```
this command will let you to give any comments related to the changes. Note that you need to do '''git add''' before commit.

- ``` git push ```
push to Git Repository. From your staging section including any changes has made and the comment, upload it to current branch of Git Repository that you work on.

- Further command please visit [Git References on Vogella](http://www.vogella.com/tutorials/Git/article.html)



