**# Introduction (pp. 2-11)**

**# Chapter 1 : Structure (pp. 12-39)**
- HTML pages are text documents.
- HTML uses tags, which are characters that sit inside angled brackets.  They act like containers and tell you something about the information that lies between them.
- Tags are often referred to as elements.
- Tags usually come in pairs.  The opening tag denotes the start of a piece of content; the closing tag denotes the end.
- Opening tags can carry attributes, which tell us more about the content of that element.
- Attributes require a name and a value.
- To learn HTML you need to know what tags are available for you to use, what they do, and where they can go.

**# Chapter 2 : Text (pp. 40-61)**
- HTML elements are used to describe the structure of the page (e.g. headings, subheadings, paragraphs).
- They also provide semantic information (e.g. where emphasis should be placed, the definition of any acronyms used, when given text is a quotation).


<dl> **Syntax**
#### <dt> /<h1/>/<//h1/> ... /<h6/>/</h6/> </dt>
#### <dt> /<p/>/<//p/> </dt>
#### <dt> /<b/>/<//b/> or /<strong/>/<//strong/> and /<i/>/<//i/> or /<em/>/<//em/> bold & italics </dt>
#### <dt> /<sup/>/<//sup/> and /<sub>/<//sub/> superscript & subscript </dt>
#### <dt> /<br ///> and /<hr ///> line break and horizontal rule (empty element - doesn't need opening /& closing tag) </dt>
#### <dt> /<blockquote/>/<//blockquote/> longer quotes that take up an entire paragraph, usually indents the contents (although you shouldn't use this *just* to indent; instead, do it using CSS) </dt>
#### <dt> /<q/>/<//q/> shorter quotes </dt>

#### **Other Syntax Mentioned (pp.53-56)**
#### <abbr></abbr> use <abbr title=""> to specify the full term
#### <cite></cite> indicate where the citation is from
#### <dfn></dfn> definition - used to indicate the defining instance of a new term
#### <address></address> address, e.g.
#### > <address> <
#### >   <p><a href="mailto: joe@example.org" <
#### >     joe@example.org</a></p> <
#### >   <p> the physical address </p> <
#### > </address>

#### <ins></ins>, <del></del>, and <s></s> insert (underline), delete (strikethrough), and strikethrough (same)
</dl>

**# Chapter 3 : Lists (pp. 62-73)**
- There are three types of HTML lists: ordered, unordered, and definition.
- Ordered lists use numbers.
- Unordered lists use bullets.
- Definition lists are used to define terminology.
- Lists can be nested inside one another.

#### **Syntax**
#### <ol>, <ul>, and <li> ordered list, unordered list, and list item
#### <dl> definition list, inside you place <dt> and <dd> elements
#### <dt>, <dd> term being defined, the definition; note, /"sometimes you might see a list where there are two terms used for the same definition or two different definitions for the same term./"

**# Chapter 4 : Links (pp. 74-93)**
- Links are created using the <a> element.
- The <a> element uses the href attribute to indicate the page you are linking to.
- If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs.
- You can create links to open email programs with an email address in the "to" field.
- You can use the id attribute to target elements within a page that can be linked to.

#### **Linking within own site (relative URLs)**
#### > <a href="example.html">Example page</a> 'This doesn't need the domain name of the URL.

#### **Linking to a specific part of another page (id attribute)**
#### > Give your header an id attribute ...
#### > <h2 id="example">example header</h2>
#### > ...And at the top of the page create a link like this:
#### > <a href="#example">title of the header you're linking to</a>

**# Chapter 5 : Images (pp. 94-125)**
- The <img> element is used to add images to a web page.
- You must always specify an src attribute to indicate the source of an image and an alt attribute to describe the content of an image.
- You should save images at the size you will be using them on the web page and in the appropriate format.
- Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

**# Chapter 6 : Tables (pp. 126-143)**
- The <table> element is used to add tables to a web page.
- A table is drawn out row by row.  Each row is created with the <tr> element.
- Inside each row there are a number of cells represented by the <td> element (or <th> if it is a header).
- You can make cells of a table span more than one row or column using the rowspan and colspan attributes.
- For long tables you can split the table into a <thread>, <tbody>, and <tfoot>.

**# Chapter 7 : Forms (pp. 144-175)**
- Whenever you want to collect information from visitors you will need a form, which lives inside a <form> element.
- Information from a form is sent in name/value pairs.
- Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.
- HTML5 introduces new form elements which make it easier for visitors to fill in forms.

