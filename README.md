# Menu Page
Coding assignment (module 2): https://jovanhuang.github.io/Menu-Page/module2-solution/

Coding assignment (module 3): https://jovanhuang.github.io/Menu-Page/module3-solution/

Coding assignment (module 4): https://jovanhuang.github.io/Menu-Page/module4-solution/ (use google chrome to open this then right click on the webpage. Select inspect and click on console to see the output.)

Coding assignment (module 5): https://jovanhuang.github.io/Menu-Page/module5-solution/ (every time you clicked on the "Specials" Menu, it will return a random menu)

Check out more details about the assignments' requirements above here: https://github.com/jhu-ep-coursera/fullstack-course4/tree/master/assignments

## Guidelines for Coding Assignment (module 2):
>You must implement the following breakpoints that will be considered desktop, tablet, and mobile. 
>
>1. The browser should display a desktop version of the site when the width of the browser window is 992px and above. 
>
>2. Tablet view should appear only if the width of the browser window is between 768px and 991px, inclusively. 
>
>3. Mobile view should appear only if the width of the browser is equal to or less than 767px.
>
>Your site is very simple. 
>
>* It consists of a page heading and 3 sections (all in one row in the desktop view). Each section contains some text. You can make it >dummy text/"lorem ipsum", it doesn't matter. 
>
>* How the sections are laid out on the screen depends on the width of the browser window. (**Hint: use media queries.**)
>
>* You are NOT allowed to use any CSS (or Javascript) framework for this assignment, including Twitter Bootstrap CSS Framework. No >framework CSS files should even be referenced in your index.html, even if you are not using them.
>
> **Layout:** 
>* In the desktop view (992px and above), each of the 3 sections should take up equal amount of space on the screen. As you make the ?>browser window wider or narrower, each section should become wider or narrower. (Hint: use percentages to define width and use the >'float' property.) 
>
>* In the tablet view (between 768px and 991px, inclusively), the first 2 sections should be in the first row and be of equal size. The >3rd section should be in the second row and take up the entire row by itself.
>
>* In the mobile view (equal to or less than 767px), each section should take up the entire row.
>
> **Section Title Region:**
>Each section should have a section title region that is always positioned at the top right corner of the section no matter the >view(desktop, tablet or mobile).
>
> **Spacing:**
>* Note the spacing between sections (both horizontal and vertical). 
>
>* Note the horizontal spacing between the edges of the section and the edges of the browser window. 
>
>* Also, note the spacing between the dummy text in each section and the edges of the section. Lastly, make sure the dummy text is >"pushed down" enough so it doesn't overlap the section title region.
>
> **Borders and Colors:**
>* Each section should have a background color set to some color (of your choosing). 
>
>* Set the background color of each section title region to some unique color (of your choosing). 
>
>* Make sure that the background color still allows the user to view the text in the section and section title regions.
>
>* Depending on the color you choose, you may want to change the color of the text so it can be easy to read. Set a black border on both >the section and section title region that is 1px thick. 
>
## Guidelines for Coding Assignment (module 3):
>**Navbar:** 
>Create a navbar that scrolls away together with the page (the navbar should become invisible and is not fixed to the top when you >scroll the page down). The navbar should have a company name (i.e., navbar-brand class) called "Food, LLC" that is aligned to the left >side of the navbar. (See https://getbootstrap.com/docs/3.3/components/#navbar. Make the browser window narrower to see the mobile menu >button appear in the first example shown at the provided link.)
>
>For desktop and tablet view, the navbar should not contain anything else. No other buttons should be visible. (Hint: use 'visible-xs' class.)
>
>**Navbar - Mobile View:**
>Create a simple menu button (3 horizontal bars). When the user clicks that button, a dropdown menu should appear (as illustrated in >Mobile Open Menu illustration below.) The dropdown menu should contain 3 items: Chicken, Beef, and Sushi.
>
>The dropdown menu should take up the entire width of the browser window. Make sure the dropdown menu has a background color set that >distinguishes it from the rest of the content.
>
>**Page Heading:**
>The page heading that says Our Menu should be centered within the browser window. You must use a Bootstrap class to accomplish this.
>
>**Create a single really tall section that will use the Bootstrap Grid and take up the entire width of the browser window (minus some >margins, of course) for all views:** 
>desktop, tablet, and mobile. To make the section really tall, you can either fill it out with a LOT of text or simply set its height to >something like 1000px. It needs to be tall enough to cause scrolling down to be required to view the bottom of the section. Make sure >its background color is set to distinguish it from the rest of the content. (Hint: don't forget to have an element with a >class='container' or class='container-fluid' wrapping your grid. Remember that to have the grid do something "always", i.e., no matter >what browser window size, use the col-xs-... classes. In this case, since we want the section to take up the entire row, use col-xs-12.)
## Guidelines for Coding Assignment (module 4):
> **Summary:**  
>In this assignment, you are going to loop over an array of names and print out either a hello or goodbye to that name to the browser >console. If the name starts with a letter j or J, you are to print out Goodbye JSomeName. If the name starts with any other letter, you >are to print out Hello SomeName.
>
## Guidelines for Coding Assignment (module 5):
> **Summary:**  
>In this assignment, we are going to have a bit of fun with our built restaurant web application. The front page of our web app contains 3 clickable tiles: Menu, Specials, and Map. If you click on the Specials tile, you will be taken to a single category page where all the menu items that belong to the Specials menu category will be shown. Your task in this assignment is to alter this behavior such that when the user clicks on the Specials tile, the web app takes the user to a random single category menu page, listing menu items in the category, be it "Lunch", "Dinner", "Sushi", etc. That way, any random category can become the Specials! What fun! (not! :-) )  
  
>Checking if it runs:  
1) Load the home page in the browser.  
2) Click on the Specials tile. A single page category with a list of menu items for some category should appear.  
3) Click on the restaurant logo to go back to the home page.  
4) Click on the Specials tile again. Most likely, a different single page category page will be shown.  

Repeat this several times to make sure that most of the time you see a different single category page.  
