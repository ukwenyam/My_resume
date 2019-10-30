# Project Title

How to host your jekyll themed resume on Github Pages.

## Getting Started

These set of instructions will give you a step by step process of successfully hosting a Resume website styled with a Github jekyll theme, and hosted on Github pages. These instructions will take you through the following steps:  
[Prerequisites](https://github.com/ukwenyam/UkwenyaMichael.github.io#prerequisites)  
[Installation](https://github.com/ukwenyam/UkwenyaMichael.github.io/blob/master/README.md#installing)  
[Getting Github Setup](https://github.com/ukwenyam/UkwenyaMichael.github.io/blob/master/README.md#getting-github-setup)  
[Creating a repository](https://github.com/ukwenyam/UkwenyaMichael.github.io/blob/master/README.md#creating-a-repository)  
[Cloning your repository](https://github.com/ukwenyam/UkwenyaMichael.github.io#cloning-your-repository-in-atom)  

And under the instructions for getting your resume uploaded to Github and hosted as a website, the following will be covered:  

[Getting markedup resume into Github](https://github.com/ukwenyam/UkwenyaMichael.github.io#getting-markedup-resume-into-github)  
[Pushing changes to Github](https://github.com/ukwenyam/UkwenyaMichael.github.io#pushing-changes-to-github-repository)  
[Adding jekyll theme and hosting webpage](https://github.com/ukwenyam/UkwenyaMichael.github.io#adding-jekyll-theme-and-hosting-webpage)  



Click on this link see an example of a [jekyll themed resume hosted on Github Pages.](https://ukwenyam.github.io/UkwenyaMichael.github.io/)

### Description of Intended Audience

This instruction set is described for individuals who have little to no experience with Github, some experience using an editor such as Atom, no experience using jekyll. You do not need to know a whole lot about Github or Jekyll to get this working.

### Prerequisites

What things you need to install the software and how to install them

* To begin, you'll need a markdown editor on your computer to edit your resume in.
 *  A great example of a markdown editor is Atom.
* You'll also need a resume edited in markdown, you will need some experience in markdown to edit your resume in markdown. [Click here](https://www.markdowntutorial.com/) for a quick tutorial to get you equiped with all the markdown skills you would need for the purpose of this project.

* You'll also need a Github account.


### Installing

Let's get things started by making sure we have all the software we'll to get this done.
* First we need to install the Atom editor. If you don't already have it installed on your computer, begin by going to this link [Download Atom editor](http://www.atom.io)
* Click on the  Download button to begin downloading Atom.  
![Download button](https://i.imgur.com/XWrGOOC.png)  
* The download should begin immediately.
* Click on the run button.
* As the installation begins, click on the "next"  button until installation commences.
* Click finish when it is complete. Congratulations, you now have atom installed on your computer.
Say what the step will be

### Getting Github setup

If you don't already have an active Github account, don't sweat it. These instructions will guide you to setting up your Github account and creating the repository needed to host your website on Github Pages.
* First head over to [github.com](http://www.github.com).
* Just like signing up for a facebook profile, fill out the information needed to create an account and click on the "Sign up for Github" button
* The following page talks about picking a personal plan for your account. The majority of your work on github you would want to be public. So select the unlimited  public repositories for free  
![Unlimited free](https://i.imgur.com/TcRiuJh.png)  
and then click on "Continue".
* On the next page, you can go ahead and start a new Project by clicking "Start a Project".
* There might be a message about verifying your email address. If you do get this message, go ahead and verify you email before proceeding with the remaining steps.
* After verifying your email, proceed to start a new project.

### Creating a repository

After getting Your Github account up and running, you want to actually start getting stuff on there. One way to do this is by creating repositories and uploading files, Documents, Pictures whatever it is you would like to share on your Github.
* Click on the little cat-like image on the top left corner (Github logo).    
  ![github logo](https://i.imgur.com/8gYpkGw.png)    
* Select the 'New' button next to 'Repositories' to create a new repository.
* Give your repository name which will be the name of the website you're trying to host on Github Pages.
* Feel free to add a description of what the repository is created for
* Next select the 'Initialize this repository with a README option'.  
![Initialize Readme](https://i.imgur.com/su6EGZe.png)  
* Next click on Create repository, and Github will get your repository up and running.
If this is your first repository then
 **Congratulations you just created your first Github repository**. If this is not your first repository, then **Way to go being productive!!**  
 * Finally you want to connect your Github repository to your Atom editor. Essentially what you'll be doing in this step is cloning you repository.

### Cloning your repository in Atom.  
A cloned repository acts as a copy of every file and folder in that repository from github.com on your computer. It is also a link between your computer and your GitHub repository which allows pushing and pulling of files easy.  
* In your editor, press the **ctrl + shift + p** buttons on a PC and **cmd + shift + p** buttons on a Mac. It should open a terminal that looks like this.  
![ctrlp](https://i.imgur.com/Lcx5oFm.png)  
* Type in 'github clone'  
![clone](https://i.imgur.com/h51HPRP.gif)  
* In order to get the clone URL, head over to your repository on Github and select the clone or download button, and click on the clipboard icon to copy your repository link to the clipboard.   
![](https://i.imgur.com/Cs2zAj0.gif)  
* Head back to your editor and paste the link on the text field and click on clone  
![](https://i.imgur.com/6ThNCME.gif)
* Net head over to this URL[github.atom.io/login](http://www.github.atom.io/login) to get the token you would need to authorize Github on Atom.
* Copy the link from the webpage and head back to your editor. press the **ctrl + shift + 9** for PC and **cmd + shift + 9** for Mac to open the git tab. Paste the token copied from the webpage into the token field and hit enter.
* Congratulations you just successfully added git to your Atom editor.  

Now let's get started!

### Instructions for hosting website on Github Pages

What you'll need now is to format your resume in markdown with the Atom. Don't worry about formatting the document with a jekyll theme just yet, we'll handle that later.
#### Getting markedup resume into GitHub  
You will need to completely edit your resume in markdown so it can be read as a markdown file. You will then save the file in the cloned repository so that it can be added to the repository on github.com
1. After editing the resume in markdown, save it as index.md.  
2. Open whatever folder you have index.md saved in, and drag and drop the index.md file to your Github repository.  
![](https://i.imgur.com/oeRpBN8.gif)  
#### Pushing changes to Github repository
After making changes to a file in your cloned repository, for that change to actually show up on github.com, you will have to push the change so it reflects on the repository. A commit message just tells you what changes was made to this version of the file that is being pushed.
1. To officially add the changes to your github, head over to the git tab on the lower right corner of the screen.  
![](https://i.imgur.com/MjhxoZQ.png)  
2. Click on the stage all button, then add a commit message to tell you what you updated later, click on commit to master, and then click push.  
![](https://i.imgur.com/D7Uft65.gif)  
This step is what you would use when updating things on your editor and pushing the changes to your repository on Github.
#### Adding jekyll theme and hosting webpage
Now that you have successfully pushed your index.md file, the next step is to style the file with a jekyll theme on GitHub.
1. On your GitHub repository on github.com, the file index.md should be available. To change the theme of your resume, click on settings and look for the 'change theme' button at the bottom of the settings page. Github gives you a hand full of themes to work with, but you can always find more from other sources. select on of the themes and click the 'select theme' button.
2. Rename the repository to whatever you want your resume website to be called, and then add '.github.io' to the end.  
![](https://i.imgur.com/1lQwjZ9.gif)  
3. Scroll down to the buttom of the page until you see a link that looks like this:  
![](https://i.imgur.com/J5BzRnD.png).  
If the link doesn't have a green check mark on the side, just reload the page and it should be checked. That is the link that was generated and hosted by Github Pages to your resume website.


### More Resources  
You can always find more jekyll themes to work with. Some themes have prerequisites that will be stated in their README file, so take a look at those and see their descriptions. Some themes even have a preview you can look at to get a feel of what it's like.  

Heres a [link](https://rubygems.org/search?utf8=%E2%9C%93&query=jekyll+themes) with a lot of jekyll themes to pick from.  

### Authors and Acknowledgments
* Billie Thompsom - _README Template_ - PurpleBooth
* Nguveren Azoom - Project Group Member
* Casey Hildebrand - Project Group member
* Christina Penner - Course professor.


### FAQs
Q. Do i need an existing GitHub repository to connect to Atom  
A. No, you don't need to have an existing repository. Atom allows you create a new repository which you can upload your files to. Check out [this](https://www.youtube.com/watch?v=KA9xvKQXXzQ) video on how to do this.  

Q. Can i customize the jekyll theme?  
A. Yes you can. Github allows you add your own CSS code to the themes so you can add whatever you want to it. Check out [this](https://help.github.com/en/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll#customizing-your-themes-css) file that descrives how this can be done.
