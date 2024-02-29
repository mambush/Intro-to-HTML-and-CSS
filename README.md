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
                   * The lang attribute is used to specify the language of a webpage.
                   * It is simple when the whole page is one language.
                   * You set the language on the main element that wraps everything else,which is the HTML element.
                   * You set it once like a template file that applies to the entire set.
                   * It is such important to specify the content direction, Since most language flow from left to right horizontally some flow from left to right.
                   * You need to use the "Dir" attribute to indicate the direction and can be applied to any element.

                     <HTML lang="en-us">
                     <HTML lang="en-gb"dir="ltr">
                     <HTML lang="ar"dir="rtl">
                     <meta charset="UTF-8">

                     * If all your content follow the same direction, define it once on the outer HTML element.
                     * A <meta> viewport element gives the browser instructions on how to control the pages's dimensions and scalling. The width=device-width part sets the width of the page to follow the screen-width of the device(which will vary depending on the device)
                     * In general metadata attribute provides a list one or more qualification value,separating those values with whitespace.
                     * An audience attribute of administrator programmer qualifies the content as applying to administrators and programmers

                       ## HTML Genetic Elements,Div and Span
                       <div>                                 <span>
                       Block-level element                   in line element
                       <div>
                       * Are used to create sections,sidebars and everything in between.
                       * Div is a block-level element, while span is an inline element
                       * They essentialy do nothing until CSS or JavaScript is applied in them
                       * Div is better referred for a block of content having different nested element,<p> which is used for paragraph and Span is nothing but an empty element.
                       DIV
                       <div> tag defines a division  or a section in a HTML document
                       * The <div> is used a container for HTML elements, which is then styled with CSS or Manipulated with javascript.
                         
                        ## UNIT 8
                       * HTML Integration allow for user authentication, data validation and seamless presentation of dynamic content on web pages.The communication between HTML, server-side scripts and database enables the creation of interactive data-driven web applications.
                       * To integrate a HTML Code you use;
                       <code> tag.
                        # Home page
                       * HTML page and all the elements attributes roles and tools used to mark up content on website or webapps ahve been covered. HTML plays a major role in explaining what these things are, but it is not just limited to that. HTML files are a vital part of the web.
                         # Structure of the whole HTML File
                         <!DOCTYPE html>
                         <html lang="en">
                         <head>
                           <meta charset="UTF-8">
                           <title>wisdom Pet Medicine</title>
                         </head>
                         <body>
                           
                         </body>
                         </html>

                         # Structure of the whole HTML File
                         * The file should begin with a "Doc".
                         * At the beginning specify a few things about the web page
                         * Declare the language being used and the content flow direction.
                         * Inside the HTML element there are two main parts where everything goes: The head and the body
                         * create them using the head and the body elements.
                         * The head contains all the metadata that the browser needs to know but will not display on the page.
                         * The body is for all the content and is composed of various element already discussed in this course.
                         * The body is where most of the action happens
                         * The doctype declaration,HTML head and body elements are the essential building block of every web page.

                           ## Document head

                           *Inside the head of a webpage, you put important information that the browser needs to know about the website.
 * We use the meta element, to ensure that meta elements are only placed inside the head as they provide metadata about the page.
 * To define the character set, use the character setb attributes and set it to"UTF-8"
 * The title element is not something that appears as visible content.

      <!DOCTYPE html>
      <html lang="en-us" dir="ltr">
      <head>
        <meta charset="UTF-8">
        <title>Our website</title>
      </head>
      <body>
        <h1> This is headline</h1>
        <p> Text in a paragraph</p>
        <p> Usually there's alot in here</p>
      </body>
      </html>

      # HTML file head section
   * Is what appears on the browser tab or bookmark when it is saved
   * It is also the name that appears under top sites when a new browser is opened.
   * Whenever the browser refers to this page, it uses the title defined in the title element.

     # META tag
     * use to inform the browser that the layout has been adjust to fit small screens
     *  Making it responsive website.
     *  without the meta tag the browser assumes the pages follows an older layout technique designed for desktop
     *  useful to include a description of the site
     *  Meta tag is used to assign a name to the webpage when saved to the home screen
     *  To specify a tile image and background color
     *  when a link is shared on a platform like SLACK, it turns into an attractive card, this made possible by meta tags.
                       
