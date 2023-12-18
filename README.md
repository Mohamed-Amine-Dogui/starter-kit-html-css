
# Introduction

Welcome to the go-to resource for kickstarting your front-end web development journey with HTML5 and CSS3. By delving into HTML and CSS, you'll gain the skills to breathe life into your web projects, creating interfaces that captivate and engage users.

## Table of Contents

- [1. Master HTML5 Basics](#1-master-html5-basics)
  - [1.1 Create Your First Web Page in HTML](#11-create-your-first-web-page-in-html)
    - [1.1.1 Mastering HTML Tags](#111-mastering-html-tags)
    - [1.1.2 Customize Tags with Attributes](#112-customize-tags-with-attributes)
    - [1.1.3 Use the Basic Structure of an HTML Page](#113-use-the-basic-structure-of-an-html-page)
    - [1.1.4 Comment Your HTML Code](#114-comment-your-html-code)
  - [1.2 Organize Your Text](#12-organize-your-text)
    - [1.2.1 Create Paragraphs with `<p>` Tags](#121-create-paragraphs-with-p-tags)
    - [1.2.2 Line Break with `<br>` Orphan Tag](#122-line-break-with-br-orphan-tag)
    - [1.2.3 Create Headings with `<h1>`, `<h2>`, `<h3>`, ...](#123-create-headings-with-h1-h2-h3-)
    - [1.2.4 Create Lists with `<li>` and `<ul>` or `<ol>`](#124-create-lists-with-li-and-ul-or-ol)
      - [1.2.4.1 Step 1: Enclose List Items with `<li> </li>`](#1241-step-1-enclose-list-items-with-li-li)
      - [1.2.4.2 Step 2: Insert the List into `<ul> </ul>` or `<ol> </ol>`](#1242-step-2-insert-the-list-into-ul-ul-or-ol-ol)
    - [1.2.5 Emphasize Important Text](#125-emphasize-important-text)
  - [1.3 Create a Hypertext Link in HTML](#13-create-a-hypertext-link-in-html)
    - [1.3.1 Create a Hypertext Link with the `<a>` Tag and the `href` Attribute](#131-create-a-hypertext-link-with-the-a-tag-and-the-href-attribute)
      - [1.3.1.1 Create a Hypertext Link from One Page to Another on Your Site](#1311-create-a-hypertext-link-from-one-page-to-another-on-your-site)
      - [1.3.1.2 Create a Hypertext Link to the URL of a Page Available on the Internet](#1312-create-a-hypertext-link-to-the-url-of-a-page-available-on-the-internet)
    - [1.3.2 Create an Anchor with the `id` and `href` Attributes](#132-create-an-anchor-with-the-id-and-href-attributes)
      - [1.3.2.1 The Anchor is Further Down on the Same Page](#1321-the-anchor-is-further-down-on-the-same-page)
      - [1.3.2.2 The Anchor is Located in Another Page](#1322-the-anchor-is-located-in-another-page)
    - [1.3.3 Special Configuration of Links](#133-special-configuration-of-links)
  - [1.4 Insert Images](#14-insert-images)
    - [1.4.1 Insert an Image with the Orphan Tag `<img>`](#141-insert-an-image-with-the-orphan-tag-img)
    - [1.4.2 Choose the Right Image Format](#142-choose-the-right-image-format)
    - [1.4.3 Add a Tooltip with the `title` Attribute](#143-add-a-tooltip-with-the-title-attribute)
    - [1.4.4 Create a Clickable Thumbnail](#144-create-a-clickable-thumbnail)
- [2. Design Your Web Pages with CSS3](#2-design-your-web-pages-with-css3)
  - [2.1 Apply a CSS Property to an HTML Page](#21-apply-a-css-property-to-an-html-page)
    - [2.1.1 Apply a Style to an Isolated Element with the `class` Attribute](#211-apply-a-style-to-an-isolated-element-with-the-class-attribute)
    - [2.1.2 Apply a CSS Property to a Unique Element with the `id` Attribute](#212-apply-a-css-property-to-a-unique-element-with-the-id-attribute)
    - [2.1.3 Utilize Universal Tags `<span>` or `<div>`](#213-utilize-universal-tags-span-or-div)
    - [2.1.4 Insert an Image in the Background at the Title Level](#214-insert-an-image-in-the-background-at-the-title-level)
  - [2.2 Change Text Appearance](#22-change-text-appearance)
    - [2.2.1 Change the Size and Style of Text](#221-change-the-size-and-style-of-text)
    - [2.2.2 Italicize Text](#222-italicize-text)
    - [2.2.3 Make Text Bold with the CSS font-weight Property](#223-make-text-bold-with-the-css-font-weight-property)
    - [2.2.4 Underline Text with the CSS text-decoration Property](#224-underline-text-with-the-css-text-decoration-property)
    - [2.2.5 Align Text with the CSS text-align Property](#225-align-text-with-the-css-text-align-property)
    - [2.2.6 Change the Font Type](#226-change-the-font-type)
  - [2.3 Add Color and Background](#23-add-color-and-background)
    - [2.3.1 Change Text Color with `color`](#231-change-text-color-with-color)
    - [2.3.2 Apply Background Color with `background-color`](#232-apply-background-color-with-background-color)
    - [2.3.3 Add a Background Image with `background-image`](#233-add-a-background-image-with-background-image)
      - [2.3.3.1 Combine CSS Properties with the 'background' Super-Property](#2331-combine-css-properties-with-the-background-super-property)
    - [2.3.4 Create Gradients with `linear-gradient`](#234-create-gradients-with-linear-gradient)
  - [2.4 Create Borders and Shadows](#24-create-borders-and-shadows)
  - [2.5 Create Dynamic Appearances](#25-create-dynamic-appearances)
----

## Why learn two languages HTML5 and CSS3 separately?

- Why not create a single language that combines HTML and CSS? Why isn't HTML enough?

  - In HTML, you'll use tags to describe your content - you'll write them between angle brackets `< >`.
  - In CSS, you'll use properties to apply style to HTML elements - you'll write them within curly braces `{ }`.

- But how do you apply CSS styles to HTML elements if they are two separate languages?
  The code editor in which you write code allows you to write in different languages, including HTML and CSS.

What we'll do is simply code:
1. A content file in HTML - which will have the extension `.html`;
2. And another style file in CSS - which will have the extension `.css`.

These two files will be saved on your computer. To make them communicate, all you need to do is add a single line of code in the HTML file!
Thanks to this line of code, whenever you click on your HTML file to open it and view your website in the browser, it will automatically call the CSS file.
This will allow you to admire the styling you have applied and modify it at your leisure without affecting the content.

### Summary

- HTML forms the structure of a web page.
- CSS adds style to the structure.
- Both languages complement each other with distinct roles for each.
- The browser is software that reads the languages of the web: HTML and CSS.
- All browsers include development tools, including the inspection tool that provides access to the HTML and CSS of a page.

# 1. Master HTML5 basics
## 1.1 Create your first web page in HTML
### 1.1.1 Mastering HTML tags

HTML, the language of the web, uses elements called tags. These tags are written between angle brackets `<` and `>`. They indicate the nature of the text they enclose, allowing the browser to understand what to display on the screen for website visitors.
![Tag](pics/tag.jpg)

Tags come in pairs, consisting of an opening tag and a closing tag:
- `<title> </title>`: "This is the title of the page,"
- `<img>`: "This is an image,"
- `<p> </p>`: "This is a text paragraph," and so on.

There are two types of tags:
1. **Paired Tags:** `<title>This is the title of my page</title>`
2. **Orphan Tags:** These are single tags, often used to insert an element at a specific location, such as an image. There's no need to delimit the start and end of the image; we just tell the computer, "Insert an image here." Hence, the term "orphan tag."

An orphan tag is written like this: `<img>`

### 1.1.2 Customize tags with attributes

Tags are sometimes accompanied by attributes to provide additional information or configure an element (e.g., `<img src="photo.jpg">`).
![Orphan Tag](pics/orphan_tag.jpg)

### 1.1.3 Use the basic structure of an HTML page

Create an `index.html` file and add the following code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>HabibiComeToTunisia</title>
</head>
<body>
Experience the perfect blend of comfort and adventure. Welcome to HabibiComeToTunisia.com, your exclusive gateway to unforgettable waterfront getaways in Bizerte, Tunisia.
</body>
</html>
```

- `<html lang="en">`: While not mandatory, specifying the language can prevent potential display issues, especially if you're coding a website in English.
- Tags open and close, nesting in a specific order, similar to Russian nesting dolls:
  ![HTML Structure](pics/html_structure.jpg)

- The first line `<!DOCTYPE html>` is an essential orphan tag, indicating that this is an HTML page.
- The paired `<html> </html>` tag encompasses the entire content of the web page. Inside, there are paired `<head> </head>` and `<body> </body>` tags.
- The `<head> </head>` tag contains two tags providing information to the browser: the encoding and the title of the page.
- The orphan tag `<meta charset="utf-8">` indicates the encoding used in the `.html` file, determining how special characters display (accents, Chinese and Japanese ideograms, etc.).
- The paired `<title> </title>` tag informs the browser of the web page's title, crucial for search results and browser tab display.
- The paired `<body> </body>` tag contains everything that will be displayed on the web page.

### 1.1.4 Comment your HTML code

In HTML, a comment is simply a memo. It has a specific format: `<!-- This is a comment -->`.
To comment lines (or even multiple lines) in Visual Studio Code:
1. Select the line(s) in question.
2. Use the keyboard shortcut with CTRL + k, then CTRL + c.

To comment  a single line in Intelij:
1. Select the line in question.
2. To comment out a single line, press Ctrl + /

To comment lines (or even multiple lines) in Intelij:
1. Select the line in question.
2. To comment out a single line, press Ctrl + Shift + /


## 1.2 Organize your text

### 1.2.1 Create paragraphs with `<p>` tags

The `<p>` tags are used to delimit paragraphs in HTML:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>HabibiComeToTunisia</title>
</head>
<body>
<p>
  Experience the perfect blend of comfort and adventure. Welcome to HabibiComeToTunisia.com, your exclusive gateway to unforgettable waterfront getaways in Bizerte, Tunisia.
</p>

<p>
  Indulge in the epitome of luxury with our exquisite range of villas, mini-villas, and apartments, offering an opulent selection from cozy studios to expansive 5-bedroom sanctuaries by the azure shores of Bizerte.
</p>

</body>
</html>
```

### 1.2.2 Line break with `<br>` orphan tag

To create a line break, use the `<br>` orphan tag (for break); it does not require closing:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>HabibiComeToTunisia</title>
</head>
<body>
<p>
  Experience the perfect blend of comfort and adventure. Welcome to HabibiComeToTunisia.com, your exclusive gateway to unforgettable waterfront getaways in Bizerte, Tunisia.
</p>

<p>
  Indulge in the epitome of luxury with our exquisite range of villas, mini-villas, and apartments,<br>offering an opulent selection from cozy studios to expansive 5-bedroom sanctuaries by the azure shores of Bizerte.
</p>

</body>
</html>
```

### 1.2.3 Create Headings with `<h1>`, `<h2>`, `<h3>`, ...

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>HabibiComeToTunisia</title>
</head>
<body>
<h1>Habibi welcome to Tunisia!</h1>
<p>
  Experience the perfect blend of comfort and adventure. Welcome to HabibiComeToTunisia.com, your exclusive gateway to unforgettable waterfront getaways in Bizerte, Tunisia.
</p>

<h2>Convenient Booking</h2>
<p>
  Indulge in the epitome of luxury with our exquisite range of villas, mini-villas, and apartments,<br>offering an opulent selection from cozy studios to expansive 5-bedroom sanctuaries by the azure shores of Bizerte.
</p>

<h3>Our Offer</h3>
- Villas<br>
- Mini-villas<br>
- Apartments<br>

</body>
</html>
```

### 1.2.4 Create Lists with `<li>` and `<ul>` or `<ol>`

#### Step 1: Enclose list items with `<li> </li>`
To mark elements in a list, use `<li> </li>` (for "listed item"). Then, insert them all inside another tag to indicate whether it's an unordered list or an ordered list.

#### Step 2: Insert the list into `<ul> </ul>` or `<ol> </ol>`
- `<ul>` tags (for "unordered list") indicate the start of an unordered list, also known as a bulleted list.
- `<ol>` tags (for "ordered list") indicate the start of an ordered list, or a numbered list.

Here's an example:

- For unordered list
```html
<h3><mark>Our offer</mark></h3>
<ul>
  <li>Villas</li>
  <li>Mini-villas</li>
  <li>Apartments</li>
</ul>
```

- For ordered list
```html
<h4>your journey:</h4>
<ol>
  <li>A sumptuous breakfast</li>
  <li>Sun-soaked moments on pristine beaches</li>
  <li>Enchanting explorations of local treasures, and tranquil evenings immersed in the vibrant culture of this coastal haven.</li>
</ol>
```

### 1.2.5 Emphasize important text

In web page text, you may want to highlight specific words. The most commonly used tag for this is `<strong>`, but HTML offers various ways to emphasize

text on your page.

| Tags                 | Browser Rendering               |
|----------------------|---------------------------------|
| `<mark></mark>`      | Highlight the text.             |
| `<em></em>`          | Make the text italic.           |
| `<strong></strong>`  | Make the text bold.             |


## 1.3 Create a hypertext link in HTML

### 1.3.1 Create a hypertext link with the `<a>` Tag and the `href` attribute

1. Use the `<a>` tag (for "anchor") to indicate that you will redirect to another location.
2. Add the `href` attribute followed by `=` to announce the location to which you want to redirect.
3. Explicitly specify the location to which the link should redirect between " ".
4. Finally, write the text that should appear on the hyperlink.

#### 1.3.1.1 Create a hypertext Link from one page to another on your site

To achieve this, create a folder named `content` and a file named `page2.html`.
Add the following line at the end of the body of `index.html` to enable navigation to page2:

```html
<a href="content/page2.html">Next</a>
```

#### 1.3.1.2 Create a hypertext link to the url of a page available on the internet

To redirect the user to our Facebook page, add the following content to `page2.html`:

```html
<h4><em>Follow us on Facebook:</em></h4>
<a href="https://www.facebook.com/ResidenceDesPin" target="_blank">Facebook</a> <br>
```

### 1.3.2 Create an anchor with the `id` and `href` attributes

To create an anchor, add the `id` attribute to a tag that will serve as a marker. It can be any tag, such as a title tag.
Here's how you can do it: The first step is to add the `id` attribute followed by `=` to give a name to the anchor between " ":

```html
<h2 id="my_anchor">Title</h2>
```

The `id` attribute is used to give a "unique" name to a tag, to use it as a reference. Here, we use it to create a link to an anchor, but in CSS, it can be useful to locate a specific tag.

#### 1.3.2.1 The anchor is further down on the same page

To achieve this, create a file named `page3.html` in the `content` folder:

```html
<h1>My big page</h1>
<p>
  Discover our design tips for:<br>
  <a href="#kitchen">The kitchen</a><br>
  <a href="#garden">The garden</a><br>
  <a href="#living_room">The living room</a><br>
</p>
<h2 id="kitchen">The kitchen</h2>
<p>... (some text) ...</p>
<h2 id="garden">The garden</h2>
<p>... (some text) ...</p>
<h2 id="living_room">The living room</h2>
<p>... (some text) ...</p>

<a href="../index.html">Home</a>
```

#### 1.3.2.2 The anchor is located in another page

In this case, type the name of the target page before the hash `#` and finally the name of the anchor:

```html
<a href="content/page3.html#garden">The garden</a>
```

### 1.3.3 Special configuration of links

- To make the hyperlink open in a new tab:

```html
<p>Do you want to follow us on Facebook <a href="https://www.facebook.com/ResidenceDesPin" target="_blank">Facebook</a>?</p>
```

- Create a hyperlink that opens the email box with a new empty message.

```html
<a href="mailto:douggui.med.amine@gmail.com">Gmail</a>
```

- Create a hyperlink that allows downloading a file that you have previously placed in the same folder as your web page.
```html
<a href="FILE.EXTENSION" download>Download</a>
```
- finally: 
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>HabibiComeToTunisia</title>
</head>
<body>
<h1>Habibi welcome to Tunisia!</h1>
<p>
  Experience the perfect blend of comfort and adventure. Welcome to HabibiComeToTunisia.com, your exclusive gateway to unforgettable waterfront getaways in Bizerte, Tunisia.
</p>

<h2><em>convenient booking</em></h2>
<p>
  Indulge in the epitome of luxury with our exquisite range of villas, mini-villas, and apartments,<br>offering an opulent selection from cozy studios to expansive 5-bedroom sanctuaries by the azure shores of Bizerte.
</p>
<h3><mark>Our offer</mark></h3>
<ul>
  <li>Villas</li>
  <li>Mini-villas</li>
  <li>Apartments</li>
</ul>

<p>
  Embark on a blissful tourist journey in <strong>Bizerte</strong>, where each day unfolds with</p>
<h4>your journey:</h4>
<ol>
  <li>A sumptuous breakfast</li>
  <li>Sun-soaked moments on pristine beaches</li>
  <li>Enchanting explorations of local treasures, and tranquil evenings immersed in the vibrant culture of this coastal haven.</li>
</ol>


<h4><em>More details:</em></h4>
<p>
  To see our accommodation options go to :<br>
  <a href="content/page3.html#kitchen">The kitchen</a><br>
  <a href="content/page3.html#garden">The garden</a><br>
  <a href="content/page3.html#room">The room</a><br>
</p>

<a href="content/page2.html"><mark>page2</mark></a> <br>
<a href="content/page3.html"><mark>page3</mark></a>

</body>
</html>
```

## 1.4 Insert images
### 1.4.1 Insert an image with the orphan tag `<img>`
The tag that allows you to insert an image is an orphan tag: `<img>`. To work correctly, it must be accompanied by two attributes:
1. src: This attribute indicates the source of the image.
2. alt: This attribute provides an alternative description for the image.

```html
<p>
  Kosksi:<br>
  <img src="../pics/kosksi.jpg" alt="kosksi" />
</p>
```

### 1.4.2 Choose the right image format
Here's which format to adopt based on the type of image you have:

- A photo: use JPEG.
- Any image with few colors (less than 256): use PNG 8 bits, or optionally GIF.
- Any image with many colors: use PNG 24 bits.
- An animated image: use an animated GIF.
- A vector logo: use SVG.

### 1.4.3 Add a tooltip with the `title` attribute

To display a tooltip on your images, you can use the `title` attribute (not to be confused with the `<title>` tag, which indicates the browser's title for a web page). The `title` attribute is optional, unlike `alt`.

Here's how it can be done:

```html
<p>
  Lablebi:<br>
  <img src="../pics/lablebi.jpg" title="Bizerte's most famous street food" alt="lablebi" />
</p>
```

Visitors to the site only need to hover over the image with the mouse to see the tooltip "Bizerte's most famous street food" appear over the image.

### 1.4.4 Create a clickable thumbnail

If your image is very large, it's advisable to display a clickable thumbnail on your site. This way, your web pages will load faster. If visitors want to see your images in their original size, they can click on them. To achieve this, you need two versions of a photo: the original image and a lighter version (smaller).
Let's see how to make the thumbnail clickable:
1. Place your two images in a folder called, for example, "images."
2. Display the "dolphin_mini.jpg" version on a page.
3. Link to the "dolphin.jpg" version.

The enlarged image is displayed when clicking on the thumbnail.

```html
<p>
  Would you like to see the dolphin in its original size? Click on it!<br>
  <a href="pics/dolphin.jpg"><img src="pics/dolphin_mini.jpg" title="Dolphin greetings" alt="Dolphin greetings" title="Click to zoom"></a>
</p>
```

# 2. Format your web pages with CSS3
## 2.1 Integrate CSS into the HTML Page

To link the `.css` and `.html` files, you will add a line in the `.html` file to instruct the browser to fetch the stylesheet to display the web page with the applied style properties. This line to be added to the `.html` file opens with the orphan tag `<link>` and is placed inside the `<head> </head>` tags:

- First, create a file named `style.css`, and edit your `index.html` as follows:

```html
<head>
  <meta charset="utf-8">
  <title>HabibiComeToTunisia</title>
  <link href="style.css" rel="stylesheet">
</head>
```

## 2.1 Apply a CSS property to an HTML page

In the `style.css` file, write:

```css
h2, h3 {
  color: royalblue;
}
```

This means that the color `royalblue` will be applied to the `h2` and `h3` level titles.

### 2.1.1 Apply a style to an isolated element with the `class` attribute

To apply a style to a single element (e.g., a single paragraph among all the paragraphs in your code), you can - in theory - use two attributes: 1. the `class` attribute, or 2. the `id` attribute. But in practice, you will mainly use the `class` attribute.

- Step 1: Mark an element with the `class` attribute in the `index.html` file:

```html
<p class="my-class">
  Experience the perfect blend of comfort and adventure. Welcome to HabibiComeToTunisia.com, your exclusive gateway to unforgettable waterfront getaways in Bizerte, Tunisia.
</p>
```

- Step 2: Call the name of the `class` attribute with a `.` in the `style.css` file:

```css
.my-class {
  color: gray;
}
```

### 2.1.2 Apply a CSS property to a unique element with the `id` attribute

The `id` attribute works in the same way as the `class` attribute, but there is a significant difference: `id` can only be used once in the code. In CSS, there isn't much difference; it will be especially useful if you do JavaScript later to recognize certain tags. In HTML, there is one because, remember, we used it in the chapter on hyperlinks to create anchors. In practice, therefore, you will use an `id` in CSS only on an element that is unique in the page, like the logo, for example.

- Step 1: Mark a unique element with the `id` attribute in the `.html` file.
  For example, with the logo, a unique element that we will "mark" with the `id` attribute in the `.html` file:

```html
<img src="pics/logo.png" alt="Logo of the website" id="logo">
```

- Step 2: Call the `id` attribute with a `#` in the `.css` file:

```css
#logo {
  /* Add CSS properties here */
}
```

### 2.1.3 Utilize universal tags `<span>` or `<div>`

Suppose you want to modify `HabibiComeToTunisia.com` in the following paragraph:

```html
<p>
  Experience the perfect blend of comfort and adventure. Welcome to HabibiComeToTunisia.com, your exclusive gateway ...
</p>
```

1. `<span>` `</span>`: This is an "inline" type tag, which means a tag that is placed within a text paragraph to select specific words only.
2. `<div>` `</div>`: This is a "block" type tag, which surrounds a block of text. It creates a new "block" on the page and therefore causes a line break.

- Step 1: Surround the element with `<span>` `</span>` and mark it with the `class` attribute in the `.html` file:

```html
<p>
  Experience the perfect blend of comfort and adventure. Welcome to <span class="my-class2">HabibiComeToTunisia.com</span>, your exclusive gateway...
</p>
```

- Step 2: Call the name of the `class` attribute with a `.` in the `.css` file:

```css
.my-class2 {
  color: royalblue;
  font-weight: bold;
}
```

### 2.1.4 Insert an image in the background at the Title level

```html
<head>
<meta charset="utf-8">
<title>HabibiComeToTunisia</title>
<style>
 body {
   background-image: url('pics/camel_2.jpg');
   background-position: left top;
   background-repeat: no-repeat;
   padding-left: 10px;
   padding-top: 200px;
   margin: 0; /* Remove default body margin */
   width: 100%; /* Extend the image across the full width of the screen */
 }
</style>
<link href="style.css" rel="stylesheet">
</head>
```

Here are some other values you might use with `background-repeat`:

- repeat-x: The image is repeated horizontally but not vertically.
- repeat-y: The image is repeated vertically but not horizontally.
- repeat: The image is repeated both horizontally and vertically.
- space: The image is repeated to fill the element with equal spacing between the images. If the element is not a complete multiple of the image size, the last image may be truncated.

## 2.2 Change Text Appearance
### 2.2.1 Change the Size and Style of Text
- To modify the size of the h1 title:
  in the `style.css` file:
```css
h1 {
  font-size: 3em;
  color: white;
  font-family: 'Lobster', sans-serif;
}
```
### 2.2.2 Italicize Text
- To italicize paragraph text:
  in the `style.css` file:
```css
p {
  font-style: italic;
}
```
### 2.2.3 Make Text Bold with the CSS font-weight Property
To vary the thickness of text, the CSS font-weight property is used, and you can assign one of the following values:
- `bold`: the text will be bold;
- `normal`: the text will be written normally (default);
- `thin`: the text is thinner.

It's also possible to be more precise and indicate the thickness of the text with a numerical value ranging from 100 to 900, from thinnest to thickest.

### 2.2.4 Underline Text with the CSS text-decoration Property
The CSS text-decoration property allows, among other things, to underline the text, but not only. Here are some of the different values it can take:
- `underline`: underlined
- `line-through`: strikethrough
- `none`: normal (default, except for links).

To write the word `luxury` in bold and underline, you need to indicate the word to be modified with `<span></span>` in the `index.html` file:

```html
<p>
  Indulge in the epitome of <span class="my-class3">luxury</span> with our exquisite range of villas, mini-villas, and apartments...
</p>
```

And in the `style.css` file:

```css
.my-class3 {
  font-weight: 700;
  text-decoration: underline;
}
```
### 2.2.5 Align Text with the CSS text-align Property
The CSS text-align property allows aligning text according to the given value:
- `left`: text will be aligned to the left (default setting)
- `center`: text will be centered
- `right`: text will be aligned to the right

To center the text of the h1 title, go to the `style.css` file:
```css
h1 {
  text-align: center;
}
```

### 2.2.6 Change the Font Type
- When dealing with text containing long paragraphs, choose a `Sans Serif` font: Inter, Montserrat, Roboto, Poppins.
- Google Font -> free and royalty-free font -> copy the font link and paste it into the HTML code's head section.
- Google Font -> copy CSS rules to specify families and paste them into our CSS file. Check the link: [Google Fonts - Lobster](https://fonts.google.com/specimen/Lobster?query=lobster)

- Step 1: Copy the <link> tags into the <head> </head> section of the HTML file, `index.html`:
```html
<head>
<meta charset="utf-8">
<title>HabibiComeToTunisia</title>

<link href="style.css" rel="stylesheet">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
</head>
```

- Step 2: Use the font-family property in the CSS file to declare that you want to use this font, `style.css` file:
```css
h1 {
  font-family: 'Lobster', sans-serif;
}
```


# 2.3 Add Color and Background

## 2.3.1 Change Text Color with `color`

The CSS property used to modify text color is `color`.

```css
h1 {
  color: blue;
}
```

While many color names are supported by browsers, there are other ways to indicate a color in CSS:

- In hexadecimal form (6 digits preceded by a #). Example: `color: #FFC8D3;`
- In RGB notation (for Red Green Blue in English). Example: `color: rgb(5, 102, 125);`. Note that opacity (or transparency) can be added with RGBA notation, where the last value corresponds to opacity: `color: rgba(5, 102, 125, 0.5);`

```css
h2 {
  color: rgba(5, 102, 125, 0.5);
}
```

If you want to find a color or convert a value using another syntax, you can use online tools like [Coolors](https://coolors.co/) or [HTML Color Picker](https://www.w3schools.com/colors/colors_picker.asp), or simply search for 'color picker' on Google.

## 2.3.2 Apply Background Color with `background-color`

To indicate a background color, the CSS `background-color` property is used. It is used similarly to the `color` property, allowing you to use color names, hexadecimal notation, or RGB method.

```css
body {
  background-color: black; /* The page background will be black */
  color: white; /* The page text will be white */
}
```

## 2.3.3 Add a Background Image with `background-image`

A background image doesn't have to apply to the entire page. You can also place a background image behind titles or paragraphs. The property for indicating a background image is `background-image`, and you should provide the address where the image is located.

```css
body {
  background-image: url('../pics/wave-banner.jpg');
  background-attachment: fixed;
  background-size: cover;
  background-position: bottom;
  opacity: 0.8;
}
```

When writing a relative address in the CSS file, keep in mind that the image address should be relative to the .css file, not the .html file. For simplicity, it's recommended to place the background image in the same folder as the .css file (or in a subfolder).

To achieve this, create a file named `page4.html` and `style4.css` in the `content` folder.

HTML file (`page4.html`):

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>HabibiComeToTunisia</title>
  <link href="style4.css" rel="stylesheet">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
</head>

<body>
  <div class="banner">
    <h1>My blog</h1>
  </div>
  <p>This is the content of my first paragraph</p>
  <p>This is the content of my second paragraph</p>

  <a href="../index.html"><mark>home</mark></a>
</body>
</html>
```

CSS file (`style4.css`):

```css
body {
  background-color: #e4e7f0;
  font-family: sans-serif;
  margin: 0; /* This ensures that our elements take up the full width of the page */
}

.banner {
  padding: 100px;
  background-image: url('../pics/wave-banner.jpg');
  background-attachment: fixed;
  background-size: cover;
  background-position: bottom;
  opacity: 0.8;
}

h1 {
  font-size: 50px;
  color: #031140;
  font-family: 'Lobster', sans-serif;
  text-align: center;
}
```

To alter the behavior of a background image, there are several CSS properties:

- `background-attachment: fixed;`: Makes the background image fixed when scrolling.
- `background-size: cover;`: Resizes the image to fit the container, maintaining its proportions.
- `background-position: top right;`: Positions the background image.

Each of these properties has various possible values that can be associated with them. You can experiment with different effects on the [Mozilla Developer](https://developer.mozilla.org/) website.

### 2.3.3.1 Combine CSS Properties with the 'background' Super-Property

If you use many properties related to the background, you can use a kind of "super-property" called `background`, whose value can combine several of the properties:

```css
.banner {
  background: url('../pics/wave-banner.jpg') cover center;
}
```

Note that the order of values doesn't matter; you can combine them in any order.

## 2.3.4 Create Gradients with `linear-gradient`

To create a gradient, you need the CSS property `background`:

```css
.gradient {
  background: linear-gradient(90deg, #8360c3, #2ebf91);
}
```

Here, `linear-gradient` is used, but there are other ways to create gradients. If you want inspiration for gradients, visit [UI Gradients](https://uigradients.com/#Bupe).


## 2.4 Create borders and shadows

## 2.5 Create dynamic appearances
