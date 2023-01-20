Project brief: "Create a personal website using HTML and CSS"
Project scope: Introductory homepage + minimum 3 other pages, complete with CSS styling

Main objectives:
1. Meet the above requirements while ensuring consistent navigation structure, coherent design, and good accessibility (including alt-text for images)
2. Adhere to best-practices for HTML (including semantic markup), CSS (external stylesheet rules only, well-factored rules), and ensure design is responsive

Secondary objectives:
1. Include a user input form
2. Make good use of a variety of appropriate HTML elements
3. Make good use of Bootstrap components 

Content and functionality:
I chose to create a website detailing my interest in computing history, retro-gaming, and system emulation.
Each of these areas is given its own page, and thus with the inclusion of the home page, the site meets the main requirement.

A mix of custom styles and Bootstrap components is used. In the case of the latter, additional classes are sometimes employed to customise the styling.

A simple [ title -> navbar -> 3 column -> footer ] layout is used on all the main pages, where the 'left' column contains links to the site-sections and the 'right' column contains links to external resources relevant to the topic of the current page. In order to have the main content right after the navbar on mobile devices where the columns switch to vertical stacking, the site-sections column is hidden on viewport widths smaller than the mobile breakpoint. Site sections can then still be accessed via the hamburger drop-down menu.

A simple contact form page is also included, although it currently takes the user to a dummy confirmation page, as there is no server to submit the request to.