# LINK ELEMENT
The <link> tag defines the relationship between the current document and an external resource.The <link> tag is most often used to link to external style sheets or to add a favicon to your website.
The <a> HTML element( or anchor element) with its href attribute creates a hyperlink to web pages,files,email addresses,location in the same page,or anything else a URL can address.
Content within each <a> should  indicate the link's destination.If the href attribute is present,pressing the enter key while focussed on the <a> element will activate it.
The link element is a crucial component used extensively within head section.It serves to connect various assets that should load, such CSS files, fonts and favicons. To inform the browser about the type of asset, utilize the rel attribute as "stylesheet". A link to a favicon would also resemble this,furthemore you can also include a link to preload a font file. It is important to consider that the browser will load the files in the order they are listed.

# The script element
<script src="my-javascript-file.js"js></script>

The script tag is commonly used element in HTML document head. It instructs the browser to load a JavaScript file.
The HTML head serves as a central hub for connecting and setting up various componets,ensuring that all assets are loaded and sharing page information with other sites and platforms. In a way it is like headquarters for getting the page off a to good start.
# Content structuring
# MAIN
* Is used once per webpage, tells the browser where the content is located.
  # Header
  * Is used for site headers,article readers and headers within the content.
  * A header is found on top of most webpages and may include a logo site name and navigation.
    # footer
    Signifies that there are extra things to convey regardless of its position on the page.
    # Article
    The article element wraps around any type of content unit whether it is long written article,a short snippet, a teaser card, a tweet or even an app element. It represent s standalone unit of content.
    # Section
    * Is used to mark section of content
    * useful for diving different topic zones on a website,each section typically start its own headline.
      # aside
      * The aside element is for content that is off to the side,like a side bar information or additional details that company an article but not part of the main flow.
      * The main element is used once per page to wrap the main content, while the header,footer,article, section and aside elements are the five section element in HTML. They are combined and nested to structure the content of a webpage.
 ## UNIT 9
 an HTML form is used to collect user input. The user is most often sent to a server for processing.
 The HTML <form> element is used to create an HTML form for user input:
 <form>
   form elements
 </form>
 The <form> element isa container for different types of input elements, such as text fields, checkboxes,radio,buttons,submit buttons.
 <form>
   <label for="fname">First name:</label><br>
   <input type="text" id="fname" name="fname"><br>
   <label for="Iname">Last name:</label><br>
   <input type="text" id="name" name="Iname">
 </form>

 <input element can be displayed in many ways,depending on the type attribute.

 <form>

   form element
   
 </form>
 * The form element is a container for different types of input element such as text field,checkboxes,radio buttons,submit buttons.

* <input> is the most used form element.
  The method attribute
  The "method" attribute specifies the HTTP method to be used when submitting the form data.
  * The form-data can be sent as URL.
  * variable(with method="get") or as HTTP post transaction(with method="post")
  * The default HTTP method when submitting form data is GET
    EXAMPLE;
    <form action ="location_page.php"method="get">
    * Forms are used for various task like logging into website,making purchases,conducting searches and adding content.
    * You create form using the<form>,<input> and <button> elements and understanding various input types.
    * You can design interactive and user-friendly forms to collect data from your wesite visitors
    * Interactive form is a form that has a username,password into login field or press button to open a menu, or click a checkbox on a setting page, You are dealing with interactive element such as button and input.
    ## Form Function

    * An HTML form is used to collect user input. The user input is most often sent to a server for processing.
    * <form action="success.html"method="get"
    <label for="name">Id="name"
    type="text">
    <label for="email">Email</label>

    ## UNIT 10

    A table is a structured set of data made up of rows and columns(tabular data). A table allows you to quickly and easily look up values that indicatesome kind of connection between different types of data for example a person and their age, or a day of the week, or the timetable for a local swimming pool.
    # How does table work
    The point of a table is that it is rigid.
    * Information is easily interpreted by making visual associations betweeen row and column headers.
    * HTML tables are handled well by accessiblity tools such as screen readers, so succeful HTML table should enhance the experience of sighted and visually impaired users alike.

      Table styling,You need to provide some styling information with CSS, as well as good solid structure with HTML.
    *The layout tables reduce accessibility for visual impaired users;
