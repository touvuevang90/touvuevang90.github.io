# Inventory of files and folder
/divisima/css

## css style 
1. animate.css
- is a bunch of cool, fun, and cross-browser animations for you to use in your projects. Great for emphasis, home pages, sliders, and general just-add-water-awesomeness.

2. bootstrap.min.css
- has been minified meaning all the whitespace and other extra characters have been removed. This is commonly done for use in production, to reduce the size of the file. When developing, it is usually helpful to use the unminified version, since, as you said, it is readable.

3. flaticon.css
- is a set of fonts that allows developers to quickly convert icons into webfonts by displaying vector icons into your website and control them with CSS.
    - Features
        1. High Resolution - Icons are scalable and retina-ready. Perfect for a responsive design. They look nice on screens of any resolution.
        2. Quick and easy - Building iconfonts with Flaticon is easier than ever. Add icons to your collections and download them in seconds.
        3. Total controll CSS - Iconfonts are basically text, so you can change their aspect easily with CSS.
        4. Accessible - Flaticon name symbols with common terms to help screen readers understand their meaning
        5. Animatable - CSS transitions and animations are completely compatible with iconfonts
        6. Tidy - No more loads of images or cumbersome sprites. Stop wasting your time!

4. font-awesome.min.css
- Font Awesome is designed to be used with inline elements. The <i> and <span> elements are widely used for icons.

5. jquery-ui.min.css
- is a curated set of user interface interactions, effects, widgets, and themes built on top of the jQuery JavaScript Library. Likewise, it is built for designers and developers with full packages of incredibly flexible kits. Indeed, jQuery UI is the perfect option whether you're building highly interactive web applications even if you just need to add a little kick to a form control.

6. owl.carousel.min.css
- Touch enabled jQuery plugin that lets you create a beautiful responsive carousel slider. Full of many customisable options, touch and drag support, modern to zombies browsers, modules and plugins. 

7. slicknav.min.css
- is a responsive mobile menu plugin for jQuery and comes with abundant combination of features that can be modified to fit website design such as multi-level menu support, flexible simple mark up, cross-browser compatibility, keyboard Accessible, degrades gracefully without JavaScript, and creates ARIA compliant menu. 

8. style.css
- is a stylesheet (CSS) file required for every WordPress theme. It controls the presentation (visual design and layout) of the website pages.

9. .btn 
- Button file used by AutoPlay Media Studio.
- High speed application development tool used to create CD menus, games, and multimedia applications.
- stores the button styles and can specify a scripted action to take when the button is clicked.

10. CSS @keyframes ----------
- The @keyframes rule specifies the animation code.
- The animation is created by gradually changing from one set of CSS styles to another.
- During the animation, you can change the set of CSS styles many times.
- Specify when the style change will happen in percent, or with the keywords "from" and "to", which is the same as 0% and 100%. 0% is the beginning of the animation, 100% is when      the animation is complete.

