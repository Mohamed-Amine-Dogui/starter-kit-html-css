# starter-kit-html-css

Welcome to the go-to resource for kickstarting your front-end web development journey with HTML5 and CSS3. By delving into HTML and CSS, you'll gain the skills to breathe life into your web projects, creating interfaces that captivate and engage users.

## table of contents

- [Why learn two languages html5 and css3 separately?](#why-learn-two-languages-html5-and-css3-separately)
- [In summary](#in-summary)
- [1. Mastering HTML tags](#1-mastering-html-tags)
  - [1.1 Customize tags with attributes](#11-customize-tags-with-attributes)
  - [1.2 Use the basic structure of an HTML page](#12-use-the-basic-structure-of-an-html-page)
  - [1.3 Comment your HTML code](#13-comment-your-html-code)


## Why learn two languages html5 and css3 separately?

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

### In summary

- HTML forms the structure of a web page.
- CSS adds style to the structure.
- Both languages complement each other with distinct roles for each.
- The browser is software that reads the languages of the web: HTML and CSS.
- All browsers include development tools, including the inspection tool that provides access to the HTML and CSS of a page.

# 1. Mastering html tags

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

## 1.1 Customize tags with attributes

Tags are sometimes accompanied by attributes to provide additional information or configure an element (e.g., `<img src="photo.jpg">`).
![Orphan Tag](pics/orphan_tag.jpg)

## 1.2 Use the basic structure of an html page

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

## 1.3 Comment your html code

In HTML, a comment is simply a memo. It has a specific format: `<!-- This is a comment -->`.
To comment lines (or even multiple lines) in Visual Studio Code:
1. Select the line(s) in question.
2. Use the keyboard shortcut with CTRL + k, then CTRL + c.
