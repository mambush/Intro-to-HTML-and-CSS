# Intro-to-HTML-and-CSS
# Week 1  
## Unit 1

INTRODUCTION TO HTML
HTML: HYPERTEXT Markup language standard markup language for documents designed to be displayed in a web browser. It defines the content and the structure of web content.It is often assisted by technologies such as Cascading style sheets and scripting language such as JavaScript.
HTML is used to tell your web browser what each part of a website is.
So using HTML is to define heaaders,paragraphs,links,images and more.
In that case the browser will know to structure the web page you're looking at.

THE FUNCTION OF HTML
= HTML
=CSS
JAVA SCRIPT
* HTML, has a straight forward structure without any programming logic, loops or functions other as a declarative language. The code simply declares Instructions like " This is a paragraph" or "Make this a link" or " put a form field here!". It is all about using the right vocabulary and making decisions.
* CSS, short for Cascanding style sheets is like the stylist of a web page. It is responsible for how everything looks,the colors, fonts and size.It is also capable of adding cool animations and interaction to spice things up.
  = CSS computer language for laying out and structing web pages(HTML or XML). This a language contains coding elements and is composed of these "cascading style sheets" which are equally called CSS files.
  = CSS got some computer science stuff going on, which makes it both fragile and powerfull at the same time. When there is a hiccup in the css code, the browser is smart enough to skip that part.
  * Java script is a scripting langauge that enables you to create dynamically updating content, control multimedia, animate images and pretty much everything else.
  * Otherwords it is used for creating dynamic web page content. It creates elements for improving site visitors interaction with web pages such as dropdown menus,animated graphics and dynamic backgroup colors.
