# Way of the Warrior
 Way of the Warrior is a website dedicated to sharing information about the art of Kung Fu. 
 The site is targeting everyone who is seeking to improve their health, body, and mindfulness through the practice of a martial art.
 Way of the Warrior serves as a valuable resource for individuals seeking their first insights into Kung Fu, its various styles, and the opportunity to participate in actual classes. 
 Users can easily access information about the training schedule, make informed decisions about attendance, explore pricing options, and effortlessly reach out to the school for additional details.
 ![Mockup](doc/index-mockup.jpg)

## Features 
This section describes the different parts of the Way of the Warrior site. 

### Existing Features

- __Navigation Bar__
    - The Navifation bar is featured on all pages, it includes links to the Home page (school), Training, Pricing and Contact page and is identical in each page to allow for easy navigation.
    - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.
    - The navigation bar highlights the active page, ensuring a intuitive user experience. 
    ![Navigation Bar](doc/navigation-bar.jpg)

- __Hero Image on all pages__
    - This section features an image that serves as an eye-catcher to capture the user's attention, accompanied by a meaningful headline that informs the user of their location on the page and what to expect on this page.
    - Each page features a different hero image, helping users in distinguishing their location within the site.
    - The graphic displayed below shows the hero image for the School / Index page.
    ![Hero Image](doc/hero-index.jpg)

- __Homepage: Introduction Section__
    - This section provides a general overview of the school and the content that users can expect to find on this site.
    ![Hero Image](doc/hero-index.jpg)

- __Homepage: What is Kung Fu Section__ 
    - This section the user receives information about what Kung Fu actually is because Kung Fu is more than just fighting. A coherent and well-structured presentation makes it easier for the user to gain an overview of this topic.
    - The user will see the value of practicing Kung Fu.
    ![What is Kung Fu?](doc/what-is-kung-fu-section.jpg)

- __Training Page: Kung Fu Styles__
    - In this section the user gets an general overview of the different Kung Fu styles he can learn at this school.
    ![Kung Fu Styles Introduction](doc/kung-fu-styles-introduction.jpg)

- __Training Page: Tabbed Style Section__ 
    - This section provides in-depth information for each individual style. 
    - The included videos support and help the user to gain a clearer understanding of the specific styles.
    ![Tabbed Style Section](doc/tabbed-style-section.jpg)

- __Training Page: The art of Kung Fu includes ...__
    - This section explains the various purposes of Kung Fu. This information is referenced in the training schedule below.
    ![The Art of Kung Fu](doc/the-art-of-kung-fu.jpg)

- __Training Page: Training Schedule__
    - This section displays the training schedule and provides information for the user about the timing of each class.
    - The colors used here indicate the type of training the user can expect when joining one of these classes.
    ![Training Schedule](doc/training-schedule.jpg)

- __Price Page: Pricing Cards__
    - This section displays the different price categories available to the user and what each of them offers. 
    - These categories are designed to cater to the various needs of the students, recognizing that everyone has different financial circumstances. The aim is to make the training accessible to a wide range of individuals.
    ![Pricing Cards](doc/price-cards.jpg)

- __Contact: Form__ 
    - This section offers a convenient way to contact the school.
    - Users have the opportunity to ask questions or request information about the school or the training.
    - After submitting the form, the user will be redirected to a Thank You Page.
    - This form includes 4 fields: 
        - Name: The full name of the user
        - Email: The email address of the user, where he can be contacted by the school
        - Subject: A topic for his request / question 
        - Message: The message
    - All of those fields are mandatory.
    ![Contact Form](doc/contact-form.jpg)

- __Thank You Page__
    - Provides feedback to the user that their message has been sent successfully to the school. 
    - This page can be accessed by sending a message via the contact form. 
    - This page is a static page, displaying a successfully send message every time.
    ![Thank You Page](doc/thank-you.jpg)

