# Introductory HTML and JavaScript


### **Structure**:-

**Is very important in helping readers to understand the messages you are trying to convey and to navigate around the 
document.**

**Structure helps readers understand the stories. Think about the stories you read in a newspaper: for each story, there 
will be a headline, text and maybe an image this is how to structure be used to shape pages.**
 
*Like a newspaper HTML structure pages by using elements. As it uses attributes to tell us More about elements.*


### **Extra Markup**:-

Since the web was first created, there have been several different versions of HTML. (HTML4, XHTML1.0, HTML5)

- Doc Type:
Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser 
which version of HTML the page is using (although browsers usually display the page even if it is not included). We will 
therefore be including one in each example for the rest of the book.

- Comments ON HTML:
!-- --

If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between 
these characters.

- ID Attribute:
Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the 
page. Its value should start with a letter or an underscore (not a number or any other character). No two elements on the 
same page must have the same value for their id attributes (otherwise the value is no longer unique).

- Class Attribute:
Every HTML element can also carry a class attribute. Sometimes, rather than uniquely identifying one element within a 
document, you will want a way to identify several elements as being different from the other elements on the page. For 
example, you might have some paragraphs of text that contain information that is more important than others and want to 
distinguish these elements, or you might want to differentiate between links that point to other pages on your site and 
links that point to external sites.


### **HTML5 layout**:-

*HTML5 is introducing a new set of elements that help define the structure of a page.*

#### HTML5 Layout Elements

- While the traditional HTML uses 'div' element to group related elements on the page (such as the elements that form a 
header, an article, footer, or sidebar). HTML5 introduces a new set of elements that allow you to divide up the parts of 
a page. The names of these elements indicate the kind of content you will find in them.
 
  ![ph](html-vs-html5.png)
- Headers & Footers the 'header' element used to contain the site name and the main navigation. The element contains 
'footer' copyright information, along with links to the privacy policy.
- The element is used to 'nav' contain the major navigational blocks on the site such as the primary site navigation.
- The element acts as 'article' a container for any section of a page that could stand alone and potentially be 
syndicated. The elements can 'article' even be nested inside each other.
- The element  'aside' has two purposes, depending on whether it is inside an article element or not.
   1. When the element 'aside' is used inside an 'article' element, it should contain information that is related to the 
   article but not essential to its overall meaning.
   2. When the element is 'aside' used outside of an 'article' element, it acts as a container for content that is 
   related  to the entire page. For example, it might contain links to other sections of the site, a list of recent 
   posts, a search box, or recent tweets by the author.
- The element groups 'section' related content together, and typically each section would have its heading.

### **Process and Design**:-

- It's important to understand who your target audience is, why they would come to your site, what information they want 
to find and when they are likely to return.
- Site maps allow you to plan the structure of a site.
- Wireframes allow you to organize the information that will need to go on each page.
- Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.
- You can differentiate between pieces of information using size, color, and style.
- You can use grouping and similarity to help simplify the information you present.


### **JavaScript**:-

- A script is a series of instructions that the computer can follow to achieve a goal.
- Each time the script runs, it might only use a subset of all the instructions.
- Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task 
programmatically.
- To approach writing a script, break down your goal into a series of tasks and then work out each step needed to 
complete that task (a flowchart can help).

#### How computers fit in with the world around them?

- Computers create models of the world using data.
- The models use objects to represent physical things the object can have properties that tell us about the object; 
methods that perform tasks using the properties of that object; events that are triggered when the user interacts with 
the computer.
- Programmers can write code to say "When this event occurs, run that code".
- web browsers use HTML markup to create a model of the web page. Each element creates its node.
- To make web pages interactive, you write code that uses the browser's model of the web page.

#### HOW HTML, CSS, and JAVASCRIPT FIT TOGETHER:-

***HTML***

- The Body
- HyperText Markup Language (HTML)
- Content and basic structure
- Describes and defines
- Made up of tags
- Tells the browser what to display

***CSS***

- The Accessories
- Cascading Style Sheet (CSS)
- Gives style and structure to the content
- Link the CSS file to the HTML
- Tells the browser how to display

***JavaScript***

- The body’s ability to perform actions
- JavaScript is not Java
- Behaviour of the website
- Used for interactive functionality
- Allows for the user to interact with the browser
 
## Tips:-
-It is best to keep JavaScript code in its JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the. js extension.
-The HTML 'script' element is used in HTML pages to tell the browser to load the JavaScript file (rather like the 'link' element can be used to load a CSS file).
-If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created.



