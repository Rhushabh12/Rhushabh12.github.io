# Hosting a Resume on static site

## Purpose
The purpose of this README is to explain how to host and format a resume in a markdown file using software like GitHub pages, and Jekyll. The language that we will be using for formatting our resume is the markup language. I will using the general principles of current Technical Writing, which is explained in Andrew Etter’s book “Modern Technical Writing”. 

## Prerequisites 
*	A resume formatted in Markdown.


## Instructions, including animated GIF
![Resume](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/resume.gif)
*	### GitHub Pages
    * **Account creation and creating a repository.**
        1. Create an account on [GitHub](https://github.com/). 
        2. Create a new repository, the name of the repository should be in this **Git_user_name.gitgub.io** format. The username can be found in the right-top corner. However, if you are not able to find, how to access your repository. Logo: ![Drop](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/logo.png) check for this logo in your screen. When pressing it will show a dropdown menu, look for the "your repositories" option. This will take you to your repositories, then press on ![new](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/new_repo.png) this button. 
        3. After naming the file, you can put some descriptions for this repository if you want in the discription box, as it is optional. 
        4. Set this repository public so when any employer wants to see your resume, they can access it through the link provided.
        5. Then the last option is to add a readme file, check the box which says “**ADD a README file**”.
        6. Then the last step is to create it by clicking on the button “**create repository**”.
    *	**Adding your resume to the git-hub** 
        *	There are a few ways for adding and creating a file on git-hub, I will be showing one easy way.
            *  	Creating from git-hub 
                1.  Open the repository that we created, there is an option available of "**add file**", click on this ![Addfile](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/add_file.PNG) option. The option "**Create new file**" will let you create a file, and the option "**Upload files**" will let you upload the file from your device.
                2.	In the "**Create new file**" option, there is a option for naming the file. Make sure to use correct format while naming it. 
                3.	Add the content in the file.  
                4.	Adding the description is optional however, it is important when doing big group projects for tracking the progress. Then press on the ![Commit_new_file](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/commit_new_file_logo.PNG) button and now the file can be seen in your repository.
    *	**Option for editing on GitHub pages**
        1.	In the repository, click on the file you want to edit.
        2.	Navigate the pencil ![Pencil_icon](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/pencil_icon.PNG) icon on the screen, which will be on right-hand side of the screen below the “**go to file**” button.
        3.	Mouseover that icon and it will say edit this file.
        4.	After clicking on that pencil icon, it will take you to the edit page.
        5.	On this page there are few good options available, the default screen will show you the edit file screen.
        6.	The first thing we will need is to name the file. There is a dialogue box that says “**Name your file…**” click there. Now there are few different formats that we need to keep in mind. For resume, the name of the file should be **index.md**, the README file should be the standard all caps **README.md** and the last file which I need is “**yml**” format file, I will explain that format in the Jekyll part.  
        7.	Besides the edit file option there is a ![Preview](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/preview_option.PNG) option for instance, if I do the formatting in markdown then I can see how it will be viewed on the screen in that preview option.
*	### Jekyll
    Static websites are good, it does not have any installation, no database, and nothing else to install. There are many static site generators that exist, I am using Jekyll which is also suggested by Andrew Etter.
    1.	The first step is to create a file named “_config.yml”. You can copy-paste ![filename](https://github.com/Rhushabh12/Rhushabh12.github.io/blob/main/jekyll_file_name.PNG)the name while creating, as the naming part is very important in Jekyll. 
    2.	In the "_config.yml" file you will see a line of code, that code is for theme purpose without the yml file there will be no theme. After we are done with all the steps, you will be able to see the resume on a static site.
    3.	When you are done with creating the yml file last thing is to check all the file names.
    4.	Even if you have named it something else it can be changed by editing the file (refer to "GitHub pages” above).

*	### Last checking
    1.	Name of the repository “git_user_name.github.io” in this format.
    2.	Resume is in the file named “index.md”.
    3.	The name of the yml file is “_config.yml”.
*	### Running 
    1.	Copy the name of the repository and paste in it on any browser (search URL) and now the resume can be seen on the site. 


## More Resources: include: 
1. A Markdown tutorial: [Language-Tutorial](https://helloacm.com/markdown-markup-language-quick-tutorial/)

2. A link to Etter’s book: [Book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

3. Using Jekyll with GitHub pages: [Tutorial](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll) 

## Authors and Acknowledgments: credit template authors and group members
Andrew Etter: [Book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
## FAQs Add (and answer) two FAQs, as described below:

1. "Why is Markdown better than a word 
processor?"
*  Markdown is very easy to use, with no complicated syntax, very few features, and can easily implement well-formatted content. 

2. "Why is my resume not showing up?"
*  Firstly, check the naming of the repository and files, are they the correct format? Then check if there is an error in the “_config.yml” file.

