# thatopen-1.00
thatopenuniversity - Mater BIM Software Developer -  Creating static websites

## 1. Welcome and summary


## 2. Structuring and styling a projects page

### 2.1. Understanding the markup syntax and html
+ Markup: Markup syntax is a set of rules used to format and structure plain text by using tags, which are enclosed in angle brackets ("<" and ">"). Tags can be opening, closing, or self-closing.

+ Tags and Attributes: Tags can have attributes within the opening tag, written in pascal or camel case, with values in quotation marks. Attributes provide additional information about the element.

+ Hierarchical Structure: Markup syntax often involves a hierarchical structure. Tags can have parent-child relationships, defining how content is structured. This hierarchy is crucial.

+ Markup Language: Extending the rules of markup syntax creates a markup language. HTML (HyperText Markup Language) is one such markup language used to define the elements of a webpage and their relationships.

+ HTML Structure: HTML documents start with a root html tag, containing two child tags: <head> for metadata and <body> for visible content. The <body> section holds elements like buttons, windows, and inputs, structuring how they appear on the page.

+ Document Object Model (DOM): Browsers read HTML files and create an element hierarchy known as the Document Object Model (DOM). It's used for dynamic interactions through JavaScript.

+ Additional Resources: To learn more about HTML and its elements, you can refer to the [Mozilla Developer Network (MDN) documentation](https://developer.mozilla.org/en-US/docs/Web/HTML) for comprehensive information.

### 2.2. Webpage composition

+ Webpage Components: Websites are not composed solely of HTML files. They consist of three key technologies: HTML, CSS, and JavaScript.

+ HTML: HTML (HyperText Markup Language) was discussed more in-depth in a previous lesson. It is responsible for structuring the content of web pages.

+ CSS (Cascading Style Sheets): CSS is responsible for the appearance of web pages. It styles HTML elements, specifying colors, fonts, layout, and positioning, making the webpage visually appealing and consistent.

+ JavaScript: JavaScript adds interactivity and dynamic behavior to web pages. It allows for features like interactive forms, image sliders, and real-time updates. JavaScript runs in the browser and can manipulate HTML and CSS on the fly.

+ Hosting and URLs: Websites' files are located on online servers known as hosting. Each website has a unique address called a URL (Uniform Resource Locator). When you enter a URL in your browser, it requests the website's files from the internet, and they are displayed in your browser.

+ How Websites Work: An overview of how websites work, involving DNS servers, IP addresses, server response, and browser rendering.

+ IDEs for Web Development: HTML, CSS, and JavaScript files are text files, and you can use any text editor to create them. However, Integrated Development Environments (IDEs) are specialized tools for web development. Visual Studio Code (VSCode) is one of the most popular IDEs for web development, developed by Microsoft.

### 2.3. How to use the files from the master

+ How to use the files from the master: Explains the process of accessing and utilizing the lesson files from the master in the VSCode environment. The user is directed to download a compressed file available in the lesson description, decompress it, and find a folder containing all the files for the almost 100 videos in the master.

+ Installing Git: Informs the user about the need to install Git, a version control technology, for effective usage of the lesson files. Guides the user to a specific page to download Git based on their operating system.

+ Git Installation Process: Briefly describes the Git installation process, emphasizing selecting VSCode when prompted. Encourages the user to restart VSCode after installation.

+ Opening Multiple Instances of VSCode: Recommends having two instances of VSCode running simultaneously—one for the project being developed and another for the master files. Guides the user to open a new window in VSCode and drag the decompressed folder into it.

+ Navigating Master Files: Instructs the user on how to navigate and switch between master files in VSCode. Explains the dropdown menu showing options like 'master' and identifiers starting with M, C, and L, representing module, chapter, and lesson. Demonstrates how to use this system to access the final files for a specific lesson, module, or chapter.

### 2.4. Structuring the main page

+ Creating a Folder and HTML File: Start by creating an empty folder for your project files. In this case, it's named "that-open-master." Then, create a new HTML file and name it index.html.

+ HTML Snippets: Integrated Development Environments like VSCode often provide code snippets for common structures. For example, typing html:5 and hitting enter generates the basic structure of an HTML file.

+ Containers in Web Design: Web design often involves thinking in terms of containers or rectangles. In HTML, the `<div> `tag is commonly used to represent containers. You create these containers to structure the page.

+ Unique Identifiers (id): To distinguish between HTML elements and reference them in CSS and JavaScript, you can assign unique identifiers using the id attribute. For example, you gave the `<div>` tags the ids of "sidebar" and "content."

+ Tags for Specific Elements: While `<div>` is a generic container, HTML provides specific tags for certain elements. For instance, you can use `<aside>` for the sidebar, `<ul>` (unordered list) for the navigation buttons container, and `<li>` (list item) for individual buttons. Use tags like `<main>` and `<header>` for more specific purposes. When no specific tag fits, you can still use `<div>`.

#### Lesson exercises:
+ Look at thhe project card and try to create its structure in html
+ Search web designs and try to create their basic html structure

### 2.5. Getting started with CSS pt1

+ Introduction to CSS: CSS (Cascading Style Sheets) is used to define the display behavior and style of elements in an HTML document, including properties like colors, fonts, container directions, and more.

vImportance of HTML and CSS Pairing: HTML documents can exist without CSS, but when combined, they create a powerful set of tools to create and style webpages.

+ Separation of HTML and CSS: CSS is written in its own file, commonly named style.css, separate from the HTML file. This separation allows for better organization and easier maintenance.

+ CSS Selectors: CSS selectors are used to target specific HTML elements for styling. One common way to do this is by using the ID of the HTML element, denoted with a hash symbol (#).

+ Linking HTML and CSS: To link an HTML file with its corresponding CSS file, a link tag is placed in the HTML file's <head>. The rel attribute is set to "stylesheet," and the href attribute specifies the path to the CSS file. This allows the browser to apply the styles defined in the CSS to the HTML elements.

+ Creating Content: Content in HTML is defined between the opening and closing tags of an element. In the lesson, you added content to the HTML file, such as a navigation button labeled "Project" and used the <h2> tag for titles.

### 2.6. Getting started with CSS pt2

+ Getting started with CSS. Part II: Continuing from the previous lesson where CSS was introduced and linked to the HTML, this video proceeds with practical styling.

+ Changing Sidebar Background Color: The first CSS rule is applied to alter the sidebar's background color. CSS rules follow a syntax where the rule's name, value, and a semi-colon to end the rule are defined. For reference, the MDN documentation on CSS rules is introduced.

+ Hex Code for Colors: The hex code is introduced as the standard method for representing colors in CSS. A suggestion is made to use websites like HTML Color Codes to pick colors from a palette and copy their hex codes.

+ Adjusting Content Element Background Color: Similar to the sidebar, the background color of the content element is adjusted using a hex code obtained from a color palette.

+ Layout Modification with CSS Grid: The default vertical flow of HTML elements is discussed, and the need to modify this behavior using CSS rules is highlighted. The introduction of CSS Grid is explained as a common and modern method to define layouts.

+ Applying Grid Layout to Body: A selector for the body tag is introduced to target all instances of the body in the document. A set of CSS rules is provided to transform the body into a grid layout with two columns and one row.

+ Grid Template Columns and Areas: The grid-template-columns rule is used to define the widths of the columns. The grid-template-areas rule assigns names to each cell in the grid layout, specifically naming them sidebar and content. Additionally, the height property is set to 100% of the viewport height, and the background color of the entire page is adjusted.

+ Viewing Changes and Default Styles with Developer Tools: The browser's developer tools are introduced by pressing F12. Using the Elements tab, developers can inspect the DOM and see the styles applied to selected elements. The default styles provided by the browser are visible, and it's demonstrated how to override them, such as removing the default margin on the body element.

+ Deleting Unwanted Content Section Rule: The lesson concludes with removing the background color rule for the content section, indicating that its background color will be defined by the body tag. Additionally, the unexpected margins observed in the page are addressed by setting the body's margin to 0 in the CSS file.

### 2.7. Working on the sidebar

+ Working on the sidebar: In this lesson, the focus shifts to refining the sidebar's appearance. The video starts with loading the company logo inside the previously created image tag. An SVG file is stored in an assets folder, and the relative path is added to the src attribute. The alt attribute is also set to display the company name if the image fails to load.

+ Adjusting Logo Size with CSS: To manage the logo's size, the image tag is given an id of company-logo. In the CSS file, the height of this image is set to 65px to ensure it fits well within the sidebar.

+ Styling Navigation Buttons Container: The focus then shifts to styling the navigation buttons container, represented by the ul element with the id nav-buttons. Default margin and padding for ul elements are set to 0 to create a cleaner layout. The styling rules for the li elements within this container include removing the default list-style, setting padding, border-radius, font size, cursor type, and background color.

+ Integrating Google Fonts: The video introduces changing the default browser font by integrating one from Google Fonts. The font "Inter" is chosen, and the necessary import lines are added at the beginning of the CSS file. The global selector * is then used to apply this font to all elements in the HTML file.

+ Using Developer Tools for Live Editing: A demonstration is provided on how to use the browser's developer tools for live editing. This allows for immediate visual feedback when making changes to the CSS. The importance of spacing between design elements is discussed, and the live editor is used to add padding to the sidebar.

+ Centering Elements with Flexbox: The challenge of centering elements using CSS is addressed using flexbox. By setting the display property to flex for the sidebar, the default direction is along the X-axis. Changing the flex-direction to column ensures a vertical layout. The row-gap property is used to specify the distance between children elements in the container.

+ Applying Changes from Developer Tools to CSS File: The video concludes by emphasizing that the changes made using the live editor in the developer tools are not permanent. However, these changes can be copied from the inspector and pasted into the CSS file to ensure persistence after reloading the page.

Lesson practice:
+ Add a second button with a margin/pading from the first button.

### 2.8. Working on the header

+ Working on the header: To address the exercise from the last lesson, there are various solutions, one being to define a top margin for the buttons. However, a preferred option involves setting the display of the nav-buttons container to flex, adjusting the flex-direction to column, and incorporating a row-gap for better spacing.

+ Header Structure: While structuring the page, a container for the action buttons on the right side of the header is created. Inside this container, a button labeled New Project is added.

+ Styling with Developer Tools: Similar to styling the sidebar, the developer tools are used to experiment with the element.style. The header is given a padding of 30px in the Y direction and 40px in the X direction. Setting the display to flex facilitates horizontal alignment.

+ Flexbox for Alignment: To separate the title and action buttons and align them accordingly, flexbox is employed. By setting align-items to center and justify-content to space-between, the desired result is achieved. This rule is then copied and pasted into the CSS file.

+ Structuring CSS with Comments: To prevent CSS files from becoming messy, styles are grouped by sections. Comments are added to denote specific sections. Comments in CSS are opened with /* and closed with */.

+ Styling the Button: The button is styled with common rules, including border-radius to round the corners and border: none to remove the default button border. The main app color (blue) is now utilized more, leading to a discussion about the DRY principle (Don't Repeat Yourself) and the introduction of CSS variables.

+ Introduction to CSS Variables: CSS variables are introduced by defining them in the root selector (root element in the HTML document). The syntax involves two hyphens, followed by the variable name, a colon, the value, and a semicolon. These variables can then be used throughout the CSS file, providing a centralized way to control colors and other properties.

+ Utilizing CSS Variables: The created CSS variables are used to replace the color values used in various rules. Changing the value of the variables at the root selector dynamically updates the associated colors across the entire stylesheet.

+ User Interaction Styling: Pseudo-classes in CSS, such as :hover, are introduced. Navigation buttons, represented as li elements, are styled to be blue only when users hover over them.

+ Introduction to Icons: The use of icons is explained to enhance the visual appeal of buttons. Google Icons, similar to the previously used font, are introduced. An external stylesheet resource is added to the HTML file to access material icons. An example icon is added before the name of the navigation button, providing an easy way to incorporate icons into the page.

```
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons+Round">
```

Lesson practice:
+ Create and use variable font sizes (small, medium and large, using css variables)
+ Change the new button background color to lighter when in being hovered
+ Set some spacing between the icon and the button name
+ Use more icons in places you find them useful.

### 2.9. Structuring and styling a project card

+ Objective and Reminder: The goal is to structure and style a project card. It's emphasized that the learner should recall the previously covered concepts, and detailed explanations won't be repeated for concepts covered earlier in the module.

+ Structuring the Card: The base design involves a card, a card header, and card content. While the card itself is represented by a div, the card header and content are also represented by div elements. The card header contains elements for project initials and a container for the name and description, using appropriate HTML tags.

+ Containers for Information: The card content is designed with a container for each piece of project information, addressing potential alignment issues. Each container includes a div for both information name and value, duplicated to match the four containers in the design.

+ Referencing Elements for Styling: The challenge of styling multiple project cards is discussed. While an ID could be used, it's explained that classes are more suitable for elements repeated several times in the design. Classes, in this case, are suggested for styling.

+ Styling with Classes: Three classes are proposed for styling: card-header, card-content, and card-property. The use of dot . is explained as the selector for targeting elements by their class in CSS.

+ Applying Styles: CSS rules are demonstrated for styling the project-card, including a hover effect. The card-header, card-content, and card-property classes are styled with typical CSS properties.

+ Additional Styling: The need for a background color in the project initials and gray text color for property names is identified. Inline styling is introduced as a solution, allowing CSS rules to be applied directly in the HTML using the style attribute.

+ Font Size Adjustment: Font size adjustments are made using variables and h tags styles. Font-size variables are created, and h tags are styled accordingly. The importance of naming conventions for variables is mentioned.

Lesson exercise:
+ Implement a grid layout for multiple cards

### 2.10. Making the projects page responsive

+ Making the projects page responsive: In this lesson, the focus is on addressing the exercise related to the grid system composed of project cards on the projects page.

+ Grid System Adjustment: The speaker acknowledges the previous solution for the grid system repetition (1fr four times) and highlights the need for further explanation. The use of the CSS repeat() function is introduced, which repeats a given CSS value a specified number of times. The goal is to make the grid system more dynamic and responsive to different screen sizes.

+ Understanding CSS Value Functions: A brief explanation of CSS value functions is provided. Functions in CSS, like in programming languages, take arguments within parentheses. The repeat() function is specifically introduced and explained, with the first argument indicating how many times to repeat the second argument.

+ Responsive Grid Columns: The need for a more flexible approach to column creation based on screen size is emphasized. The solution involves replacing the fixed repetition with auto-fill and minmax() functions in the repeat() statement.

	+ auto-fill dynamically creates as many grid columns as possible while respecting size constraints.

	+ minmax() sets the size of each item with two arguments:

		+ 350px: the minimum size each item should have.

		+ 1fr: the flexible sizing unit that distributes available space equally among items.

+ Summary of Responsive Approach: The revised repeat() statement creates a grid layout where columns are at least 350 pixels wide but can grow and fill any additional available space equally. This approach ensures responsiveness as the project cards adjust to changes in page size.

### 2.11. Creating the new project fform

+ Creating the new project form: The design introduces a modal for the form, where the modal container (dialog element) is set within the main tag with the id of new-project-modal. Modals are windows that overlay everything, and the modal container is the black-blurred background beneath the form.

+ Form Structure: The form structure is outlined, with various containers:

	+ The form itself, represented by the form tag.

	+ The form title, an element within the form.

	+ The inputs list, another container within the form.

	+ 	Action buttons, belonging to the same container.

	+ Each label + input field pair has its own container.

+ HTML Representation: The HTML representation of the form structure is briefly presented.

+ Styling the Form: CSS styles are applied to the form, form title, input list, and form field container. Notable points include the use of margin: auto for centering and styling the backdrop of the dialog element.

+ Showcasing in the Browser: It's noted that the dialog element is hidden by default. To reveal the form, a line of JavaScript code is introduced, and users are instructed to execute it in the console tab of the developer tools.

+ Styling Inputs: HTML tags like label, input, textarea, select, and option are used to structure the input elements. Attributes like for and type are discussed. Not all inputs use the input tag; textarea and select are employed for the project description and dropdowns, respectively.

+ Placeholder Attribute: The placeholder attribute in input tags is mentioned, providing text before the user starts typing.

+ Styling Input Elements: CSS styles for input, textarea, and select elements, along with their focused states, are presented. Commas are used to separate different selectors targeting elements with the same rules.

+ Final Form Presentation: With the execution of the code in the console, the almost completed form is showcased in the browser.

## 3. Structurinng and styling a details page

### 3.1. Structuring the project details page

### 3.2. Creating and styling the details card and to-do list

### 3.3. Commmon VSCode Shortcuts

+ CTRL + F // CMD + F	for Search: By pressing CTRL + F, the search field in VSCode is activated. This allows for efficient searching within the document. For instance, typing 'button' and pressing Enter enables cycling through all matches.

+ CTRL + D // CMD + D	for Multiselection: Selecting a word and then pressing CTRL + D in VSCode adds the next similar word to the selection. This shortcut is particularly useful for making simultaneous changes to multiple occurrences.

+ Creating Comments Shortcut: In the process of writing comments, a shortcut in VSCode lets you create a comment without memorizing the syntax. It involves pressing CTRL and the key used in your keyboard to close a curly bracket.

+ Writing at Multiple Cursor Locations: A handy shortcut enables writing simultaneously at different cursor locations. By setting the cursor at one location and holding ALT while clicking at other places, you can copy text to all selected locations. Pressing Escape ends the process.

+ Quickly Copying Lines: The video introduces a shortcut for quickly copying lines in VSCode. By selecting a block of code and pressing SHIFT + ALT along with either up or down arrow keys, you can create a copy. Repeating the key combination produces multiple copies.

## 4. Static websites modul exercise

### 4.1. Challenge

