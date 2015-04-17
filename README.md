# Week 1 day 3 - Git Workflows
##Assignment Overview

This assignment will build upon basic Git knowledge and illustrate a full Git workflow, much like workflows used in production environments. 

**Instructions:**

- **Fork** this repository, which contains an `index.html` file and a markdown file named `README.md`. `fork` is much like `clone`, in that it is a copy of the existing repository, except that you can contribute back to the original project through 'pull requests' (or by pushing to 'upstream' if you have contributor access). 
- Create a new **branch** named 'readme'. This is what is called a 'feature branch' and is used to work on features without impacting the main branch.
- Checkout the "readme" branch. 
- Add a new JavaScript file. 
- Add a new CSS file.
- Edit the HTML file to include your new files.
- Fill out the markdown document, following the GitHub guide [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
	- Explain that this is a basic HTML template.
 	- Explain how to use it, including at least one example,  how to clone it using Git, what the files are and where to add specific types of content.
 	- Add your contact information
	- Add a [software license of your choice](http://choosealicense.com/).
- Once you're completely finished with the assignment, merge your branch back into the master branch of your repository to signal that the "feature" is complete.
- Submit a pull request to *this* repository.


#Contents
##README.md
This is the file you're reading. Add any content you like!

##index.html
This is a HTML that can be used to start a project with some basic framework already in place. When starting a new project, for example about __Batman__, this will give you a jumpstart to get your **Bat-tastic** information out on the web quicker. To use the HTML document, make a clone to your computer. Here are some helpful steps to get you going.

1. Pull up terminal on your computer
2. Use 'mkdir <name of directory>' to create a directory where you would like to store your awesome Batman website 
3. Use 'cd' command to change into this new directory
4. Use 'git clone <url>' to pull these files from GitHub to your directory on your computer 

Once you have cloned all the files out of this [GitHub](http://github.com) repository there are a couple good things to know before you get going. 
* 'index.html' Is a good place to build your html framework and put your main information within the <body> tag
* 'stylesheet.css' Can be used to put styling to your sweet html using CSS
* 'script.js' Can be used to functionality to your website like processing user information


###Doctype

The Document Type Declaration, or doctype, is a way to tell the browser what type of document it is looking at. It goes at the top of the document, and until other HTML tags, it does not need a closing bracket.

```html
<!doctype html>
```

###Html Element

The `<html>` element is the document root. It is the recommended place for specifying the page language. 

It has a start tag `<html>` and an end tag `</html>`. The html element includes the `lang` attribute with a value of `en`, which specifies that the document is in English.

```html
<html lang="en">
...
</html>
```

###Head Element

The `<head>` element is a container for metadata (*data about data*). HMetadata is not displayed. Metadata typically defines document title, styles, links, scripts, and other meta information. 


```html
<head>
...
</head>
```


###Meta Element

The `<meta>` element is used to specify page description, keywords, author, and other metadata. Metadata is used by browsers, search engines, and other web services.

The first line inside the head is the one that defines the character encoding for the document, which is nearly always utf-8. The character encoding declaration must be included somewhere within the first 512 characters of your document, before any content based blocks.

Meta data is optional. Here we've also included the description and author.


```html
<head>
<meta charset="utf-8">
...
<meta name="description" content="Empty HTML5 Template">
<meta name="author" content="Joseph Szczesniak">
...
</head>
```

###Title Element

The `<title>` element defines the title of the document and is required in all HTML/XHTML documents. It defines a title in the browser toolbar,
provides a title for the page when it is added to favorites, and displays a title for the page in search engine results.

```html
<title>Empty HTML5 Template</title>
```

###Contact Information
Vince Jones
vincethebutcher@gmail.com

####Be sure to commit your changes to your development branch frequently!
![image](http://www.fillmurray.com/415/300)