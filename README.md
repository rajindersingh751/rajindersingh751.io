# Hosting your resume on GitHub pages

## Purpose
The aim of this document is to provide the reader with a tutorial on how one can upload their resume on GitHub Pages using a Markdown editor and Jekyll. These changes will be made by utilizing the principals in the *Modern Technical Writing* by Andrew Etter. 

### Motivation for the reader
There are three main reasons why are we are doing this activity, the first being the importance of static websites, the second being the use of a Lightweight Markup Language (LML) and the third being the integration of an LML into a static site generator like GitHub Pages in such a way which promotes engagement from viewers to host a distributed file sharing system among themselves. One can read more about the importance of LML in the FAQ's section at the end of the document.

Andrew Etter states that static websites since speed, simplicity, portability, and security. Static websites offer unbeatable portaibility since there are very few moving parts such as plugins and do not require any server-side application dependencies, and therefore increasing security of the overall site. Static websites are great for someone looking to this kind of project to showcase their resume or provide a source for documentation for any caliber of a project.  

The reason behind the decision of hosting your project on websites like GitHub Pages can be further described from the sections with the title *Build a Website* and *Help Others write* Andrew mentions that  

> “Hosting your content on a website gives you the power to fix inaccuracies almost instantly and keep your content in sync with the latest software release.”  

And this is very relatable to everyone, since we all have files ending with a number which means that we have a previous version of it downloaded already on our machines. To avoid this Andrew suggests to upload everything in HTML format, and to upload in such a way that people will be happy to share their expertise with you relevant to the topic of discussion. This will not only open many avenues for the discussion but also help develop the documentation since you are getting lots of perspectives with people who could be from a variety of backgrounds.  

## Prerequisites
Before we get started with uploading files and styling our GitHub Page, we need to know how to use GitHub Flavored Markdown and Jekyll. The knowledge to use both of these technologies are provided with a link in the More Resources section of this document.

## Instructions
This section provides an end to end, detailed steps on how one can host their resume on GitHub Pages and change the visual theme for the document.

### Getting Started with the basics  
1.	Log in or Create your GitHub account, then click on Create a repository.
![img](/Assets/create-repo.jpg)  
2.	Now we will make the changes as shown in the image below:
Note: Make sure the repository name is "<yourusername>.gitgub.io".
![img](/Assets/repo-settings.png)  

### Changing the Settings     
3.	Navigate to the settings page and Scroll down until you see the “GitHub Pages” section as shown below. Under the source tab, set the branch settings to Main and then click on “Save” to update your settings. 
![img](/Assets/repo-theme-change.png)    
### Choosing a Theme    
4.	 Now click on “Choose a theme” which will redirect you to a new Page. At the top half of the Page we are going to navigate the carousel until we get to the “Tactile” theme and click the button Select Theme, this will initialize the theme and make the changes accordingly to your file.  
![img](/Assets/theme-carousel.png)  

### Creating the index file  
5.	Now we are presented with the following screen which prompts to show a new file and we are going to rename it to “index.md.” This will be the index file in our repository which will store our resume for viewing. Below in the editor we can see a template file which shows the features provided with a Markdown File. You can make your necessary changes and click on Make changes to update the file.    
![img](/Assets/theme-edit.png)   

### The Final Product  
After making the changes as described above, you should end up with a final result as shown below.  
![ResumeGif](/Assets/resumeGif.gif)


## More Resources
* [GitHubPages Tutorial](https://guides.github.com/features/pages/)  
* [Markown Tutorial](https://www.markdownguide.org/)
* [Jekyll Tutorials](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB) 
* [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)    


## Authors and Acknowledgments
Authors  
* **Rajinder Singh** - Template Author   
* **Emily Nguyen**   - Peer Editor    
* **Charina Duenas** - Peer Editor 
* **Mohammed Anjum** - Peer Editor 

## Acknoledgements 
* [Jekyll Tectile Theme](https://github.com/pages-themes/tactile)    


## FAQ's
### Why is Markdown better than a word processor?  
Although Microsoft Word is a fantastic application for the end user, but any aspiring programmer should take the initiative to look into Markdown as it is a great tool to publish Documentation which can be updated on most devices. Markdown has many advantages over Word but the major factor being easier to read and easier to write in plain text format which is very close to plain HTML. These advantages aid the programmer to produce some documentation to maintain its lifespan, since the editor can make changes on the fly and eliminates the need for the end user to download a disposable copy which are considered as waste since they are disposable. 
 
### Why are we using  LML as opposed to HTML?  
A lightweight Markup Language (LML) is a type of language which was originally meant to augment HTML and its main focus was to encourage developers to produce documentation for their projects. Overall Markdown is very simple and requires almost no coding knowledge. In our tutorial we are going to use StackEdit which is an online live Markdown editor where one can make their changes and view them live, the other reason why I chose this is because it supports file export which is a very helpful feature and we are going to demonstrate how to use this feature in the demo section of this document.  
