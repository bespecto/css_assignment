# css_assignment# CSS assignment, due on 11/21 at noon  
  
For this assignment, you’re going to create a CSS file from scratch (using my instructions) to mimic the look of a BuzzFeed News article. You have all of the components that you need here — the only thing you need to do is write CSS statements.   
  
Download and submit instrux: Download this repository and edit 'main.css' with the instructions below. You should drag 'article.html' to a Chrome tab so you can see the changes you're making. When you're done, you should create a new repository in your Github account, call it CSS_YourLastName, and upload only 'main.css' and 'article.html'.  
  
## Instructions:    
1. Style the body element and to have a zero-pixel margin.  
2. Set the following properties on the class site_banner:  
	a. A solid black border along the top that is eight (8) pixels thick.  
	b. A solid black border along the bottom that is one (1) pixel thick.  
	c. Padding of 20 pixels on all sides.  
	d. Use text-align to put contents in the center.  
3. In the HTML file, find the div element that has the class site_banner. An image element is inside of it. Set that image’s width to 330 pixels.
4. There’s also a heading 3 element enclosed within the same div. In your CSS sheet, give it the following styles:
	a. Give it the “Basier” font. Also make sure to give it an appropriate back-up generic font style, like 'serif' or 'sans-serif'.  
	b. Make it bold (with CSS) and give it a size of 14 pixels.  
	c. Set the color to #de2f23 (this is the HTML color code for a nice BuzzFeed red-orange).  
	d. Space the letters at one (1) pixel (Note: this isn’t a property we’ve used in class, but the property name to use is letter-spacing).  
5.  The story’s written copy, photos, captions and header (with headline, byline, etc.) are all enclosed in a div that has the class article. Set the maximum width for that class to 900 pixels (using max-width), and also give it a 5 percent margin on the left and right sides.  
6. We’re moving on to the div that has a class of story_header now. Take a look at the HTML file to see which elements are enclosed inside. Have this class use the same font from step 4a, as well as a size of 20 pixels.  
7. Identify the HTML element that contains the story’s headline. Set its size to 46 pixels and make the bottom margin 0px.  
8. Look for the story’s byline and make it bold with CSS.  
9. For the div that has a class of story_copy, set it to use the “Pensum” font (and give it an appropriate back-up style like before) and a font size of 20 pixels.  
10. Aside from the Buzzfeed News logo at the top of the webpage, there are two images in this story. Write a CSS selector that would give these two images a width of 100 percent.  
11. These two images also have captions. Set these to be colored gray, with a size of 14 pixels and no margin along the top.  
12. Go and check out the div that has a class of footer towards the bottom of the HTML file. Write a selector that will have it use the “Basier” font; give it a top and bottom margin of 30 pixels.  
13. Inside the footer div, there are paragraphs with journalist names and article publication dates. Those should be colored gray and have a size of 14 pixels.  
14. In the CSS file, make all the links in the HTML file black.  
*Bonus*: Do some research and write a selector that changes link colors when a cursor hovers over them. The colors must be different on hover than what they are when you're not hovering on them.
