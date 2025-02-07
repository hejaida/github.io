[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=12872728)
# Resume 💼🏢💻📄🗂📎🗄️🏦📠🖇🖨📱📧

You will utilize GitHub Pages to create a host your resume

## Part 1 - Instructions

You will have to create this project from scratch using plain HTML, JavaScript, and CSS.

This website will include:

* At least four pages that you can navigate to, consider index, about me, projects, socials, bio, demo real, portfolio, etc.
* Have at least two interactive JavaScript components that alter the view but are also accessible with a keyboard. Consider a button to switch between light and dark mode themes, a switch to change languages from English to Spanish, something to change the font sizes, go to high contrast mode, etc.
* Include a professionally written, styled, and presented resume. Visit with the career services people to have them look it over.
* Create your own favicon.
* Publish your website onto GitHub Pages.

You can utilize open-source CSS, but it must be cited and adapted to your needs.

Be sure that you have:

* Validated your HTML using [validator.w3.org](https://validator.w3.org/) to ensure no errors nor warnings.
* Verify that you are well documenting your code using [JSDoc](https://www.npmjs.com/package/jsdoc) standards. You do not need to generate an API.
* Ensured that you write satisfactory unit tests and that your code passes them, with **75%** coverage for non-view related tests.
* Include View Testing with puppeteer to ensure your website is updating as expected.
* Test your color contrast by visiting [a11y.com](https://color.a11y.com/).

**Optional**:

Purchase a domain name for your site and link it to your GitHub pages. I've used Google Domains, recently purchased by SquareSpace, with usually costs $1 for a domain name such as [www.oscarveliz.com](www.oscarveliz.com) and it is always a good idea to at least grab your name before someone else does. See [https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site) for more information on how to do this.

## Part 2 - Reflection

Add screenshots below showing,

* Your app running on GitHub Pages
  https://cs5610-seattle-fall23.github.io/resume-jerryyummy/
* Your html validation
* Your code coverage
* Your view testing
![Screenshot 2023-11-17 at 9.15.06 PM.png](image%2FScreenshot%202023-11-17%20at%209.15.06%20PM.png)
![Screenshot 2023-11-17 at 9.22.22 PM.png](image%2FScreenshot%202023-11-17%20at%209.22.22%20PM.png)
![Screenshot 2023-11-17 at 9.23.20 PM.png](image%2FScreenshot%202023-11-17%20at%209.23.20%20PM.png)
![Screenshot 2023-11-17 at 9.23.27 PM.png](image%2FScreenshot%202023-11-17%20at%209.23.27%20PM.png)
![Screenshot 2023-11-17 at 9.34.46 PM.png](image%2FScreenshot%202023-11-17%20at%209.34.46%20PM.png)
![Screenshot 2023-11-17 at 10.06.08 PM.png](image%2FScreenshot%202023-11-17%20at%2010.06.08%20PM.png)
Update the README to answer the following questions:

 1. Identify the interactive JavaScript elements of your website and explain how you implemented them.
1. Theme Toggle (Dark Mode/Light Mode)
   Function: changecolor
   Implementation:
   This function listens for a click event on an element with the ID themeToggle.
   When the button is clicked, it toggles the website's color theme between dark mode and light mode.
   It checks if the document.body contains the class dark-mode. If it does, the class is removed (switching to light mode), and the button text is updated to "Dark Mode". If it doesn't contain the class, the class dark-mode is added (switching to dark mode), and the button text is updated to "Light Mode".
   This implementation provides a user-friendly way to switch between themes, enhancing user experience, especially in different lighting conditions.
2. Font Size Adjustment
   Function: adjustFontSize
   Implementation:
   This function is designed to adjust the font size of the content within the element with the ID container.
   It takes a parameter change, which determines the amount by which the font size should be increased or decreased. Positive values increase the size, and negative values decrease it.
   The function calculates the current font size of the container element and adjusts it based on the change parameter. This allows for dynamic adjustment of text size, which can be useful for accessibility purposes.
3. Form Submission and Validation
   Function: contact
   Implementation:
   This function handles the submission of a form with the class needs-validation.
   It prevents the default form submission action to apply custom validation logic.
   The function checks the validity of the form. If the form is not valid, it adds a class was-validated for visual feedback and returns 0. If the form is valid, it logs the form data to the console (simulating a form submission) and would typically show a success alert (though this is commented out). It returns 1 to indicate a successful submission.
   This approach is useful for handling forms with custom validation requirements and providing immediate feedback to the user.
 2. What specific feedback did the career services people give you about your resume?
+ Formatting and Structure:

The resume is well-structured with clear sections: Education, Project Experiences, Research Experiences, Internship, and Qualifications. However, there could be more consistent spacing between sections for better readability.
+ Detailing in Project and Experience Sections:

The projects and experiences are well detailed, showing the technologies used and the role played in each project. This is good as it gives potential employers a clear idea of skills and experience.
For some project descriptions, like the "Take-out Reservation Application Development", quantifying the achievements (e.g., "got 30% less code") is excellent. It provides a tangible measure of the impact of the work.
+ Education Section:

The education section is clear and includes relevant coursework, which is helpful. However, it might be more impactful to highlight any outstanding achievements or GPA if it's particularly strong.
 3. What aspects of this project did you find particularly challenging and why? Explain how you overcame them.
how to use plain js to implement some functions other than react or node.js,cuz it will require me to write direct function. just follow the tutorial and debug over and over again
 4. Explain how you created a custom favicon for your page.
first, draw it or choose a photo on software and design the format. generate the image, link it on html
 5. Write a short essay about what you've learned in this class so far. Think about all the technologies we've used, the activities you've done, the programs you've made, and how far you've come. Describe your experiences in at least 20 sentences with specific examples from this course.
+ tech:js,html,css, jest, pug, react,express, nodejs, puppeteer, mongodb,google run
+ activities: team project , write unit test, write js function, use pug as template, link css and js on html, design the layout, xmlhttprequest, use api
+ programs:cycle，temperature, hello-email, express, simpledb, pickupapi, resume and so on
- we use html,css to design the page
- we use js to interact with page and create function
- we store data in mongodb, and require the data from it
- we use express to build the project
- we use react to generate the project
- we use google cloud to make authentication
- we use jest to write unit test
- we use puppeteer to test the view
- we use pug to replace html
- we use nodejs as the runtime platform
- we use xmlhttprequest to make a request and response
- we get data from certain api
- we create tag in js and render it
- we use form to submit a request
- we upload project on google cloud