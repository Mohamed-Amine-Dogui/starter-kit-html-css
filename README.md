
#

Introduction

Welcome to the go-to resource for kickstarting your front-end web development journey with HTML5 and CSS3. By delving into HTML and CSS, you'll gain the skills to breathe life into your web projects, creating interfaces that captivate and engage users.

## Table of Contents

- [1. Create Your First Web Page in HTML](#1-create-your-first-web-page-in-html)
  - [1.1 Mastering HTML Tags](#11-mastering-html-tags)
  - [1.2 Customize Tags with Attributes](#12-customize-tags-with-attributes)
  - [1.3 Use the Basic Structure of an HTML Page](#13-use-the-basic-structure-of-an-html-page)
  - [1.4 Comment Your HTML Code](#14-comment-your-html-code)
- [2. Organize Your Text](#2-organize-your-text)
  - [2.1 Create Paragraphs with `<p>` Tags](#21-create-paragraphs-with-p-tags)
  - [2.2 Line Break with `<br>` Orphan Tag](#22-line-break-with-br-orphan-tag)
  - [2.3 Create Headings with `<h1>`, `<h2>`, `<h3>`, ...](#23-create-headings-with-h1-h2-h3-)
  - [2.4 Create Lists with `<li>` and `<ul>` or `<ol>`](#24-create-lists-with-li-and-ul-or-ol)
  - [2.5 Emphasize Important Text](#25-emphasize-important-text)
- [3. Create a Hypertext Link in HTML](#3-create-a-hypertext-link-in-html)
  - [3.1 Create a Hypertext Link with the `<a>` Tag and the `href` Attribute](#31-create-a-hypertext-link-with-the-a-tag-and-the-href-attribute)
    - [3.1.1 Create a Hypertext Link from One Page to Another on Your Site](#311-create-a-hypertext-link-from-one-page-to-another-on-your-site)
    - [3.1.2 Create a Hypertext Link to the URL of a Page Available on the Internet](#312-create-a-hypertext-link-to-the-url-of-a-page-available-on-the-internet)
  - [3.2 Create an Anchor with the `id` and `href` Attributes](#32-create-an-anchor-with-the-id-and-href-attributes)
    - [3.2.1 The Anchor is Further Down on the Same Page](#321-the-anchor-is-further-down-on-the-same-page)
    - [3.2.2 The Anchor is Located in Another Page](#322-the-anchor-is-located-in-another-page)
  - [3.3 Special Configuration of Links](#33-special-configuration-of-links)
- [4. Insert Images](#4-insert-images)
  - [4.1 Insert an Image with the Orphan Tag `<img>`](#41-insert-an-image-with-the-orphan-tag-img)
  - [4.2 Choose the Right Image Format](#42-choose-the-right-image-format)
  - [4.3 Add a Tooltip with the `title` Attribute](#43-add-a-tooltip-with-the-title-attribute)
  - [4.4 Create a Clickable Thumbnail](#44-create-a-clickable-thumbnail)
- [5. Integrate CSS into the HTML Page](#5-integrate-css-into-the-html-page)
  - [5.1 Apply a CSS Property to an HTML Page](#51-apply-a-css-property-to-an-html-page)
  - [5.2 Apply a Style to an Isolated Element with the `class` Attribute](#52-apply-a-style-to-an-isolated-element-with-the-class-attribute)
  - [5.3 Utilize Universal Tags `<span>` or `<div>`](#53-utilize-universal-tags-span-or-div)
  - [5.4 Insert an Image in the Background at the Title Level](#54-insert-an-image-in-the-background-at-the-title-level)


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

# 1. Create your first web page in HTML
## 1.1 Mastering HTML tags

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

## 1.2 Customize tags with attributes

Tags are sometimes accompanied by attributes to provide additional information or configure an element (e.g., `<img src="photo.jpg">`).
![Orphan Tag](pics/orphan_tag.jpg)

## 1.3 Use the basic structure of an HTML page

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

## 1.4 Comment your HTML code

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


# 2. Organize your text

## 2.1 Create paragraphs with `<p>` tags

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

## 2.2 Line break with `<br>` orphan tag

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

## 2.3 Create Headings with `<h1>`, `<h2>`, `<h3>`, ...

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

## 2.4 Create Lists with `<li>` and `<ul>` or `<ol>`

### Step 1: Enclose list items with `<li> </li>`
To mark elements in a list, use `<li> </li>` (for "listed item"). Then, insert them all inside another tag to indicate whether it's an unordered list or an ordered list.

### Step 2: Insert the list into `<ul> </ul>` or `<ol> </ol>`
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

## 2.5 Emphasize important text

In web page text, you may want to highlight specific words. The most commonly used tag for this is `<strong>`, but HTML offers various ways to emphasize

text on your page.

| Tags                 | Browser Rendering               |
|----------------------|---------------------------------|
| `<mark></mark>`      | Highlight the text.             |
| `<em></em>`          | Make the text italic.           |
| `<strong></strong>`  | Make the text bold.             |


# 3. Create a hypertext link in HTML

## 3.1 Create a hypertext link with the `<a>` Tag and the `href` attribute

1. Use the `<a>` tag (for "anchor") to indicate that you will redirect to another location.
2. Add the `href` attribute followed by `=` to announce the location to which you want to redirect.
3. Explicitly specify the location to which the link should redirect between " ".
4. Finally, write the text that should appear on the hyperlink.

### 3.1.1 Create a hypertext Link from one page to another on your site

To achieve this, create a folder named `content` and a file named `page2.html`.
Add the following line at the end of the body of `index.html` to enable navigation to page2:

```html
<a href="content/page2.html">Next</a>
```

### 3.1.2 Create a hypertext link to the url of a page available on the internet

To redirect the user to our Facebook page, add the following content to `page2.html`:

```html
<h4><em>Follow us on Facebook:</em></h4>
<a href="https://www.facebook.com/ResidenceDesPin" target="_blank">Facebook</a> <br>
```

## 3.2 Create an anchor with the `id` and `href` attributes

To create an anchor, add the `id` attribute to a tag that will serve as a marker. It can be any tag, such as a title tag.
Here's how you can do it: The first step is to add the `id` attribute followed by `=` to give a name to the anchor between " ":

```html
<h2 id="my_anchor">Title</h2>
```

The `id` attribute is used to give a "unique" name to a tag, to use it as a reference. Here, we use it to create a link to an anchor, but in CSS, it can be useful to locate a specific tag.

### 3.2.1 The anchor is further down on the same page

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

### 3.2.2 The anchor is located in another page

In this case, type the name of the target page before the hash `#` and finally the name of the anchor:

```html
<a href="content/page3.html#garden">The garden</a>
```

## 3.3 Special configuration of links

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

# 4. Insert images
## 4.1 Insert an image with the orphan tag `<img>`
The tag that allows you to insert an image is an orphan tag: `<img>`. To work correctly, it must be accompanied by two attributes:
1. src: This attribute indicates the source of the image.
2. alt: This attribute provides an alternative description for the image.

```html
<p>
  Kosksi:<br>
  <img src="../pics/kosksi.jpg" alt="kosksi" />
</p>
```

## 4.2 Choose the right image format
Here's which format to adopt based on the type of image you have:

- A photo: use JPEG.
- Any image with few colors (less than 256): use PNG 8 bits, or optionally GIF.
- Any image with many colors: use PNG 24 bits.
- An animated image: use an animated GIF.
- A vector logo: use SVG.

## 4.3 Add a tooltip with the `title` attribute

To display a tooltip on your images, you can use the `title` attribute (not to be confused with the `<title>` tag, which indicates the browser's title for a web page). The `title` attribute is optional, unlike `alt`.

Here's how it can be done:

```html
<p>
  Lablebi:<br>
  <img src="../pics/lablebi.jpg" title="Bizerte's most famous street food" alt="lablebi" />
</p>
```

Visitors to the site only need to hover over the image with the mouse to see the tooltip "Bizerte's most famous street food" appear over the image.

## 4.4 Create a clickable thumbnail

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

# 5. Integrate CSS into the HTML Page

To link the `.css` and `.html` files, you will add a line in the `.html` file to instruct the browser to fetch the stylesheet to display the web page with the applied style properties. This line to be added to the `.html` file opens with the orphan tag `<link>` and is placed inside the `<head> </head>` tags:

- First, create a file named `style.css`, and edit your `index.html` as follows:

```html
<head>
  <meta charset="utf-8">
  <title>HabibiComeToTunisia</title>
  <link href="style.css" rel="stylesheet">
</head>
```

## 5.1 Apply a CSS property to an HTML page

In the `style.css` file, write:

```css
h2, h3 {
  color: royalblue;
}
```

This means that the color `royalblue` will be applied to the `h2` and `h3` level titles.

## 5.2 Apply a style to an isolated element with the `class` attribute

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

## 5.3 Utilize universal tags `<span>` or `<div>`

Suppose you want to modify `HabibiComeToTunisia.com` in the following paragraph:

```html
<p>
  Experience the perfect blend of comfort and adventure. Welcome to HabibiComeToTunisia.com, your exclusive gateway ...
</p>
```

1. `<span>` `</span>`: This is an "inline" type tag, which means a tag that is placed within a text paragraph to select specific words only.
2. `<div>` `</div>`: This is a "block" type tag, which surrounds a block of text. It creates a new "block" on the page and therefore causes a line break.

- Step 1: Surround the element with `<span>` `</span>` and mark it with the `class` attribute in the `index.html` file:

```html
<p>
  Experience the perfect blend of comfort and adventure. Welcome to <span class="my-class2">HabibiComeToTunisia.com</span>, your exclusive gateway...
</p>
```

- Step 2: Call the name of the `class` attribute with a `.` in the `style.css` file:

```css
.my-class2 {
  color: royalblue;
  font-weight: bold;
}
```

## 5.4 Insert an image in the background at the Title level

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