- __404 Page__
    - This page is designed to display a 404 error page to the user instead of an empty page when he enters an incorrect URL.
    - In the event of site refactoring or changed links, users will receive informative feedback instead of encountering a blank screen.
    ![404 Page](doc/404.jpg)

- __Footer__ 
    - The footer section includes contact information that allows the user to easily get in touch with the school, ensuring a seamless and convenient way to reach out for inquiries, assistance, or feedback.
    - The footer section includes links to the relevant social media sites. The links will open to a new tab to allow easy navigation for the user. The footer is valuable to the user as it encourages them to keep connected via social media.
    ![Footer](doc/footer.jpg)

- __Favicon__
    - This feature enhances brand recognition and user experience by providing a distinctive visual identity in browser tabs and bookmarks, making it easier for users to locate and return to the site.
    ![Favicon](doc/favicon.jpg)

### Future Features
The following features are not available in this release, but will be implemented in the future. 

   - __Contact form sending to an actual email__
        - Because this site needs to remain a static HTML website for the current state, I haven't implemented this feature yet. However, it is definitely planned for the future to ensure the proper usage of this contact form.

## Test
Before deploying this site, it's essential to thoroughly test it to ensure that everything is functioning as expected. 
Here are the steps to test this site:

### 1. Open in Local Browser
To start testing this site, open it in your local web browser. Ensure that all the pages load correctly, and the navigation is functional. 
Pay close attention to:
    - Links: Click all links and verify that they lead to the correct pages.
    - Images: Confirm that images are displayed correctly and load quickly.
    - Responsiveness: Check if the site is responsive and adapts to different screen sizes.

### 2. Cross-Browser Compatibility
Test this site in multiple web browsers to ensure it works consistently accross different platforms.
Commonly browsers to consider testing: Google Chrome, Mozilla Firefox, Safari, Microsoft Edge.

### 3. Mobile-Friendly Testing
With the increasing use of mobile devices, it's crucial to test your site's compatibility with various mobile devices and screen sizes. Test with browser developer tools and real mobile devices. 

### 4. Functionality Testing
Test all interactive elements on this site. 
This includes:
    - Contact Form
    - JavaScript for tabbed navigation within the training page
    - all links open in a new window and work as expected

### 5. SEO Testing
Test for search engine optimazation (SEO): 
    - Meta tags (title, description, keywords) are correctly set on each page.
    - Images have appropriate alt text.
    - The site's content is crawlable and indexable by search engines.

### 6. Accessibility Testing
Test on its accessibility for all users.
To access this site the user needs an active internet connection.
The colors match the contrast criteria, the font is readable and the font size is adapted to the size of the device.

### 7. Cross-Device Testing
Test on various devices, including desktops, laptops, tablets, and smartphones, to guarantee it displays and functions correctly on all of them.

### 8. Content Review
Test the content on its accuracy, spelling and grammar errors.

### 9. Validator Testing 
- HTML
  - No errors were returned when passing through the official W3C validator.
- CSS
  - No errors were found when passing through the official (Jigsaw) validator.


## Deployment
After this site has been tested successfully and it passed all those tests, it's time to deploy this site to a live server
or hosting environment. 
Here's a step-by-step guide on how to deploy this site:

### 1. Version Control (GitHub)
All files has been commited during the development process to GitHub.
    File Structure: 
        - HTML Files (all used pages)
        - assets/img (all used images for the site)
        - js-folder (needed javascript code for this site)

### 2. Deploy to Your Chosen Platform
Because we used GitHub, we will use the GitHub deployment process:

- GitHub Pages:
  1. Create a repository on GitHub if you haven't already.
  2. Push your static site files to your repository.
  3. Go to the repository's settings.
  4. Scroll down to the GitHub Pages section.
  5. Choose the branch you want to deploy (usually "main" or "master").
  6. Your site will be accessible at a URL like `https://pbrdys.github.io/way-of-the-warrior/`.


## Credits

### Media
- The social media icons used in the footer were take from https://icons8.com/icon/set/social-media/material