1.	List three major version control software for software engineering.
 	git: it tracks changes that were made
	AWS codeCommit: literly git but published by amazon 
	Mercurial: search systems and backup allow for a high level of orgaination

2.	What are the main advantages to using Git in your software development, and how is it useful for game developers.
	git allows working with outhers in a quick and efficient manner this is because it tracks and logs changes made so if something gets messed up you can revert back to a old verson
	it is useful for game delvelopers beacuse it will allow more then one person to work on the game at the same time and when they are done it can intelgenty merge there work together

3.	Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge
	branch it relates to the section where your changes are saved 
	pull it relates to downlowing any changes that have been made 
	push commits your changes to the repostory 
	repository is the central storage location for all the files and allow you to track them
	working copy is the copy without a merge conflict and the latest up to date bug free verson 
	merge is where to different versons come together

4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
	policies relating to file managment and saving because git allows you to save files you will need to use these policies

5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
	visual stuido code 
	notepad
	git desktop
	any other text editor bacause you can manualy go in and remove the code thats giving you a problem 

6.	In a merged source code file, how does Git let you know there is a conflict?
	when git detects that the same line of code has been changed in the two different versons it failes to merge and gives you a error asking you to resolve it 

7.	What are the steps you can take to resolve Git conflicts?
	by going into your text editor than finding the lines of code that is causing the errors than removing one of the conflecting lines after all the errors are corrected remove the 	git formatting and save the file 

8.	What does git revert do, and how can you use it?
	git revert is a safe way of undoing changes by making a new commit with the changes removed
	you can use it by doing git revert and than doing all the normal steps the you would do for a normal commit

9.	What does git reset do, and how can you use it? 
	git reset takes you back to the specified commit and deleates all commits made after the specified commit
	you can use it by doing git reset and then the name of the commit 

10.	What is the difference between git revert and git reset?
	git revert allows you to undo it's effects where as reset is perment 

11.	True or False: It is okay to commit broken code to the main branch.
	false you should commit it to a sub brance like devloment to make sure it works and fix any problems 

12.	True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
	True doing this is a good pratice because co workers can look over the code and adjust the code seperalty  

13.	Describe what is DevOps, how is it useful for game developers?
	DevOps is a set of tools and practices that developers follow and use this can be helpful for game devlopers because they use things like item tracking, version control, and CI/CD  	build pipelines these help inprove improve communication and collaboration with in the groupe improving productivity.
	
14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
	git hub allows for verson control and easy file canahing and saving
	AWS CodePipeline help automate your releace pipeline 
	terraform allows easy cloud infrastructure and security    

15.	What is CI/CD and how can it be used to automate the game development process?
	it aims to streamline and accelerate the software development process by automateting the manual human intervention traditionally needed to get new code from a commit into it's 	final stage this speeds up the production process
