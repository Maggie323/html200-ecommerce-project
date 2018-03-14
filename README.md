# Description

This is an assignment to build a responsive ecommerce web page. Nav and product container div will use flexbox. Sidebar/aside is a module that changes layout and location based on window size. Submitting the mailing list signup form results in user feedback on the page. Clicking a product's “add to cart” or “remove from cart” button updates cart count at top.

Students may use the provided mockups to guide their design to whatever extent they like. Matching the mockups is not required.

## Provided Materials

  - basic HTML and CSS
  - JSON list of products in script.js file
  - reset.css
  - images for all products
  - suggested design mockups

## Assignments

Lesson 03:

  - Make design decisions about how you'd like your site to look. You can use the provided mockups to guide your design to whatever extent you'd like- feel free to implement them exactly or make up your own design completely.
  - Code basic CSS for page. `reset.css` file should remain as it is. `main.css` file can be added to, changed, or completely redone.
  - `nav ul` and `.item-container` elements should be styled as flexbox containers. Implement a responsive grid system of your own design, or use a library, or don't use a grid at all. Be sure all important size values are proportional (em, rem, %).
  - We'll continue working on the CSS for this project throughout the course, in particular making it more responsive. The styling does not have to be perfect after this assignment. It's fine to change or add to the HTML as necessary for your styling.

Lesson 05:

  - Write a JS form handler function to be triggered on form submit. It should print to the console a friendly message that includes the value of the form element with name "email". Something like "Thanks for signing up for our mailing list, bobross@example.com!"

Lesson 06:

  - Serve appropriately sized images. Use GIMP or another photo-editing program to resize all images to more reasonable, consistent dimensions. This includes product images, the logo, and any background or other images you've included.

Lesson 07:

  - Write Javascript function that toggles the inclusion of a product in the "cart".
  - Add/edit HTML as necessary to trigger the function on click of a button for each product.

Lesson 08:

  - Write CSS that uses media queries to change layouts/style based on device size. There shoud be at least one obvious layout change in addition to elements fluidly changing width.
  - Finish styling the page.

Lesson 09:

  - Write Javascript that causes the total number of items in the cart to display next to the cart icon when that total changes.
  - Write Javascript that displays the friendly message on form submit in the page, not in the console.
  - Update the HTML and CSS as necessary to accomodate these changes.
  - Update the Testing section of this README with your own information.