* JavaScript is also defined with the function keyword,followed by a name,followed by parentheses. Function names can contain letters,didgits,underscores and dollar signs(same rules as variable). The parentheses may include parameter names separated by commas;
* Function name(parameter 1,parameter2,parameter3) {
   // code to be executed.

 ## UNIT 2

HTML text formatting 
HTML syntax
* Langauge used to structure web pages,It uses tags, which are enclosed in less than and greater than. Symbols ,to mark different elements. Tags come in two types: opening and closing tags. For example,the opening tag for a paragraph is <p> and the closing tag is </p>
* HTML contains several elements for defining text with a special meaning
  for Example: The text is bold
  This text is italic
  This is subscript and superscript.
  HTML formatting Elements
  <b>- bold text
  <strong>- Important text
  <i> - Italic text
  <em> - Emphasized text
  <mark> - Marked text
  <small> - Smaller text
  <del> - Deleted text
  <ins> - Inserted text
  <sub> - Subscript text
  <sup> - Superscript text.

  Nested HTML Element
  * An entire document is basically a bunch of HTML element nested inside each other.
  * The browser pays attention to this nesting create a tree structure, like a family tree with parents,children and Siblings;It shows how everything is related and is called a called "Dom Tree"( Document Object Model), This tree is very important when dealing with CSS or javascript.
  * Practical Snippet of HTML has emphasized text, mostly pay attention to where we open and close our HTML tags and how we rest elements within each other. This helps convey meaning about the content and interfaces.
  * Sometimes the outer element will just other elements as in the example above.for example look how "li" elements inside the "ol" element are indented.
    <!DOCTYPE html>
    <html>
      <body>
        <h1> First Heading</h1>
        <h2> Second paragraph</h2>
        
      </body>
    </html>

  A paragraph is used to to start on a new line and browsers automatically add some white spaces.
  HTML Headline are what defines with <h1> to <h2>
  <h1> Defines the most important heading.
  <h6>Defines the least impportant heading.
  HTML lists 
  * If you want to write a list you use <li></li> for Order HTML you use <ol></ol>
  If you want to create a recipe:
  = you need to mark each step as a <li> element and then wrap the entire list in an<ol>

 ## UNIT 3

  HTML Attributes
  * All HTML elements can have attributes
  * Attribute provide additional information about elements
  * Atributes are always specified in the start tag
  * Atrributes usually come in name/value pairs like: name=" value"
Another popular attribute is the ID, It is similar to the class attribute but we can use unique names on a entire HTML page ID can be used for CSS targetting but are more specific
which can be sometimes causes issues. As a result CSS developers usually prefer using classes.
The href attribute <a>
=Defines a hyperlink,The href attributes specifies the URL of the page the link goes to:
for Example <a href="https://www.w3schools.com"Visit W3schools</a>
The src Attribute
The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed 
<img src="img_girl.jpg">
* ID Attribute- The ID attribute is a unique identifier which is used to specify the document.
  #NB- It is used by CSS and Javascript to perform for unique elements
  * Class Attribute - The class attribute is used to specify one or more class names for an HTML element.
    ID usually come in handy when we address specific elements in JavaScript or targeted links.
    ID ensures that there will be one element with that ID making it useful for interacting with JavaScript or Links.

    #ARIA Roles- provide semantic meaning to content, allowing screen readers and other tools to present and support interaction with an object in a way that is consistent with user expectations of that type of object.
    #ARIA Function - ARIA is set of attributes you can add to HTML elements that define ways to make web content and Application accessible to users with disabilities who use assistive technologies(AT)

    # A tree browser accessiblity tree- allows users to vertically navigate hierarchical business object, each presented as a node with a large image,three lines of metadata and an optinal link.
    # Metadata are HTML snippets used in web development to describe the content on a web page.
    Meta tags don't appear on the pages but instead exist within the websites source code, also known as the HTML code, located in the website head.

    * FORMATTING IN HTML, refers to the way text is displayed on a web page.
    * Since I know that HTML does not pay much attention in spaces,Tabs or line break. But there couple exceptions for example if you use elements like<pre>,<code> or ,<textarea> or you want to modify the white handling with CSS then extra space or indentation can matter.
    * working with comments in the HTML can be used to insert comments in the source code.
    * Comments are not displayed in the browsers, You can use comments to explain your code whcih can be useful when youn edit the code at a later date,especially when you have alot of code.

      *Working with the upper or lowercase, can define the text case for your style by using the text transforms property. In this way you can display the text either with initial capital letters, in all capital letters in all small letters or as it was typed.
      * HTML allows mixing uppercase and lowerscase letters in element names, However we recommend using lowercase element names because mixing uppercase and lowercase names look bad. Most developers use normally use lowercase names.
      * Working with short element, <code> HTML element displays its contents styled in a fashion intended to indicate that the text is a short fragment of computer code. By default, the content text is displayed using the user agents default monospace.
      * In code formatting you write symbols with space around them and they will appear as regular content,However if you start to writing something that resembles an HTML element it magically disappear.

        A commonly used HTML entity is the non- breaking:&nbsp: non- breaking space is a space that will not break into a new line.Two words separated by non- breaking space will stick together(not break into a new line).

##UNIT 4
 HTML NAVIGATION AND LINKS
 The <nav> tag defines a set of navigation links notice that not all links of a document should be inside a <nav> element.
 The <nav> element is intended only for major blocks of navigation links.
 HTML LINKS -are links that we encounter everytime or everywhre online
 ##NB -when creating a list we use the<a> element to define the link.
 *Use the href attribute to define the link address
 *use the target attribute to define where to open the linked document
 *Use the <img> element (inside <a>) to use an image as a link

 HTML LINKS - Syntax
 The HTML <a> tag defines a hyperlink.It has the following syntax
 <a href="url"> link text</a>
 The most important attribute of the <a> element is the href attribute ,which indicates the links destination.
 The links text is the part that will be visible to the reader
 clicking on the link text, will send the reader to specified URL address 
 for Example:
 <a href=" http://www.w3 school.com/"
 =visit w3schools.com!</a>
 * To make use of HTML file paths, the two option are either relative or absolute file path.With relative file paths,the fiels you inted to reference are located in the same folder of your website folder structure.
 * HTML FILE Paths
   A file path describe the location of a file in a web site's folder structure.
   File paths are used when linking to external files,web pages,images,style sheets and javascripts.
   * An absolute File paths is the full URL to a file:
     <img
     src="https://www.w3schools.com/images/picture.jpg" alt="Mountain">
     NAVIGATION HTML

     #UNIT 5

     HTML working with Graphic and Image

     * IMAGES
       = A web would not be a complete web without images.
       =when we add image to a webpage we use image element written a "img"
       EXAMPLE;
       <img src="image.jpg"alt="brown dog" width="400"height="300">

       #FOUR ATTRIBUTES THAT NEED TO BE INCLUDED FOR EVERY IMAGE
       1.We have the source attribute (SRC) which tells the browser which image file to load.
       2. The alt attribute (ALT) which provides a text description of the image
       3. Then we have the width and height attribute, which determine the size of the image. So every image should have all four of the attribute.

       Working with an image element.

       In order to put simple image on a webpage,we use the <img> element. This is a void element(meaning, it cannot have any child content and cannot have an end tag) that requires two attributes to be useful: SRC and ALT. The SRC attribute contains a URL pointing to the image you want to embed in the page.
       * You need to add on an ALT attribute in the HTML, which serve as replacement for image when it cannot be seen.













     
       


  