**# Chapter 8 : Extra Markup (pp. 176-199)**
- DOCTYPES tell browsers which version of HTML you are using.
- You can add comments to your code between the <!-- and --> markers.
- The id and class attributes allow you to identify particular elements.
- The <div> and <span> elements allow you to group block-level ad inline elements together.
- <iframes> cut windows into your web pages through which other pages can be displayed.
- The <meta> tag allows you to supply all kinds of information about your web page.
- Escape characters are used to include special characters in your pages such as <, >, and &#169.

**# Chapter 9 : Flash, Video & Audio (pp. 200-225)**
- Flash allows you to add animations, video and audio to the web.
- Flash is not supported on iPhone or iPad.
- HTML5 introduces new <video> and <audio> elements for adding video and audio to web pages, but these are only supported in the latest browsers.
- Browsers that support the HTML5 elements do not all support the same video and audio formats, so you need to supply your files in different formats to ensure that everyone can see/hear them.

**# Chapter 10: Introducing CSS (pp. 226-245)**
- CSS treats each HTML element as i it appears inside its own box and uses rules to indicate how that element should look.
- Rules are made up of selections (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like).
- Different types of selectors allow you to target your rules at different elements.
- Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties.  For example, the font-family property sets te choice of font, and the value arial specifies Arial as the preferred typeface.
- CSS rules usually appear in a separate document, although they may appear within an HTML page.

**# Chapter 11: Color (pp. 246-263)**
- Color not only brings your site to life, but also helps convey the mood and evokes reactions.
- There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
- Color pickers can help you find the color you want.
- It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
- CSS3 has introduced an extra value for RGB colors to indicate opacity.  It is known as RGBA.

**# Chapter 12: Text (pp. 264-299)**
- There are properties to control the choice of font, size, weight, style, and spacing.
- There is a limited choice of fonts that you can assume most people will have installed.
- If you want to use a wider range of typefaces there are several options, but you need to have the right license to use them.
- You can control the space between lines of text, individual letters, and words.  Text can also be aligned to the left, right, center, or justified.  It can also be indented.
- You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.

**# Chapter 13: Boxes (pp. 300-329)**
- CSS treats each HTML element as if it has its own box.
- You can use CSS to control the dimensions of a box.
- You can also control the borders, margins and padding for each box with CSS.
- It is possible to hide elements using the display and visibility properties.
- Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes.
- Legibility can be improved by controlling the width of boxes containing text and the leading.
- CSS has introduced the ability to create inline borders and rounded borders.

**# Chapter 14: Lists, Tables & Forms (pp. 330-357)**
- In addition to the CSS properties covered in other chapters which work with the contents of all elements, there are several others that are specifically used to control the appearance of lists, tables, and forms.
- List markers can be given different appearances using the list-style-type and list-style image properties.
- Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.
- Forms are easier to use if the form controls are vertically aligned using CSS.
- Forms benefit from styles that make them feel more interactive.

**# Chapter 15: Layout (pp. 358-405)**
- <div> elements are often used as containing elements to group together sections of a page.
- Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.
- The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)
- Pages can be fixed width or liquid (stretchy) layouts.
- Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).
- Grids help create professional and flexible designs.
- CSS Frameworks provide rules for common tasks.
- You can include multiple CSS files in one page.

**# Chapter 16: Images (pp. 406-427)**
- You can specify the dimensions of images using CSS.  This is very helpful when you use the same sized images on several pages of your site.
- Images can be aligned both horizontally and vertically using CSS.
- You can use a background image behind the box created by any element on a page.
- Background images can appear just once or be repeated across the background of the box.
- You can create image rollover effects by moving the background position of an image.
- To reduce the number of images your browser has to load, you can create image sprites.

**# Chapter 17: HTML5 Layout (pp. 428-451)**
- The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure.
- The new elements provide clearer code (compared with using multiple <div> elements).
- Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.
- To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed, which is available free from Google.

**# Chapter 18: Process & Design (pp. 452-475)**
- It's important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return.
- Site maps allow you to plan the structure of a site.
- Wireframes allow you to organize the information that will need to go on each page.
- Design is about communication.  Visual hierarchy helps visitors understand what you are trying to tell them.
- You can differentiate between pieces of information using size, color, and style.
- You can use grouping and similarity to help simplify the information you present.

**# Chapter 19: Practical Information (pp. 476-492)**
- Search engine optimization helps visitors find your sites when using search engines.
- Analytics tools such as Google Analytics allow you to see how many people visit your site, how they find it, and what they do when they get there.
- To put your site on the web, you will need to obtain a domain name and web hosting.
- FTP programs allow you to transfer files from your local computer to your web server.
- Many companies provide platforms for blogging, email newsletters, e-commerce and other popular website tools (to save you writing them from scratch).

**# Index (pp. 493-506)**

**Try out & download the code in this book www.htmlandcssbook.com/code**
