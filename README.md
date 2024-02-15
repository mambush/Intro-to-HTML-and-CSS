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

## UNIT 4
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

     ## UNIT 5

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
       * You need to add on an ALT attribute in the HTML, which serve as replacement for image when it cannot be seen.For instance people who are visually impaired may use a Screen reader that reads the ALT test outload to them.
         ## NB:
         * Make the ALT text interesting.
         * No need to mention that it is a Photo, as it is obvious.
         * No need to write a lengthy description
         * Focus on what it depicts.
            WORKING WITH BLANK ALT TEXT.
           =Decorative images require the addition of an empty or null ALT attribute in the HTML code view that will tell the screen reader to skip over the image. An empty alt attribute is written as ALT=" " with a space between the double qoutes.A null alt text is written as alt="" with no space between the set of qoutes.

           The browser also needs to be informed about the size of the image in pixels. In this case, the image is 400 pixels and 300 pixels tall. If the image os opened in a program like Photoshop,those dimensions can be verified. Include that information in the image element using the width and height attribute. The units for these numbers do not to be specified just the numerical value are enough. It is universally understood that the dimensions are actual pixels.
           ## NB;
           =It does not matter, whether the height or the width is specified first. In HTML, the order of attributes within an element can be whatever you prefer.

           The importance of typing in the width and height attributes is to set the space required for the image is reserved when the page is loaded.
           * If the browser is provided with the exact dimension of each image, it knows right away how to display it. This gives the browser a slight head start in calculating the layout.
             ## Image Formats
             = Is a file for a digital image.There are many format that can be used, such as JPEG,PNG and GIF. The data stored in an image file format may be compressed or uncompressed.

             # GIF = Are great for compressing illustrations that have large areas of the same color, but it falls short when it comes to photographs.It only supports 256 colors and image can end looking pixelated, unless you want that retro vibes GIFs can have transparent areas but the edges between transports and solid parts can be jagged.
             # SVG = Are perfect for logos,icons and other types of illustrations unlike GIF, SVG is a vector file that contains instructions for drawing rather than individual pixels. This means it can be scaled to any size without losing quality and file size remains small.SVG is actually a programming language of Graphics, and there are dedicated courses on it if you wish  to learn more. SVG files can be exported from pograms like illustrator or sketch,and handled just like other file formats on the web.

          # JPG
         JPG are a popular choice for compressing Photographs. Most digital Camera save image in JPG format, but when placed on the web, it is important to resize and compress appropriately. Avoid using gigantic, half-compressed JPG on your website as they will slow the loading speed. JPG can be Compressed further by reducing color information, finding the right balance quality and file size. You can do this manually or rely on web services for assistance.
         # PNG
         Is a newer format that works well when you need transparency in a Photograph. It Sometimes outperforms both GIFs and JPG in compressing certain types of images. When manually compressing files, try different options to find the smallest file size. It is worth mentioning that new image formats will likely emerge in the future, offering even better compression
         capabilities. Keep an eye out for those when working with image files,consider the physical size,file format and compression  settings to ensure fast download speeds interestingly, the HTML used remains the same regardless of the file format you choose.

       # Responsive image
       *Images that are designed to adjust their size and resolution based on the size of the device or screen they are being viewed on.
       * HTML allows us to deliver different image files to screen of different sizes
       * To support these different screens, create multiple copies of an image with different resolutions and inform the browser about these options. Then, the device can choose which image to use based on factors like screen density, network connection, and user settings. Even if someone has a high-resolution screen, the browser might opt to download a lower-resolution image.
         # Responsive width
         To make an image responsive you need to give a new value to its width property. Then the height of the image will adjust itself automatically. The important thing to know is that you should always use relative units for the width property like percentage,rather than absolute ones like pixels.
         # FIGURE AND FIGCAPTION
         A caption can be associated with the <figure> element by inserting a <figcaption>inside it( as the first or the last child). The first <figcaption> element found in the figure is presented as the figure caption. The <figcaption> provides the accessible description for the parent<figure>
         The <figcaption> element is used to define some text as the caption of a figure. Example:
         code.<figure><img src="image.jpg"
         alt= "Description of the image">
         <figcaption>This the caption of the figure</figcaption> </figure>

           ## UNIT 6
         # WORKING WITH AUDIO
          <audio>: The Embed Audio
         The <audio> HTML element is used to embed sound content in documents. It may contain one or more audio sources, represented using the SRC attribute or the <source> element: The browser will choose the most suitable one.
         The <audio> tag is used to embed sound content in a document such as music or other audio streams.
         The<audio> tag contains one or more <source> tags with different audio source. The browser will choose the first source it supports.
         The text between the <audio> and </audio> tags will only be displayed in browser that do not support the <audio> element
         There are three supported audio formats in HTML:MP3,WAV and OGG.

         * The opening tag and closing tag on Audio is to specify multiple audio files,Similar to how the picture is used.

           <audio control SRC="audio.mp3"></audio>
           *If a new file format is used that is not supported in all browsers while providing feedback for older ones,to achieve this, remove the source attribute from the audio element and place it on a seperate source element.
           # WORKING WITH VIDEO
           The <video> tag contains one or more<source> tags with different video sources.
           * The browser will choose the first source it supports. The text between the <video> and </video> tags will only be displayed in browsers that do not support the<video> element.
             * The <video> element supports three video formats:MP4,WebM and Ogg.
               * However, not every web browser supports all three of these formats. To be sure that your video content display properly across browser you can specify multiple video sourcers with the<source>tag
                 <video width="320"height="240" controls>
                 <source src="movie.mp4"type="video/mp4">
                 <source src="movie.ogg"type="video/ogg">
                 Your browser does not support the video tag
                 </video>
                 The <video> tag is used to embed video content in a document, Such as a movie clip or other video streams.
                 The controls attribute adds video controls, like play, pause and volume.
                 Just like with image formats like PNG,JPEG,GIF or SVG there are different codecs that can be used to encode video files. Video file contains alot of data and if not compressed they become too large to be efficiently transimitted over the
                 internet. Internet videos,therefore use a mechanism to compress all data into a smaller package.
                 There have been various codecs developed over the years suchn as Real video,Sorenson, windowsMedia,Flash and H.263 from 2015 to 2020, H.264 was the dominat codec that most people used,however there is a catch:H.264 is not open source.
                 It is a patented codec owned by a consortium. They charge licensing fees for every device,operanting system,browser,camera or anything that wants to record,comprers or play H.264 FILES. And now they are Planning to charge even more for H.265
                   # WORKING WITH VIDEO ELEMENT
                 HTML <caption> tag defines a table cation.The <caption> tag must be inserted immediately after the <table> tag.TIP: By default,a table caption will be center-aligned above table.
                 * caption and subtitle, we use it for those people who are deaf or people who do not want display sound in Public platform.
                 * we use the track element and link it to a text file to add caption to the video. This element adds functionality to the video player, allowing those viewers to toggle captions on and off or switch between different subtitle options. On a web, a file format called"ibvtt", which stands for web video text tracks, will be useed.
                 * It is simple text file with vtt extension that follows a specific convention for providing information. Each line text is accompanied by a time code, that will when it should be displayed in the video.
                 HTML allwos us to specifyfor a video using the <track> element.
                 #Embedding via Media
                 * There is a wide range of content that can be embedded on a page,instance,a map from Google or Mapbox, acode demo from codePen or Glitch or even a slide deck from speaker Deck or Notist.It is common parctise to embed complex content from a service that handleds the techinical aspects.Instead of figuring out how to builed a mapping service a slide deck system a code demo platform, or an adaptive bitrate server, you can rely on someone else toolkit to handle all of it.Simply embed the results onto a website. So that what HTML knowledge do we need to facilitate this process.

                 #GETTING AN EMBED LINK FROM YOUTUBE
                 *Look for the video element,which could be an <iframe>,<video> or<embed> ta. Find the URL in the source code: Once you have located the video element, search for the src attribute within the element.The url of the embedded video should be specified in src attribute.
                 #WORKING WITH IFRAME ELEMENT
                 * An inline frame is used to embed another document within the current HTML document. Use CSS style to style the <iframe>
                 * It is good practise to always include a title attribute for the <iframe>. This is used by screen readers to read out what the content of the <iframe> is.
                 * If used a content management system(CMS) that was set up by another person for example;"Word press" or "Drupa" there is no need to copy and paste random embed code from other websites.
                 * The CMS have a specific way to allow URLs or Shorcodes from trusted sources, So to embed things like YouTube videos,its better ask someone who already knows how to use it.
                   # NB;
                   If you are building a website consider security aspects that are related to the iframe element.

                   ## UNIT 7
                   # HTML CONTENT IDENTIFICATION
                   =The lang global attribute helps define the laguage of an element: The langauge that non-editable element are written in or the language that the editable elements should be written in by the user.
                   * The Lang tag(lang="" attribute) is designed to signal screen readers pronunciation engines to switch to another language.
                   * Thge lang attribute is used to specify the language of a webpage.
                   * It is simple when the whole page is one language.
                   * You set the language on the main element that wraps everything else,which is the HTML element.
                   * You set it once like a template file that applies to the entire set.
                   * It is such important to specify the content direction, Since most language flow from left to right horizontally some flow from left to right.
                   * You need to use the "Dir" attribute to indicate the direction and can be applied to any element.

                     <HTML lang="en-us">
                     <HTML lang="en-gb"dir="ltr">
           













     
       


  