screen readers used by blind people interpret the tags tha exist in an HTML page and read out the contents to the user.Because tables are not the right tool for layout,and the mark up is complex tha wit CSS layout techniques, the screen readers output will be confusing to their users.
* The table layout generally involve more complex markup structure than proper layout techniques.

  * An HTML table is created with an opening<table> and a closing</table>
  Inside these tags data is organized into rows and columns by using opening and closing table row <tr> tags and opening and closing table data <td> tags. Table row <tr> tags are used to create a row of data.
 Example;
<table>
  <tr>
    <th> Company</th>
    <th>Contact</th>
    <th> Country</th>
  </tr>
  <tr>
    <td> Alfred Futterkiste</td>
    <td>Maria anders</td>
    <td> Germany</td>
  </tr>
  <tr>
    <td> Centro</td>
    <td> Francisco</td>
    <td> Mexico</td>
  </tr>
</table>

## INTRODUCTION TO CSS
# IMAGES AND COLORS
## UNIT 1 IN CSS


 * CSS stands for cascanding Stylesheet.
* Is a file that holds all the style for your webpage.
* CSS adds visual appeal to your webpage
* CSS describe how HTML elements are to be  displayed on Screen,paper or in other media.
* CSS saves a lot of work. It can control the layout of multiple web pages all at once
* External stylesheets are stored in CSS file.

  # We use CSS:
  * We use CSS to define styles for your webpages,including the design,layout and variations in display for different devices and screen sizes.

     = In CSS we use selectors to target HTML elements and define how should they look.
    # We have three types of CSS
    * Inline
    * Internal
    * External
   # INLINE
  *Is where you write your css on your HTML file
  <p style="color;"> This is paragraph</p>
  # INTERNAL
  * Is a dedicated session in your HTML file for your styles
  <head>
    <style type=text/css>
      body(background-color:blue: }
           p { color:yellow:}
      </style>
  </head>
  # EXTERNAL CSS
  * Is a form of CSS which is used to add styling to multiple HTML pages at a time. External CSS helps to design the layout of many HTML webpages simultaneously. The External css is always saved with the CSS extension, and through this file, we can change the complete style of our HTML webpages.
  * External is more like a separated CSS file that can be accessed by creating a link within the head section of webpages.
  <head>
    <link rel="stylesheet" type="text/css" href="style.css"
  </head>
  ## CSS syntax
  A CSS rule consists of a selector and a declaration block

for example:
<h1> is a selector
The selector points to the HTML element you want to style.
The declaration block contains one or more declarations separated by semicolons.
* Each declaration includes a css property name and a value separated by a colon.
* Multiple CSS declaration are separated with semicolons, and declaration blocks are surrounded by curly braces.
Example:
p {
color: red;
text-align: center;
}
P is a selector in CSS(It points to the HTML) element you want to style:</p>
* Color is a property,red is the property value
*Text-align is a property and center is the property value.
## Example;
Selectors       Properties      values
= h1            color            Red
= p             Margin           25%

 * All of this together create the block of your webpage.
## UNIT 2 IN CSS
A CSS selector the HTML element you want to style.
CSS selector are to "find"(or select) the HTML element you want to style.
* we can divide CSS selector into five categories:
  = ID selector
  * The ID selector uses the Id attribute of an HTML element to select a specific element
  * The Id of an element is unique within a page, so the Id selector is useed to select one unique element
  * To select an element with specific id,write a hash# character,followed by Id of the element.

