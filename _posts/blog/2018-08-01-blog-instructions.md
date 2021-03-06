---
layout: post
title: "Making a Blog Post"
modified:
categories: blog
excerpt: In this course, you will be invited to share a critical reflection with the public on this course website.  
tags: []
author: halperta
image:
  feature:
---
In this course, you will be invited to share a critical reflection with the public on this course website ([more info](../../assignments)). To do this, you will need to learn how to:
* Create a GitHub account
* Write a blog post in markdown
* Push your changes to the website.

## Step 1: Creating a GitHub account
1. GitHub is an online platform for creating and sharing code. It is owned by Microsoft. You can create a GitHub account here:  
[https://github.com/](https://github.com/)  
2. After you create an account, you'll need to verify your email before moving on to the next step.  

## Step 2: Create an author ID.
You'll need to create an author ID for the website so that your blog post can be attributed properly. To do this, follow these steps:

1. Log in to GitHub and navigate to:  
[https://github.com/halperta/criticalarchives/blob/gh-pages/_data/authors.yml](https://github.com/halperta/criticalarchives/blob/gh-pages/_data/authors.yml)
2. **Important:** Make sure the branch has been changed from `gh-pages-2.3.4` to `gh-pages`. To do this, find the drop-down menu that says "branch" near the top of the page, and select `gh-pages.`
3. Open the file for editing by selecting the pen icon in the upper right corner of the screen. 
4. Create a biographical entry by copying someone else's and pasting it at the bottom of the document, replacing their information with your own info. At the very least, you should add a single-word author id, as well as your name. If you want to have a photograph of yourself to link to the page, enter the file name of the image, including the extension, under "avatar." It should look something like this:  

    authorid: oneword  
       name: Enter Name Here  
       email: email@utexas.edu  
       bio:  
       avatar:  image.jpg  
       twitter:  handle
       google:  
         plus:  

5. **Commit your changes:** Once you've added your own author entry to the file, "propose the file change."  
	1. At the bottom of the page, in the text block where it says "Update authors.yml," enter a brief description of your proposed change. It should be something like: `Added author: Hannah Alpert-Abrams.`  
	2. Click "propose file change."

6. **Merge your changes:** Select "Create Pull Request" to propose your changes. The admin will approve your changes before the site goes live.

*7. (Optional): If you want to include an author photo, please email it to Hannah for uploading!*

## Step 3: Write your blog post in markdown.

[Markdown](https://en.wikipedia.org/wiki/Markdown) is a simple formatting language for writing text. It works a lot like HTML, only it's a lot easier to use.

You'll be writing your blog post in Markdown. That means that you should compose the text (or copy the text) into a *plain text editor*. Notebook is one popular program. I like to use [Sublime](https://www.sublimetext.com/). Follow these instructions to get started:

### YAML header
Your file should begin with a header that looks exactly like this (including the dashes):

```
---
layout: post
title: "ENTER YOUR TITLE HERE"
modified:
categories: blog
excerpt: YOU CAN INCLUDE A SENTENCE FROM THE BLOG HERE IF YOU WANT.
tags: []
author: "ENTER YOUR AUTHOR ID HERE"
image:
  feature:
---
```

### Content
Below the YAML header, you should write the post just as you ordinarily would do. You can find detailed instructions on how to write in Markdown [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), or use the following tips:
```
Headers:  
    # Heading One  
    ## Heading Two  
    ### Heading Three (etc)  

Formatting:  
	*italics*  
	**bold**  

Links:  
	[link text in brackets](url-in-parentheses)

Line Breaks:  
	End the previous line with two spaces,  
	then begin writing on the following line to create a line break.  

Accents:  
	Accents and other diacritics (á, ñ, ü)  
	can be typed into the text as normal.

Lists:
	Use 
		* text
	to create a disordered list.
	Use 
		1. text
		2. text 
		3. text 
	to create an ordered list.

```

## Step 4: Upload your blog post
1. **Log in to GitHub** and navigate to: [https://github.com/halperta/criticalarchives/tree/gh-pages/_posts/blog](https://github.com/halperta/criticalarchives/tree/gh-pages/_posts/blog)  
2. Make sure that you are in the `gh-pages` branch (upper left corner).
3. In the upper right corner, click on the button that reads `create new file`.
4. **Name your file** using the current date. The name should be `YYYY-MM-DD-short-title.md` . For example, this blog post is named `2018-08-01-blog-instructions.md`
5. **Copy and paste** the text of your blog post into the text box. Use the `preview` tab (just to the right of the `edit new file` tab) to see what your post will look like.

## Step 5: Submit your post for review
1. 

## Step 6: Propose your file and merge changes
1. **Propose file:**
	1. At the bottom of the page, in the text block where it says "Create filename.md," enter a brief description of your proposed change. It should be something like: "Posting blog post by Hannah Alpert-Abrams." This is also the process you'll use if you'd like to make changes to the file later.  
	2. Click "propose file change."
2. **Merge your changes:** Select "Create Pull Request" to propose your changes. The admin will approve your changes before the site goes live.

