# How to host a resume on GitHub Pages

## Purpose 
- This README Markdown file will help you to learn how to format our resuem and host it on static website (i.e. GitHub Pages).
- This file will also connect the guideline of current technical writing written by Andrew Etter to help you to understand the material.

## Prerequisites 
- A resume in Markdown format 
- A GitHub application installed on a computer or using online GitHub website 
- A GitHub account 

## Instructions 
### Some background infomation about Markdown 
- If we check the source file of the README, we can find following symbols:
    - '#' symbols can help us to control the size of heading and sub headings.
    - The *single start* symbol at both sides of word can help us to focus on the important word 
    - The **bouble start** symbol at both sides of word remind us to do some operations with button
    - The '-' symbol can list instructions or details 
    
### Creating repository
1. Log into the GitHub website or application
2. Find **New** or **New repository** 
- Clicking the button will bring us to the create repository page
- This repository will contain the reusme, README, and other files that will decided the appearance design and content of static hosting site
3. Fill in the repository name box same as Owner's name and end with github.io 
- This operation will create a static hosting site which is GitHub Pages.
4. Add an README file into the repository page 
- README file will help reader or future contributors understand the purpose and the operation of this project (i.e. hosing our resume) 
5. Click **Create repository** to end the creation of the repository
    -  When we finish this step, we will at the new repository that we just created
    -  Currently, we will only have one file (i.e. README.md) 

### Adding resume into the repository
1. Create new file by clicking **Add file** or **Upload file**
2. - Choosing **Add file**:
    - Typing or pasting existing resume Markdown file into the *<>Edit file* text box
   - Choosing **upload file**
    - Choosing or draging our resume (which name should be index) Markdown file into the tooltip
3. Make sure the file name is index.md even we choosing **Add file** or **Upload file**
4. Add comment to clarify any changes we made for the file
- This step will help us or future contributors to know what changes have been made and timeline of product update.
5. **Commit changes** will add the resume into the repository
- This step will make sure the content which will be showed on the static hosting website i.e. Github Pages.  
 
### Formatting our resume 
1. Create new file by clicking **Add file**
2. Write theme and title of the GitHub pages by using these two code:
    > theme: jekyll-theme-slate
    
    > title: Our Resume
    - The title will the title of our resume page.
    - This two lines use Jekyll to format our resume on GitHub Pages.
3. Type *_config.yml* as the file name 
- This file contains the style of our GitHub Pages by using Jekyll.
4 and 5 are same steps in **adding resume into the repository**

### Opening the GitHub Pages
1. Add the _repository name.github.io_ into the web search bar
    - Then, it will find our resume which hosted on the GitHub Pages.
    - Note: we can also find our GitHub pages at **Settings** -> **pages**.
### More resources
- [How to create a good Markdown](https://www.markdownguide.org/getting-started/)
- [Morden technical writing introduction dodument](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) which is written by Andrew Etter. 
- [Video about hosting profile on GitHub Pages](https://www.youtube.com/watch?v=fqFjuX4VZmU&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=19) which is created by Mike Dane.

### Image of our resume hosted on the GitHub Pages 
- ![Our Resume](https://github.com/dinokana/dinokana.github.io/blob/main/resume.gif)
## Author and Acknowledgements 
- Author:
 - Hong Gao
- Acknowledgement:
 - Thanks to Cain Stoeke, Adam Kroeker, Johnson Makumator-Jones, and Aman Preet Singh for various suggestions about my README and index files. 

## FAQs

  1. I made some changes on my GitHub Pages, but it does not show immediately. Why?
  - Since there is about 20 minutes latency time for GitHub Pages to get the changes.
  2. Why is Markdown better than a word processor?
  - The most stuff that word processor functions implements can also be realized by Markdown. It also can easy to operate and most of interpreter the Markdown file. Other people have opportunities to contribute the product and provide ideas, and the Word processor can only allow one person to operate the file concurrently.

