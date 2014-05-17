---  
title: Emily Sun's Lab Notebook  
author: Emily Sun
date: May 12, 2014  
--- 

# Labs

## Zotero
Had to download Firefox because it works better with Zotero than Chrome

Why is it that on some webpages, Zotero will allow me to “Create Web Page Item from Current Page,” but other times I can’t do so? It’s very confusing.

Note: I do kind of like manually entering in my citations. I find it relaxing. Obviously I see the appeal in Zotero, but I do sort of miss the old school version.

## Command Line Prompts
rmdir – you have to be a level ABOVE the file you want to remove

I don’t really understand pushd and popd

"Moving" files is really just renaming them

Have gotten to (not including) Moving A File (mv)

## Version Control with Git
URL: [http://try.github.io/levels/1/challenges/1](http://try.github.io/levels/1/challenges/1).

Code School’s Git tutorial is really nice

Why do I have to enter “git” before every command?

Is code school “working” alongside me? Is that while files are added in the octobox repository in between steps?

Note: good to run “git status” often

You don’t have to type out anything: just click on the arrow by the instructions and it types out the instruction for you in the terminal window!

**Directory:**A folder used for storing multiple files.

**Repository:**A directory where Git has been initialized to start version controlling your files.

**staged:**Files are ready to be committed.

**unstaged:**Files with changes that have not been prepared to be commited.

**untracked:**Files aren't tracked by Git yet. This usually indicates a newly created file.

**deleted:**File has been deleted and is waiting to be removed from Git.

**add all:**You can also type git add .. The dot represents the current directory, so everything in it, and everything beneath it gets added.

**git reset:**You can use git reset <filename> to remove a file or files from the staging area.

I don’t *really* understand what the “stage” in Git is

Wildcard = symbol used to replace or represent one or more characters. **Wildcards** or **wild characters** are either an asterisk (*), which represents one or more characters, or question mark (?), which represents a single character.

**git remote:**Git doesn't care what you name your remotes, but it's typical to name your main one origin.

It's also a good idea for your main repository to be on a remote server like GitHub.

I have no idea what Git “hooks” are

“The name of our remote is **origin** and the default local branch name is **master**. The **-u** tells Git to remember the parameters, so that next time we can simply **run git** **push** and Git will know what to do.”

Takes a couple seconds for Git to execute commands

By default **HEAD** points to your most recent commit.

I don’t really understand the things that show up in the terminal when I execute commands. Ex:
@@ -1 +1 @@
-A Tale of Two Octocats
+[mA Tale of Two Octocats and an Octodog

You want to try to keep related changes together in separate commits. Using **'git diff'** gives you a good overview of changes you have made and lets you add files or directories one at a time and commit them separately.

I don’t really understand the explanation for “--“

I don’t really understand creating in additional branch “clean-up” outside of the master branch? Why can’t you just work inside the master branch directly?

A **pull request** allows the boss of the project to look through your changes and make comments before deciding to merge in the change. It's a really great feature that is used all the time for remote workers and open-source projects.

You can use **git branch -d <branch name>** to delete a branch

## Markdown and Pandoc
Note: From Professor Wythoff’s “Screen Reading” lab

Files are saved under Emily/Tex

This is really cool!

Some things aren’t formatting correctly, and I’m not quite sure why. Some examples:
* In the PDF version of my file, the image in Subsection 2.3 is actually displayed before the “Subsection 2.3” heading, on its own separate page. Subsection 2.3 is then left blank and is followed directly by the heading for Subsection 2.4.
* In the word doc version, indentations don’t seem to be showing up. “>” and “>>” create indentations in the PDF version but not the doc one.  The text stays aligned right. 

Bullets in a word doc are aligned right with the rest of the text, but are indented in the PDF version. 

I think I like the font in the PDF version better than the word doc.

## Amazon AWS Tutorial
Link: [http://www.lynda.com/AWS-tutorials/Up-Running-Amazon-Web-Services/114888-2.html](http://www.lynda.com/AWS-tutorials/Up-Running-Amazon-Web-Services/114888-2.html)
> Go through sections 1 and 2

Notes: [https://github.com/denten/dhnotes/wiki/Launching-an-AWS-instance](https://github.com/denten/dhnotes/wiki/Launching-an-AWS-instance)

Tip: When you get to launching a service, they’ll give you a list of images
> Search for Debian64
> Make sure you’re using the micro instance (free)

Notes:

Lynda: Up and Running with Amazon Web Services

* WHOA Lynda is so cool! I really like how you can watch a video but also read a full transcript, as I feel that I learn better from reading than from watching. 
* Mac users – SSH terminal is already installed and available through terminal
* Free tier for Amazon AWS is good for beginners
* Introduction to cloud computing:
* What is cloud computing?
* “Use of service for hardware and software resources delivered by a network, usually the internet”
* Delegation of overhead – outsourcing
* Modular, compartmentalized
* Elastic, resilient
* Software as a Service (SaaS)
* Network as a Service (NaaS)
* Infrastructure as a Service (Iaas)
* Platform as a Service (PaaS)
* 1) Introduction to Amazon AWS:
* Cloud computing platform
* Web services provided by Amazon.com
* EC2 is a “compute” service within AWS’ foundational level
* EC2 = Elastic Compute Cloud, is a virtual private service, textbook example of IaaS
* Amazon AWS history:
* Launched in 2002, allowed third party sites to search and display items from Amazon.com
* August 2006 – launched EC2
* In April 2012, a report by DeepField showed that 1/3 of all internet traffic accesses at least one facet of Amazon’s AWS
* An instance is a single EC2 server
* Several EC2 instances can reside on one physical server
* Keeping close proximity improves speed, but diversifying instances across multiple availability zones reduces risk
* Instantiating and Configuring an EC2 Server:
* Amazon uses “compute units” – standardized measurement of CPU capacity
* Bigger = faster

Amazon Elastic Compute Cloud (EC2) is a Foundation Service within Amazon Web Services

Upper right on AWS: will show you where the server is located—choose East US

## Python
Love Learn Python the Hard Way

Does Zed Shaw get paid for this?

I actually think this is better at teaching Python than Columbia's introductory computer science clases