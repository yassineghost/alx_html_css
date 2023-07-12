Flexbox Project
This is a simple project that demonstrates the use of flexbox to create a responsive layout. The project includes several tasks, each building upon the previous one to enhance the layout and styling of the web page.

Task 0: Add display flex
In this task, we introduce the use of display: flex to create a flex container. All direct children of the container become flex items, and margins no longer collapse as they would with block elements.

Task 1: Add new classes on sections
In this task, we add specific classes to the outermost section tags of different sections, such as services, works, about, latest news, testimonial, and contact. These classes will be used for further styling and customization.

Task 2: Reverse order Latest news cards
Here, we utilize the flex-direction property to reverse the order of the Latest news cards. By setting flex-direction: row-reverse for the row class inside the section-latest-news, the cards will appear in reverse order.

Task 3: Simplify services list
This task involves simplifying the services list by removing the second unordered list (ul) and placing all list items (li) under the first unordered list. Additionally, we set flex-wrap: wrap for the row class inside the section-services to ensure the items wrap to multiple lines if needed.

Task 4: Playing around with the spacing between flex service items
In this task, we adjust the spacing between flex service items. The width of the .col-1-3 class is updated to calc((100% / 3) - 2rem), and the width of the .col-1-2 class is updated to calc((100% / 2) - 2rem). Padding is removed from [class*='col-'], and a margin of 1rem is set instead. The margin of ul.row is also updated to -1rem.

Task 5: Flexify the header
Here, we make the header section more flexible by wrapping the logo and navbar menu with a container div. The container div is given the header-container class, and the necessary CSS properties (display: flex and justify-content: space-between) are applied to the container class. Rules related to header-logo and navbar-menu are removed.

Task 6: Flexify the navbar
In this task, we focus on flexifying the navbar. The display: flex property is added to the nav class selector, and the display declaration is removed from the .nav .nav-item selector. The margin declaration is moved to a new selector targeting .nav-item + .nav-item inside the nav class. The value of the nav-item-margin variable is also changed to 0 0 0 2rem.

Task 7: Align center logo and navbar
Finally, in this task, we align the logo and navbar vertically centered by setting align-items: center for the header-container class selector.

Please refer to the respective task files in the GitHub repository for the HTML and CSS changes made in each task.

Repository: alx_html_css
Directory: flexbox
Files:

Task 0: 0-index.html, 0-styles.css
Task 1: 1-index.html, 1-styles.css
Task 2: 2-index.html, 2-styles.css
Task 3: 3-index.html, 3-styles.css
Task 4: 4-index.html, 4-styles.css
Task 5: 5-index.html, 5-styles.css
Task 6: 6-index.html, 6-styles.css
Task 7: 7-index.html, 7-styles.css