Example:        @-webkit-keyframes loader {
	            0% {
		            -webkit-transform: rotate(0deg);
		            border: 4px solid #f44336;
		            border-left-color: transparent;
	            }

## More Information
## icon-fonts
1. Flaticon.eot
- Embedded OpenType (EOT) fonts are a compact form of OpenType fonts designed by Microsoft for use as embedded fonts on web pages. These files use the extension .eot . They are supported only by Microsoft Internet Explorer, as opposed to competing WOFF files.

2. Flaticon.svg
- An SVG file is a graphics file that uses a two-dimensional vector graphic format created by the World Wide Web Consortium (W3C). It describes images using a text format that is based on XML.

3. Flaticon.ttf
- A TTF file is a font file format created by Apple, but used on both Macintosh and Windows platforms. It can be resized to any size without losing quality and looks the same when printed as it does on the screen. The TrueType font is the most common font format used by both Mac OS X and Windows platforms.

4. Flaticon.woff
- A WOFF file is a web font file created in the WOFF (Web Open Font Format) format, an open format used for delivering webpage fonts on the fly. It is saved as a compressed container and supports TrueType (.TTF) and OpenType (.OTF) fonts and also supports font licensing information.

5. fontawesome-webfont.eot,svg,woff,woff2
- the web's most popular icon set and toolkit.

## JavaScript
1. bootstrap.min.js

2. jquery-3.2.1.min.js
- This release comes with some hotfixes for regressions that were introduced in the 3.2.0 build four days ago. We wanted to release this patch as quickly as possible to squash any bugs you may have experienced when upgrading. The most significant one had to do with retrieving width or height on an inline element with no explicitly-set dimensions

3. jquery-ui.min.js

4. jquery.nicescroll.min.js
- The best nicescroll release ever - extremely smooth and consistent in modern browsers and mobile devices, with low resource usage
    1. Features
        - simple installation and activation, it works with NO modification of your code. (some exceptions can happen, so you can write to me)
        - very stylish scrollbars, with no occupation on your window (original browser scrollbars need some of page space and reduces window/div usable width)
        - you can style main document scrollbar (body) too!! (not all device/browser support this feature)
        - on all browsers you can scroll: dragging the cursor, mouse wheel (speed customizable), keyboard navigation (cursor keys, pagup/down keys, home/end keys)
        - scroll is smooth (as modern tablet browsing), speed is customizable

5. jquery.slicknav.min.js
- SlickNav is a responsive mobile menu plugin for jQuery.

6. jquery.zoom.min.js
- A plugin to enlarge images on touch, click, or mouseover.

7. main.js
- standard file for your main application scripts, the code that would instantiate and use the plugins.

8. map.js
- stored as a Key, value pair in a set of its own special characteristics. Map object can support both objects and primitive values as either key or value. When iterating over a map object it returns the key, value pair in the same order as inserted.

9. owl.carousel.min.js
- Touch enabled jQuery plugin that lets you create a beautiful responsive carousel slider.

## SASS
1. What is SASS?
- Sass (Syntactically Awesome Style Sheets) is an extension of CSS that enables you to use things like variables, nested rules, inline imports and more. It also helps to keep things organised and allows you to create style sheets faster.
   
# Inventory of the code in the index.html
1. HTML Documents
- All HTML documents must start with a document type declaration: <!DOCTYPE html>.
- The HTML document itself begins with <html> and ends with </html>.
- The visible part of the HTML document is between <body> and </body>.

2. HTML Headings
- HTML headings are defined with the <h1> to <h6> tags.
- <h1> defines the most important heading. <h6> defines the least important heading: 

Example:    <h1>This is heading 1</h1>
            <h2>This is heading 2</h2>
            <h3>This is heading 3</h3>

3. HTML Paragraphs
- HTML paragraphs are defined with the <p> tag:

4. HTML Links
- HTML links are defined with the <a> tag:

Example: <a href="./product.html">Product Page</a>

5. HTML Buttons
- HTML buttons are defined with the <button> tage:

Example: <button><i class="flaticon-search"></i></button>

 6. HTML Lists
- HTML lists are defined with the <ul> (unordered/bullet list) or the <ol> (ordered/numbered list) tag, followed by <li> tags (list items):

Example: <ul class="sub-menu">
            <li><a href="#">Sneakers</a></li>
            <li><a href="#">Sandals</a></li>
            <li><a href="#">Formal Shoes</a></li>
            <li><a href="#">Boots</a></li>
            <li><a href="#">Flip Flops</a></li>
        </ul>

7. HTML <span> Tag
- a <span> element used to color a part of a text:

Example: <span>New Arrivals</span>

8. HTML <div> Tag
- A section in a document that will have a light blue background color.

9. HTML | Class Attribute
- The class is an attribute which specifies one or more class names for an HTML element.
- The class attribute can be used on any HTML element.
- The class name can be used by CSS and JavaScript to perform certain tasks for elements with the specified class name.

Example: <div class="col-lg-3 col-sm-6">
            <div class="product-item">
                <div class="pi-pic">
                    <div class="tag-sale">ON SALE</div>
                    <img src="./img/product/6.jpg" alt="">
                    <div class="pi-links">
                        <a href="#" class="add-card"><i class="flaticon-bag"></i><span>ADD TO CART</span></a>
                        <a href="#" class="wishlist-btn"><i class="flaticon-heart"></i></a>
                    </div>

10. Bootstrap Grid Examples
- Three Equal Columns
.col-sm-4   .col-sm-4   .col-sm-4

Example:    <div class="col-md-4 p-0 feature">
                <div class="feature-inner">
                    <div class="feature-icon">
                        <img src="img/icons/2.png" alt="#">
                    </div>
                    <h2>Premium Products</h2>
                </div>

- Three Unequal Columns
.col-sm-3   .col-sm-6   .col-sm-3

Example: <div class="row">
            <div class="col-lg-3 col-sm-6">
                <div class="footer-widget about-widget">
                    <h2>About</h2>
                    <p>Donec vitae purus nunc. Morbi faucibus erat sit amet congue mattis. Nullam frin-gilla faucibus urna, id dapibus erat iaculis ut. Integer ac sem.</p>
                    <img src="img/cards.png" alt="">
                </div>
            </div>

11. HTML <footer> Tag
- The <footer> tag defines a footer for a document or section.
- A <footer> element should contain information about its containing element.
- A <footer> element typically contains.
    - authorship information
    - copyright information
    - contact information
    - sitemap
    - back to top links
    - related documents
Note: You can have several <footer> elements in one document.

Example: <!-- Footer section -->
<section class="footer-section">
        <div class="container">
            <div class="footer-logo text-center">
                <a href="index.html"><img src="./img/logo-light.png" alt=""></a>
            </div>

12. HTML The class attribute
- The HTML class attribute is used to define equal styles for elements with the same class name.
- So, all HTML elements with the same class attribute will have the same format and style.
- Here we have three <div> elements that point to the same class name.

Example: <!-- letest product section -->
<section class="top-letest-product-section">
		<div class="container">
			<div class="section-title">
				<h2>LATEST PRODUCTS</h2>
			</div>
			<div class="product-slider owl-carousel">
				<div class="product-item">
					<div class="pi-pic">
						<img src="./img/product/1.jpg" alt="">
						<div class="pi-links">
							<a href="#" class="add-card"><i class="flaticon-bag"></i><span>ADD TO CART</span></a>
							<a href="#" class="wishlist-btn"><i class="flaticon-heart"></i></a>
						</div>
					</div>

13. Preloading content with rel="preload"
- The preload value of the <link> element's rel attribute allows you to write declarative fetch requests in your HTML <head>, specifying resources that your pages will need very soon after loading, which you therefore want to start preloading early in the lifecycle of a page load, before the browser's main rendering machinery kicks in. This ensures that they are made available earlier and are less likely to block the page's first render, leading to performance improvements. 

14. HTML <link> Tag
- Link to an external style sheet.

Example: <!-- Stylesheets -->
        <link rel="stylesheet" href="css/bootstrap.min.css"/>
        <link rel="stylesheet" href="css/font-awesome.min.css"/>
        <link rel="stylesheet" href="css/flaticon.css"/>
        <link rel="stylesheet" href="css/slicknav.min.css"/>
        <link rel="stylesheet" href="css/jquery-ui.min.css"/>
        <link rel="stylesheet" href="css/owl.carousel.min.css"/>
        <link rel="stylesheet" href="css/animate.css"/>
        <link rel="stylesheet" href="css/style.css"/>

15. HTML <meta> Tag
- Describe metadata within an HTML document.

Example: <meta charset="UTF-8">
         <meta name="description" content=" Divisima | eCommerce Template">
         <meta name="keywords" content="divisima, eCommerce, creative, html">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">

16. HTML <title> Tag
- Define a title for your HTML document.

Example: <!DOCTYPE html>
        <html lang="zxx">
        <head>
            <title>Divisima | eCommerce Template</title>
        </head>

17. HTML <body> Tag
- A simple HTML document.

Example: <html>
        <head>
        <title>Divisima | eCommerce Template</title>
        </head>
        <body> The content of the document......</body>
        </body>
        </html>

18. HTML <nav> Tag
- A set of navigation links.

Example: <nav class="main-navbar">
            <div class="container">
                <!-- menu -->
                <ul class="main-menu">
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Women</a></li>
                    <li><a href="#">Men</a></li>
                    <li><a href="#">Jewelry
                        <span class="new">New</span>
                    </a></li>

19. HTML <li> Tag
- One order (<ol>) and one unordered (<ul>) HTML list.

Example: <li><a href="#">Pages</a>
            <ul class="sub-menu">
                <li><a href="./product.html">Product Page</a></li>
                <li><a href="./category.html">Category Page</a></li>
                <li><a href="./cart.html">Cart Page</a></li>
                <li><a href="./checkout.html">Checkout Page</a></li>
                <li><a href="./contact.html">Contact Page</a></li>
            </ul>

20. HTML <header> Tag
- A header for an <article>.

Example: <!-- Header section -->
        <header class="header-section">
            <div class="header-top">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-2 text-center text-lg-left">
                            <!-- logo -->
                            <a href="./index.html" class="site-logo">
                                <img src="img/logo.png" alt="">
                            </a>
                        </div>

21. HTML <section> Tag
- A section in a document explaining what WWF is.

Example: <!-- Hero section -->
        <section class="hero-section">
            <div class="hero-slider owl-carousel">
                <div class="hs-item set-bg" data-setbg="img/bg.jpg">
                    <div class="container">
                        <div class="row">
                            <div class="col-xl-6 col-lg-7 text-white">
                                <span>New Arrivals</span>
                                <h2>denim jackets</h2>
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum sus-pendisse ultrices gravida. Risus commodo viverra maecenas accumsan lacus vel facilisis. </p>
                                <a href="#" class="site-btn sb-line">DISCOVER</a>
                                <a href="#" class="site-btn sb-white">ADD TO CART</a>
                            </div>
                        </div>

22. HTML <a> href Attribute
- The href attribute specifies the link's destination:

Example:    <a href="" class="instagram"><i class="fa fa-instagram"></i><span>instagram</span></a>
            <a href="" class="google-plus"><i class="fa fa-google-plus"></i><span>g+plus</span></a>
            <a href="" class="pinterest"><i class="fa fa-pinterest"></i><span>pinterest</span></a>
            <a href="" class="facebook"><i class="fa fa-facebook"></i><span>facebook</span></a>
            <a href="" class="twitter"><i class="fa fa-twitter"></i><span>twitter</span></a>
            <a href="" class="youtube"><i class="fa fa-youtube"></i><span>youtube</span></a>
            <a href="" class="tumblr"><i class="fa fa-tumblr-square"></i><span>tumblr</span></a>

23. HTML <script> Tag
- The <script> tag is used to define a client-side script (JavaScript).
- The <script> element either contains scripting statements, or it points to an external script file through the src attribute.
- Common uses for JavaScript are image manipulation, form validation, and dynamic changes of content.

Example:    <script src="js/jquery-3.2.1.min.js"></script>
            <script src="js/bootstrap.min.js"></script>
            <script src="js/jquery.slicknav.min.js"></script>
            <script src="js/owl.carousel.min.js"></script>
            <script src="js/jquery.nicescroll.min.js"></script>
            <script src="js/jquery.zoom.min.js"></script>
            <script src="js/jquery-ui.min.js"></script>
            <script src="js/main.js"></script>

24. <div class="pi-text">
- .pi-header block is main header wrapper that include each header row
 
 Example:   <div class="pi-text">
                <h6>$35,00</h6>
                <p>Flamboyant Pink Top </p>
            </div>

25. add-card
- A card is a flexible and extensible content container. It includes options for headers and footers, a wide variety of content, contextual background colors, and powerful display options.

Example:    <div class="pi-pic">
                <img src="./img/product/9.jpg" alt="">
                <div class="pi-links">
                    <a href="#" class="add-card"><i class="flaticon-bag"></i><span>ADD TO CART</span></a>
                    <a href="#" class="wishlist-btn"><i class="flaticon-heart"></i></a>
            </div>

26. HTML <input> Tag
- An HTML form with 3 input fields with two text firlds and one submit button.

Example:    <div class="range-slider">
                <div class="price-input">
                    <input type="text" id="minamount">
                    <input type="text" id="maxamount">
                </div>
            </div>



27. HTML <table> Tag
- A simple HTML table containing two columns and two rows:

28. HTML <tbody> Tag
- An HTML table with a <thead>, <body>, and a <tfoot>element.

29. HTML <td> Tag
- A simple HTML table with two table cells.

30. HTML <tr> Tag
- A simple HTML table containing two columns and two rows.

Below is an Example:

<table>
<thead>
    <tr>
        <th class="product-th">Product</th>
        <th class="quy-th">Quantity</th>
        <th class="size-th">SizeSize</th>
        <th class="total-th">Price</th>
    </tr>
</thead>
<tbody>
    <tr>
        <td class="product-col">
            <img src="img/cart/1.jpg" alt="">
            <div class="pc-title">
                <h4>Animal Print Dress</h4>
                <p>$45.90</p>
            </div>
        </td>
        <td class="quy-col">
            <div class="quantity">
                <div class="pro-qty">
                    <input type="text" value="1">
                </div>
            </div>
        </td>
        <td class="size-col"><h4>Size M</h4></td>
        <td class="total-col"><h4>$45.90</h4></td>
    </tr>
    <tr>
        <td class="product-col">
            <img src="img/cart/2.jpg" alt="">
            <div class="pc-title">
                <h4>Ruffle Pink Top</h4>
                <p>$45.90</p>
            </div>
        </td>
        <td class="quy-col">
            <div class="quantity">
                <div class="pro-qty">
                    <input type="text" value="1">
                </div>
            </div>
        </td>
        <td class="size-col"><h4>Size M</h4></td>
        <td class="total-col"><h4>$45.90</h4></td>
    </tr>
    <tr>
        <td class="product-col">
            <img src="img/cart/3.jpg" alt="">
            <div class="pc-title">
                <h4>Skinny Jeans</h4>
                <p>$45.90</p>
            </div>
        </td>
        <td class="quy-col">
            <div class="quantity">
                <div class="pro-qty">
                    <input type="text" value="1">
                </div>
            </div>
        </td>
        <td class="size-col"><h4>Size M</h4></td>
        <td class="total-col"><h4>$45.90</h4></td>
    </tr>
</tbody>
</table>

31. HTML <i> Tag
- The <i> tag defines a part of text in an alternate voice or mood. The content of the <i> tag is usually displayed in italic.
- The <i> tag can be used to indicate a technical term, a phrase from another language, a thought, or a ship name, etc.
- Use the <i> element only when there is not a more appropriate semantic element, such as:

<em> (emphasized text)
<strong> (important text)
<mark> (marked/highlighted text)
<cite> (the title of a work)
<dfn> (a definition term)

Example:    <button><i class="flaticon-search"></i></button>
            <i class="flaticon-profile"></i>

32. HTML <textarea> Tag
- The <textarea> tag defines a multi-line text input control.
- A text area can hold an unlimited number of characters, and the text renders in a fixed-width font (usually Courier).
- The size of a text area can be specified by the cols and rows attributes, or even better; through CSS' height and width properties.

Example:    <form class="contact-form">
                    <input type="text" placeholder="Your name">
                    <input type="text" placeholder="Your e-mail">
                    <input type="text" placeholder="Subject">
                    <textarea placeholder="Message"></textarea>
                    <button class="site-btn">SEND NOW</button>
            </form>

33. HTML <img> src Attribute
- An image is marked up as follows.

Example:    <img src="img/icons/3.png" alt="#">

34. HTML <form> Tag
- An HTML form with two input fields and on submit button.
    The <form> tag is used to create an HTML form for user input.

The <form> element can contain one or more of the following form elements:

<input>
<textarea>
<button>
<select>
<option>
<optgroup>
<fieldset>
<label>

Example:    <div class="col-xl-6 col-lg-5">
                <form class="header-search-form">
                    <input type="text" placeholder="Search on divisima ....">
                    <button><i class="flaticon-search"></i></button>
                </form>
            </div>

35. HTML content Attribute
- The content attribute gives the value associate with the http-equiv or name attribute
- Applies to the conntent attribute which can be use on the following element:
    Element: <meta>         Attribute: content

Example:    <title>Divisima | eCommerce Template</title>
            <meta charset="UTF-8">
            <meta name="description" content=" Divisima | eCommerce Template">
            <meta name="keywords" content="divisima, eCommerce, creative, html">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">

36. UTF-8 
- A character in UTF8 can be from 1 to 4 bytes long. UTF-8 can represent any character in the Unicode standard. UTF-8 is backwards compatible with ASCII. UTF-8 is the preferred encoding for e-mail and web pages


