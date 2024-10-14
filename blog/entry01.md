# Entry 1
##### 10/14/24

## Name: Eliot Paster
## Course: SEP10
## Period: 7
## Concept: HTML and Markdown basics

### Context
In unit one we choose a topic for our freedom project. For my project I chose architecture as it is something I have found intrest in the past few years and someting I may consider for a career later in life. We also started reviewing  HTML and Markdown basics as they are skills we can use throughout the year and the project.
 
### Lesson Summary
Here are some important notes to remember:

HTML and Markdown Basics
* Text sizes
  * To change the text sizes in HTML you need to put <h_> tags before and after where _ is how big you want the text to be (1 being the largest text size and 5 being the smallest.)
  * To change the text sizes in Markdown you simply add hashtags before the line of text. (1 hashtag being the largest text size and 5 being the smallest.)
* Images
  * To insert images in HTML you download an image into your main branch then use <img src=">. Inside the quotes you put the downloaded image name/url.
  * To insert images in Markdown you use ! [alt text] (filename)
* Links
  * To insert links in HTML you use <a href=""></a>
  * To insert links in Markdown you use [display text] (linkurl)
* Paragraphs
  * To write text in paragraph in HTML you use <p> tags before and after the text you want to uses
  * To write text in paragraph form in Markdown you simply just write the text
* Italics and Bold
  * To change the text to italics or bold in HTML you have to change the style.css file
  * To change the text to italics or bold Markdown you simply put astriscks before an after words (1 astrick for italic, 2 for bold, and 3 for both)

 ### Challenge 1

The first challenge I stumbled across was in the website we use for learning html called freecodecamp.com. There was a section called "Link to Internal Sections of a Page with Anchor Elements" In this section you had to create an internal link in a webpage that could lead you down to a different spot. This acted similar to a table of contents in a book. I was following the instructions clearly but I still could not figure out what the issue was. Here is my initial code:
Below is an example of an internal anchor link and its target element:
```html
<a href="footer">Footer</a>
...
<h2 id"#footer">Footer</h2>
,,,
Below is an example of an correct internal anchor link and its target element:
```html
<a href="#contacts-header">Contacts</a>
...
<h2 id="contacts-header">Contacts</h2>
```
The mistake I made was where I placed the hashtag. The location of the hashtag is very important because where it is placed determines if I am naming a place that does not exist #footer or if I am creating a real place in the code #footer.

### Challenge 2
The second challenge I faced was while writing this blog entry. This blog entry is my first real experience using github as unit one also introduced websites I will be using through highschool. I learned many things about adding code pages, text pages, files, folders and more. I also learned how people can make templates I can used. What I did not learn was the point of the commit changes button in the top right of my code.
![commitchangesimage](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/commit-changes-github.png)
After tragically closing my laptop assuming github has autosave features I come back to github saturday night prepared to finish my first blog to realize none of my work has saved. Because of this I did reserch to find a solution and found a quote that stuck with me while writing the current blog.

[Next](entry02.md)

[Home](../README.md)
