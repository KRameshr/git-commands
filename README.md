
Git and GitHub

Git 
Free and open source version control system

Version control
The management of changes to  documents, computer programs, large websites, and other collections of information


Terms 
  Directory -> folder 
Terminal  = an interface for text commands
CLI =  command line interface
Cd = change directory
A code editor and word processor for writing code
Repository = project or the folder/ place where your project is kept 
Git is a tool to track the code and redeploy code (VCS)
Github = a website to host your repositories online


Git  commands

Clone -> bring a repository that is hosted somewhere like GitHub into a folder on your local machine 
Add ->track your files and changes in git
Commit  -> Save your files in Git
Push  -> upload git commits to a remote repo. Like github
Pull -> Download changes from the remote repo to your local 
machine, the opposite of push 

Create a file and open it in CMD in the terminal 

working

Working directory

Create a folder and open it in the CMD

git init
git status
create.txt 


Staging area

    –git add create.txt 
Only send a specific file
 


 local repository 


commit
Send a Group of files 
– git  commit -m “committing”

Remote repository

Push 

Create a new repository in GitHub
Add in terminal cmd enter
Ex – git remote add origin git@github.com:KRameshr/git-first.git
Check the git branch 
Master 
Push 
– git push -u origin master



Creating a branch in the repository 

git checkout -b "copy1"    
git status 
git add 
git commit -m "Committing"
git push --set-upstream origin copy1

From the remote to the Staging area
– git clone <git website link>
   git branches
         Three multiple branches 
 git checkout <brancename>


To move from branch to branch

 git checkout <brancename>
 git pull

git checkout  <brancename>
git merge origin/master
git status







System Design

It is the process of designing the architecture and components of the software system to meet specific business requirements


1. Understand the requirements
2. Define the system architecture
3. Choose the technology stack
4. Design the modules	
5. Plan for scalability
6. Consider security and privacy
7. Test and validate

Conclusion

Overall, system design is a complex process that requires careful planning and attention to detail. By following these steps, you can create a system design that meets the needs of the users and your business.


Tips and Tricks to Solve System Design Problems

1. When you are given a system design problem, you should approach it in a planned manner.
2. Initially, the problem may look huge, and one can easily get confused about how to start solving it.
3. There is no fixed solution while you are designing a system
4. There is more than one way to reach the solution.

Approaching a System Design Problem

1. Breaking down the problem
2. Communicating your ideas
3. Assumptions that make sense 



. We need to ensure that our system is reliable, available, and scalable

Reliable - A system is reliable when it can meet the user's requirements.

Fault Tolerant System

Fault - Faults are the errors that arise in a particular component of the system.
      - An occurrence of fault doesn't guarantee failure of the system

Failure - It is the state when the system is not able to perform as expected.
	- It is no longer able to provide certain services to the end users.


Availability - It is essential for a system to ensure high availability in order to serve the user's request

There are various principles to follow in order to ensure the availability of your system:
 1. Your system should not have a single point of failure.
 2. Detecting the failure and resolving it at that point.


Scalability - It is the ability of the system to cope with increasing load.

If you have to design a system for load X, then you should plan to design it for 10X and test it for 100X


These are various factors that describe the load on the system:
1. Number of requests coming to your system for processing per day.
2. Number of Database calls made from your system
3. The number of Cache hit-and-miss requests to your system.
4. Users currently active on your system