*Extra Challenge*: Incorporate unit tests with [Qunit](https://qunitjs.com/).

*Extra Challenge*: Code a popup that toggles between hidden and displayed when user clicks on cart icon. It should show information about items in the cart (maybe list of their names, but up to you).

*Extra Challenge*: Serve appropriately sized images for user's device. Create multiple sizes of each image, and serve the appropriate one using the `srcset` and `sizes` attributes on the `img` tags. This will require naming all of the images consistently, e.g. "ombre-infinity400.jpg", "ombre-infinity200.jpg". [More](https://css-tricks.com/responsive-images-youre-just-changing-resolutions-use-srcset/) about [srcset](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)

*Extra Challenge*: Use browser storage to save details about a user's cart so when they revisit the page, it's in the same state as when they left it. [More about browser storage](https://www.w3schools.com/html/html5_webstorage.asp)

*Extra Challenge*: Dynamically generate the HTML for product listings from the JSON objects in script.js.

## Requirements

  - Site layout looks good on all sizes of devices. At a minimum, elements are proportionally styled and aside element changes location and layout at different screen sizes. This should be tested using a variety of devices and at least one online browser compatiblity testing tool.
  - Nav and product container elements are styled using flexbox.
  - Appropriately sized images are served.
  - User can add and remove items from their cart, which changes cart count number at top of page.
  - This README is updated to include information about the testing steps taken to ensure site quality.
  - Site is live on GH Pages hosting.

## Grading
Each weekly assignment will be graded independently. There will not be a final grade for the entire project.

## Testing
Audiences

WHO:

Ladies 
- Rating: HIGH 
- I found that 75% of women own a smartphone, so, mobile browsing while - viewing this site must be a pleasant experience for this user group. 
- http://www.pewinternet.org/fact-sheet/mobile/

People under 60 years of age 
- Rating: MEDIUM 
- I found that the vast majority of everyone under the age of 60 years own a mobile device.
	- Ages 18-29 94%
	- Ages 30-24 89%
	- Ages 50-64 73%
- http://www.pewinternet.org/fact-sheet/mobile/

Parents, students, working adults 
- Rating: HIGH 
- In my research I found that 9/10 American adults use the internet, my conclusion is that if my site isn't working properly, such as if a link is broken, it will have a huge impact on the number of visitor my page looses. 
- http://www.pewinternet.org/fact-sheet/internet-broadband/

Middle school education and above 
- Rating: MEDIUM 
- I saw there is a trend: those with a higher education tend to own more smartphones vs their counterparts.
- http://www.pewglobal.org/2016/02/22/smartphone-ownership-and-internet-usage-continues-to-climb-in-emerging-economies/

Online Shoppers 
- Rating: HIGH 
- My findings: More than 1 in 5 of the world's population shopped online in the past 30 days. 
- https://wearesocial.com/uk/special-reports/digital-in-2017-global-overview

HOW:

I think my user base is probably using PC devices to complete their order and have a fast internet connection. 
- Rating: HIGH 
- This site's functionality should be able to load fast enough, there's a huge population that relies on fast internet and will opt out of using my site if it takes too long to load. 
- My findings: 3/4 of American adults have broadband internet service at home. 
- http://www.pewinternet.org/fact-sheet/internet-broadband/

Users possibly use a hand-held device to browse the site and look at the pictures. 
- Rating: HIGH
- My findings: Reliance on smartphones for online access is mainly common for younger adults, non-whites and lower-income Americans.
- http://www.pewinternet.org/fact-sheet/mobile/

WHERE: 

Nationals are probably the ones viewing my site. I'm not planning on shipping world wide at this time. 
- Rating: HIGH 
- I'm expecting more of my users to be nationals, and according the the below source, "95% of Americans use a cellphone", therefore it's extremely important that this website works perfectly on a mobile device. 
- http://www.pewinternet.org/fact-sheet/mobile/

WHY:

- Users seek this site to be informed of new winter scarf trends 
	- Rating: MEDIUM 
- Visitors may visit my site to do research on scarf material?
	- Rating: LOW 
- Visitors are mainly here to shop for a scarf either for themselves or as a gift 
	- Rating: HIGH 
- Few may want to browse for pure entertainment 
	- Rating: LOW 

WHEN:

Page is proably seen after work between 5-11PM 
- Rating: HIGH 
Anytime during the weekend 
- Rating: HIGH


MY Quality Control: 
1)	I used the below link to view my website on different device screen sizes. 
For the most part I'm happy with the way that my page is rendered. But I did notice that the text on the headers are too big for some devices such as on a iPhone 6&7 Plus, therefore increasing the size of both my header and footer.
My favorite rendering was on a 22" Desktop with a 1680X1050 display.  
http://responsivedesignchecker.com/
2)	I also used:
https://developer.microsoft.com/en-us/microsoft-edge/
I was glad to see there were 0 Accessibility issues, but I did have others. 
I have 45 performance issues; a lot are with the size of my images. I like that this site provides what looks to be 'recommendations' 
i.e.: File "logo-scarfcat-400.png" can be 95.17kB (67%) smaller.
I didn't completely understand some of the 'recommendations' that this site posted, and I'm sure it's because my tech knowledge isn't advanced enough at this point to understand everything that was listed on this site
i.e.: Should be served with the 'Vary' header containing 'Accept-Encoding' value.
https://use.fontawesome … leases/v5.0.6/css/all.css:10:5
<!--  
<link href="https://use.fontawesome.com/releases/v5.0.6/css/all.css" rel="stylesheet">
-->
On reading how to fix one 'error' i realized that there is still A LOT for me to learn if I'm going to complete my own quality control for my products. I stumbled on this blog, which seems handy and thorough, but a lot of work for a newbie like myself:
https://www.fastly.com/blog/best-practices-using-vary-header


3)	Lastly, I used:
https://www.webpagetest.org/
I got an A in first byte time, keep-alive enabled, compress transfer, compress images, and effective use of CDN. 
I did however get an F rating for: Cache stating content. 
I did a google search on how to fix this issue and found a good blog with other great links with directions on how to fix this issue:
https://varvy.com/pagespeed/leverage-browser-caching.html
From my understanding, this basically means that the material on my site is not being 'remembered' by the server whenever a user pulls up my site, even if my site is loaded more than once, this may therefore delay the time it takes to load my page. In order to fix this, the instructions on the blog instruct me to add a '.htaccess' file and add a period of time for which I want my browser to remember the mentioned files. 

