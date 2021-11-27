# Yoga Lovers

Yoga lovers is a website for people who are interested in learning yoga techniques. The website's goal is to build a community of yogis from home through yoga techniques lessons. Yoga Lovers website will be useful for people who are beginners and as well as those who are already is a little bit familiar with yoga. 

The user of this website will be able to find all the information they need to know about the different yoga courses, contact information, and a signup form. Through online registration, users can access online classes and various courses. This website is targeted towards people who want to learn yoga at home.

![Responsive page](/assets/images/readme/responsive.jpg)

# Features

- ### Navigation Bar
  - Featured at the top of the page on all three pages. The navigation bar includes links to the Logo, Home page, Courses, and Sign Up page.
  - The navigation makes the different pages of the website easy to find. It is fully responsive and identical on each page to allow for easy navigation without having to revert to the previous page.

- ### The Header
  - The header shows the logo, the name of the website, and navigation. The logo color is a combination of light and dark purple, which symbolizes peace and wisdom in Hinduism which yoga belongs. The user encounters this color spectrum throughout the website.
  - The header is sticky and sticks to the top of the page when the user starts scrolling. This allows the user to always access the navigation bar.

![Navigation bar](/assets/images/readme/nav.jpg)

- ### The landing page image
  - The landing includes an image with text overlay and a button to allow the user to see exactly what the website is about, yoga courses.
  - This section grabs user attention with an eye-catching animation by zoom effect. With the help of the Visit us button, the user can be linked directly to the courses page for more information. 

![The landing page image on the home page](/assets/images/readme/banner.jpg)

- ### The Courses Section
  - The Courses section shows the user which courses the website offers their members. This section is divided into three sections, which each section represents a specific course.

![The Courses section](/assets/images/readme/courses-section.jpg)

  - In this section by hovering over any of the images, the names of the courses appear on it. This allows the user by clicking on the desired course can be linked to the courses page where there is more information about the courses.

![The Meditation part on the Courses section](/assets/images/readme/courses-section-meditation.jpg)

- ### The Testimonial Section
  - The Testimonial section introduces two customers who are sharing their positive experiences with the user. This section helps to gain the user's trust in the way that the user feels that she/he is not the first person who wants to register for these courses and also what are the benefits of these courses.

![The Testimonial Section](/assets/images/readme/testimonial-readme.jpg)

- ### The Flexible Section
  - The Flexible Section includes an image with text overlay and a button to give the user a little more information about yoga.
  - In this section by fixing the background image is created this effect that the photo is flexible and mobile. This is what helps to better understand the cover text.
  - This section allows the user to be linked to the Sign Up page for registering for starting courses by clicking on the Let's start button.
  
![The Flexible Section](/assets/images/readme/flexible.jpg)

- ### The Footer
  - The footer section includes the contact phone number, links to the relevant social media sites for Yoga Lovers, and e-mail address. 
  - The social media links will open to a new tab to allow easy navigation for the user and the encourages user to keep connected via social media.

![The Footer](/assets/images/readme/footer.jpg)

- ### The courses Page
  - This page has the same layout as the home page with the same header and same footer. A new photo has been used for the banner image which shows that this is a new page. The cover text is also changed to the Courses title.

  ![The Courses page header](/assets/images/readme/banner-courses-page.jpg)

  - The main section in the Courses page is divided into three sections, each section represents a specific course and is covered by the name of the course.

  ![The Beginners part on the Main section, on the Courses page](/assets/images/readme/main-section-begginers.jpg)
  ![The Meditation part on the Main section, on the Courses page](/assets/images/readme/main-section-meditation.jpg)
  ![The Pregnancy part on the Main section, on the Courses page](/assets/images/readme/main-section-pregnancy.jpg)

  - In this section by hovering over any of the images appears more information about the courses.

  ![The Main section hover](/assets/images/readme/main-section-hover.jpg)

- ### The Sign Up Page
  - This page will allow the user to get signed up to Yoga Lovers to start their courses at home. The user can choose the course that they are interested such as yoga, meditation, or pregnancy training. The user will be asked to submit their full name and email address.

  ![The Sign up page](/assets/images/readme/signup-readme.jpg)

# Testing

- This website has been tested in different browsers: Chrome, Firefox, and Safari.

- This website is responsive for different devices such as desktop pc, tablets, and mobile. It functions on all standard screen sizes using the Chrome Dev Tools device toolbar.

- Different parts of the website such as header, footer, courses section, testimonial section, flexible section, the main section on courses page, and sign up page all are easy to understand and readable.

### Bugs
#### Solved bugs
- When I deployed my project to GitHub Pages and I tried to test it by Chrome Dev Tools on the iPad dimension I discovered that the Sign Up page does not cover our entire frame and there is a blank white space at the bottom of the footer.
- I fixed the problem by changing the HTML code and style for the form section on the Sign Up page.

![Bugs html](/assets/images/readme/bug-html.jpg)
![Bugs css](/assets/images/readme/bug-css.jpg)

- To correct the Yoga Lovers website dictation errors, I checked the text of the website in Grammarly again.

- I changed the titles text on the Testimonial section because it was mistakenly copied from the titles text on the Courses section.

- To Improve the Lighthouse performance score on Chrome Dev Tools, I reduced the size of the photos by compressing images.

- To Improve the Lighthouse accessibility score on Chrome Dev Tools, I changed the button color on the Form section on The Sign Up page.

- To improve the user experience, I added the Let's start buttons under the cover text in all three parts of the main section on the Courses page.

- I added empty onclick event listener to fix iOS hover bug

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fanahita83radfar.github.io%2Fyoga-lovers%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fanahita83radfar.github.io%2Fyoga-lovers%2Fsignup.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)
- Accessibility

![Accessibility](/assets/images/readme/accessibility.jpg)
  
# Deployment
- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - https://anahita83radfar.github.io/yoga-lovers/

# Credits
### Content
- The font in the Yoga Lovers website were taken from Google Fonts [Google Fonts](https://fonts.google.com/)
- The icons in the footer and sign up form were taken from [Font Awesome](https://fontawesome.com/)
- The code to make zoom effect animation on the home page and courses page banner, and the code to make sign up form was taken from the CI [Love Running](https://github.com/Code-Institute-Solutions/love-running-2.0-sourcecode/tree/main/03-creating-the-hero-image/02-hero-image-animation) project.
- The code to appear the cover text on overlay images on the courses section on the Home page and the main section on the Courses page, and the Testimonial section was taken from [Specific YouTube Tutorial](https://www.youtube.com/watch?v=oYRda7UtuhA&list=PLjwm_8O3suyP5kGKmwS_DM0Hs1j7fshi5&index=1)

### Media
- The logo image on the navigation bar is from [Clipart Library](http://clipart-library.com/clip-art/yoga-transparent-background-10.htm)
- The photos used on the home page, the courses page, and the sign up page are from [Pexels](https://www.pexels.com/sv-se/sok/yoga/)
