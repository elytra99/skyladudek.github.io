# How to Host Your Resume on GitHub Pages with a Jekyll Theme

This project displays an example of a resume created on Markdown that is formatted with a Jekyll theme. It also contains this README file in the GitHub pages home repository. This will give you instructions on how to host your own resume on GitHub pages with a Jekyll theme, write your resume in Markdown using Atom as a text editor, and format the Jekyll front matter for your theme.  

## Intended Audience

This instruction set is for absolute beginners. You require no previous experience with Markdown, GitHub, Atom or Jekyll to be able to follow these instructions. 

### Prerequisites
In order to complete the described task you will need:

*   A working computer with Internet 

*   [Atom](https://atom.io) (a text editor) installed on your computer

*   Your own [GitHub Account](https://github.com)

### Instructions
After you have done the necessary setup in the prerequisites section, you can now get started with writing your resume in Markdown.
#### Create your own Resume using Markdown

1. Open up your installed Atom application

2. Open a new file in Atom  
  a. Select `<File>` in the top left corner of Atom.      
  b. Select `<New File>` from the drop-down menu.   
  
3. Write your resume using Markdown syntax in the newly created file.   
    Markdown is a simple Mark*up* language used to create text files.  
    For more information on Markdown's Syntax for your resume please refer to this [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) by [Adam Pritchard](https://github.com/adam-p). For example, you can:
    * Use Markdown headers to make headers in your resume such as "Education", "Work Experience" etc.
    * Use Markdown lists to create a list of your skills.
    * You can insert Markdown links onto your resume since it will be published online.

4. Save your new Markdown resume   
  a. Select `<File>` in the top left corner of Atom.   
  b. Select `<Save As>` from the drop-down menu.     
  c. Save your resume as FirstNameLastName.md wherever you'd like in your computer.

#### Host your Resume on GitHub Pages
Now that you have your own resume in Markdown, we can host (publish) the file on a GitHub webpage. 

##### Create a new repository on your GitHub account
1. Login to your GitHub Account            

   Once you have logged in, you should be on the `<Overview>` tab,    
  
2. Click on the `<Repositories>` tab to the right      

![](https://github.com/skyladudek/skyladudek.github.io/blob/master/images/Repositories.png)

3. Add a new repository

![](https://github.com/skyladudek/skyladudek.github.io/blob/master/images/New.png)

4. Name your repository `<user>.github.io` 

5. Make your repository public so everyone will be able to view your resume online.

6. Select the checkbox to "initialize your repository with a README".

7. Click "Create repository".

###### Use your new repository to host your Markdown resume on GitHub Pages
1. On GitHub go to your site's repository

2. Select "Create new file" 
![](https://github.com/skyladudek/skyladudek.github.io/blob/master/images/Create%20new.png)

3. Create a new file called `index.md`. This file will contain the content you want to be displayed on 
   the GitHub page, in this case, your Markdown resume. 

4. Under "Edit your file", you can copy the text of your Markdown resume file, and paste it in the textbox below

5. Scroll down and select "Commit new file" 
![](https://github.com/skyladudek/skyladudek.github.io/blob/master/images/Commit%20new.png)

6. Under your repository, click `<Settings>` and scroll down to the header `<GitHub Pages>`

7. Click your site's URL to see your published page. Or. you can type the link `http://username.github.io`        
   into your browser to view the page

#### Apply a Jekyll Theme to your Resume
Now that your page is up, you can apply a Jekyll theme to make the aesthetics of your resume look less plain.

1. Go back to the `<Settings>` tab in your repository

2. Scroll back down to the `<GitHub Pages>` header 

3. Select `Choose Theme` under `<Theme Chooser>` 
  
4. Explore the themes on the page and select the one you want - the resume for this repository uses "minimal"

5. Click the `Select Theme` button to apply the theme

6. Visit your GitHub Pages webpage to view what the applied theme looks like. You can repeat Steps 1-4 by  
   clicking `Change Theme` under `<Theme Chooser>`.

#### Format the Jekyll Front Matter to Edit the Jekyll Theme
Now that you have a theme selected, you can edit the Front Matter of the theme to 
better reflect what should be displayed on your webpage.

1. Go back to the `<Code>` tab in your repository

2. Click on the `<_config.yml>` folder

3. Click the pen icon to edit the file 
![](https://github.com/skyladudek/skyladudek.github.io/blob/master/images/Pen.png)

4. Edit/add to the content of the file such as "title" and "author" to personalize the front matter according to yourself.
   You can read about Jekyll's front matter more [here](https://jekyllrb.com/docs/front-matter/)
```javascript
"title: Resume for <Your Name>"
```
5. Scroll down and select `Commit changes` when finished 
![](https://github.com/skyladudek/skyladudek.github.io/blob/master/images/Commit%20changes.png)

You should now have your resume hosted online with GitHub pages using a Jekyll theme and custom front matter :smiley_cat:

### More Resources  
[Create](https://github.com/) your own GitHub account  
[Download](https://atom.io) Atom for free  
[View](https://jekyllrb.com/docs/variables/) a list of Jekyll front matter variables you can use 
[Discover](https://help.github.com/en/github/working-with-github-pages) more things you can add to your GitHub webpage!  

### FAQs 
**Why aren't changes on my webpage showing up?**

Changes on your webpage such as choosing a new theme may take a few minutes to 
show up. Just wait and refresh the page.

**Why isn't my Markdown file rendering properly even though my syntax is correct?**

Certain things from your Markdown file such as tables may not show up correctly 
on GitHub correctly because GitHub uses a specific "flavour" (standardization) of
Markdown. Visit https://github.github.com/gfm/ for a specification of GitHub 
Flavoured Markdown syntax. 

### Authors and Acknowledgments
[Skyla Dudek](https://github.com/skyladudek) :mushroom: - Author of Resume and instructional README file  
[Emily Nguyen](http://github.com/emily0906) - :coffee: Peer editor and discussion member  
[Anna Stacey](http://github.com/ajstacey24) - :turtle: Peer editor and discussion member  
[Jekyll minimal template authors](https://github.com/pages-themes/minimal) - All contributors to the Jekyll 'minimal' template