#para1 {
   text-align: center;
    color:  red;
    }
    </style>
    </head>
    <body>
     <p id="para1">Hello word!</p>

    CSS Class Selector
    * The class selector selects HTML element with a specific class attribute.
    * To select elements with a specific class,write a period(.) character, followed by the class.
    .Center {
      text-align: center;
      color: red;
      }
      HTML elements can also refer to more than one class

      EXAMPLE:
       <p class="center large"> This paragraph refers to classes</p>

       Universal Selector

       The universal selector (*) selects all HTML elements on the page.
       The CSS rule below will affect every HTML element on the page.
       *{
        text-align: center;
        color: blue;
        }
         Grouping selector

      The grouping selector selects all the HTML element with the same style definitions.

      h1,h2,p {
          text-align: center;
          color:  red;
          }

          
        ## UNIT 3
        

   = STYLING IMAGES
    Size: You can set the width and the height of an image using the"width" and "height" properties.
   img {
      width: 200px;
      height: 150px;
   }
    Alignment: You can control the alignment an image using the "float" property
    img {
       float: left;
   }
    Borders. You can add borders around iamges using the"border" property.
   Background color; you can set the background color of an element using the "background-color" property
    body {
     background-color: # f0f0f0; /* Hexadecimal color*/
   * To style images using CSS we use: border-radius
   * Indentify a color scheme,there goal is to choose a color scheme specific color for your website
   * Canva approach is a friendly graphic design.
   * CSS can be used to change the color of images. This can be done by using the color property. The color property can be used to specify the color of text,backgrounds and images.The value of the color property can be a hexadecimal color code, a named color or an RGB value
   * RGBA allow you to control opacity

       div {
          background-color: rgba(255,0,0,0.5);/* Red with 50% opacity*/
     *  Hexidecimal values, are the most common way to specify colors in CSS.
     *  Hex values are actually just a different way to represent RGB values. Instead of using three numbers between 0 and 255,you use six hexadecimal numbers.Hex numbers can be 0-9 and A-F.
     *  CSS color can be specified using a hexadecimal value in the form:
    
       #rrggbb

      where rr(red),gg(green) and bb(blue) are hexadecimal values 00 and ff( same as decimal 0 -255)
     for example,#ff0000 is displayed as red, because red is set to its highest value(ff) and the others are set to the lowest value(00).
     To display white,set all values to ff, like this #ffffff
     (#ff) Red
     (63) Green
     (47) Blue

     ## UNIT 4

     = Serif
     = Sans serif
     * Serif fonts have small lines at the ends of letter called "Serif"
     * Serif help connect the letters, making the text easier to read

       * Sans serit fonts do not have more modern appearance wit computer type setting, Sans serit fonts are mainly used for extend text because they look clean and are easy to read.
       * Serif-font have a small stroke at the edges of each letter.
       * They create a sense of formality and elegance.
       * Sans-serif fonts have clean line(no small strokes attached)They create a modern and minimalistic look.
       * Monospace-fonts here all the letters have the same fixed width. They create a mechanical look.
       * Cursive-fonts imitate human handwriting.
       * Fantasy-fonts are decorative/playful fonts.
         # Appyling Type formatting with CSS
         The <span> tag is also useful for marking up content to be styled with CSS.
         * It is in conjuction with the class and ID attributes, the <span> tag helps you assign class attributes to inline sections od text.
         * Font styles: Properties that affect a text's font,e.g,which fonts gets applied,its size and whether its bold italic
         * Text layout styles: Properties that affect the spacing and other layout features of the text,allowing manipulation of,for example,the space between lines and letters and how text is aligned with the content box.

# The purpose of applying type of formatting
* The goal is to make things look decent and readable, but perfections on every device is not neccessary.
* Set Arial, Helvetica, Sans-serif as the fonts for the entire page.
* For headings use a Serif font like Georgia and Times New Roman
  # Understanding the size
  Absolute size, such as points or pixels,remain the same regardless of the screen size
  * Relative units like percentange or R-E-M(pronounced "rem") can adjust based on the page size. When I zoom in, the font sizes using relative units scale proportionally with the rest of the page. Most developers use relative units for better flexibility.
  * The preffered font size unit by developers is usually"rem".
  * 1 rem is equivalent to 16 pixels
  * If the font size is specified as 1.5 rem, you can multiply it by 16 to get the size in pixels, which would be approximately 24 pixels.
    # Understanding the box model in CSS
    * CSS Box model is a container that contains multiple properties including borders,margin,Padding and the content itself. It is used to create the design and layout.

      In the box model we have:
      * The content
      * The border
      * Padding
      * Margin

The content; is the text inside the box,it is where text and images appear.

=The border ; is the surrounding the content, the border goes around the padding and Content, The border is like a line surrounding the content. We can choose to display all four sides of the border or just a few and there are various styles available for the border.
= Margin; Represent the space between element on the page. Margin clears an area outside the border, if you want to seperate intersecting elements you add some margin which will do the trick.
          
     
     
  
                       
           













     
       


  
