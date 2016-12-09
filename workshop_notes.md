# Mini Tuts+ Town Workshop

## Getting Started: What is Web Design Exactly?
* Well, it’s tricky. It can mean a lot of different things and it’s not uncommon for 2 web designers to have few overlapping skillsets. 
* For example, while some designers are completely focused on a user’s experience of a site, others are tasked with actually building these designs with code, which is what we are going to focus on today.  

## How The Web Works
* Now, since we are creating something on the web it’s helpful to have a general idea of what it is and how it works. 
* When two computers are connected to the Internet (which is shown as a yellow line in the picture below) they can talk to each other.
* A server (the blue box) is a special computer that contains web page files. Your computer at home or school is not a server, because it is not connected directly to the Internet. We connect to the Internet through an Internet Service Provider (ISP).
* A site’s content (all that stuff a website talks about) is organized within a special set of rules that computers understand; sort of like speaking in a secret, coded language, except we will soon be in on this little secret as well!
* In this picture the browser is asking to view www.tutsplus.com from the server where the site’s files live. The server is sending the files back and the browser is translating them to display a page on the screen. And this happens very quickly!
* Because of all this, a site you write locally (on your computer) can’t be seen by other people on a different computer, until you move the files to a server.
* Luckily we will be using an online tool that will allow us to skip over this folder structure part today (but basically a website is just a bunch of connected files that must live in the same folder). 

## What is HTML and CSS?
* Hypertext markup language is a way of structuring a document in a way that the browser can understand. For example, we will learn that we can’t just type up a paragraph in our text editors and expect the browser to understand what it is; we have to put it in a paragraph element!
* Cascading style sheets is a separate document that allows us to style our HTML document by adding coloring and moving things around in a more appealing and usable way. 

## Linking These Two Files
* In order for our CSS to impact our HTML they have to be properly linked together, which is taken care of for us with CodePen. 

## HTML Intro: Syntax & Structure Basics
* This is what HTML looks like! 
* HTML is written with elements that have important meaning. All of our content has to live within the right elements in order to be understood by the browser, so creating a solid structure or foundation in our document is an excellent first step. 
* Most elements require both an opening and closing tag, with the content written within these tags. 

## Full Preview
* So we don’t have a background-color and everything is left aligned by default, but our text and images are there! 
* Practice time!
* (practice adding a heading, paragraphs, and images without talking about nesting)

## CSS Intro: Properties & Values
* Just as with HTML, CSS needs to be written in the correct way in order to work. 
* So we can call on a class name (refer as additional reading) or full element name here. 
	* The styling instructions are contained within curly brackets, `{ }`. 
	* What we will be styling (`background-color`) is immediately followed by a colon `:` 
	* Then we add the value (which is `blue` in this case). 
	* Each style must end with a semicolon `;` 
* Practice time!

## CSS: Colors 
* So we have a green background but it’s not very pretty. There are some colors you can use by writing out their names in CSS, but to achieve such a unique color as the light yellow we designed for Tuts+ Town we need to include its hex value. 
* All colors have a hex number to match. So while browsers do not understand many colors when they are written out, they do understand hex numbers very well. The hex number for our light yellow color is `#FAF8DA` 
* Practice Time! 

## CSS: Sizing 
* We also have the power to change the sizing of text and images with CSS. There are lots of units of measurement that can be recognized by the browser, but we are going to work with pixels, which is basically dots filled with color on the screen. 
* If we take a look at our header again we may find that we need to make changes to the size and color of our primary heading and image. 
* The first thing we will want to do here is add class to these elements in our HTML
* Now in CSS was can target this class name and declare sizing

## Where To Go From Here!
* Review what we learned today
	* We built our very first website by learning how to properly markup and HTML document and add our content in a way that the browser can understand.
	* After understanding the role CSS plays here we were able to get a glimpse into the styling possibilities for our site.  
* Review what rest of series will cover 
	* The rest of this series will cover the remaining CSS styling and layout required to complete the site, and also touches on things like typography, color theory, and some general design concepts we didn’t have time to go over today. 
* Provide link to [the Tuts+ Town full curriculum](http://webdesign.tutsplus.com/series/web-design-for-kids--cms-823)
* Provide link to reference site. 
