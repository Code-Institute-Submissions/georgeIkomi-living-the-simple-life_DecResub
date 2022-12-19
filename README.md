
# Living The Simple Life

## Description

The world we live in today can often bring unexpected challenges in that life can get complicated
very quickly. This can bring unhappiness, and in some cases stress, in people's lives.

Living the Simple Life is a blog website that offers people insights into ways to mitigate these
challenges by exploring approaches that can be adopted to find simplicity in the life they're
already living today.

The site is targeted towards those who are experiencing difficulties or unhappiness in their
lives in general, and will be useful to them in that they will become informed about the
subtle they can make in their lives to live a more fulfilled and happier life.


![](/assets/images/hero-image-for-home-screen.png)

![](/assets/images/recen-posts-section-image.png)

![](/assets/images/testimonial-section-image.png)

![](/assets/images/about_and_call-to-action-image.png)
# Features

## Existing Features

* Navigation bar

  - This feature will forster an easy way for the user to navigate the site and improve   
    the user experience.

![](/assets/images/navigation_scrn-shot.png)

* Toggle menu

  - This funtionality provides a way for the user to view the navigation links in an 
    organised fashion on smaller screen devices.

  - The user is able to expand and close the menu for navigation on small screen devices
    should they need to do so.

![](/assets/images/hamburger-menu1_scrn-shot.png) ![](/assets/images/hamburger-menu2_scrn-shot.png)



* Header section

  - This feature provides the user with viewing consistency as they explore the site.

![](/assets/images/hero-image1_scrn-shot.png) 

![](/assets/images/hero-image2_scrn-shot.png)



* Recent posts section

  - This section of the site provides the user with posts from the member community with ideas on how 
    to keep up with changing trends.

![](/assets/images/recent-posts1_scrn-shot.png)

![](/assets/images/recent-posts2_scrn-shot.png)  ![](/assets/images/recent-posts3_scrn-shot.png)

* About me section

  - This section gives a very brief introduction about the creator of the "Live a simple life" ideology
    and how he turned things around in his personal life with this idea.

![](/assets/images/about-me1_scrn-shot.png)

![](/assets/images/about-me2_scrn-shot.png)   ![](/assets/images/about-me3.png)

* Footer section

  - This section includes a number of social media platforms through which the creator can be 
    contacted or communicated with. 

![](/assets/images/footer1_scrn-shot.png)  

![](/assets/images/footer2_scrn-shot.png)

* Newsletter section

  - This section provides the user with the opportunity to subscribe to the newsletter, where they can 
    get involved and see what other members are saying, and keep up with issues and trends.

![](/assets/images/newsletter1_scrn-shot.png)

![](/assets/images/newsletter2_scrn-shot.png)
                      
## Technologies Used

### Languages Used

* HTML5
* CSS3

### Frameworks, Libraries & Programs Used

1. Google Fonts
      - Google fonts were used to import the 'Lora' and 'Ubuntu' fonts into the style.css
        file which is used on all pages throughout the project.  

2. Git
      - Git was used for version control by utilizing the Gitpod terminal to commit to Git
        and Push to GitHub.

3. GitHub
      - GitHub is used to store the project's code after being pushed from Git.

4. Flexbox
      - The use of Flexbox made it easier to design a flexible responsive layout structure
        without using float or positioning.

# Testing

  * Initial testing involed making sure the html file runs as expected. Some text was added to the 
    standard boilerplate HTML, saved, and run in the browser (using VScode "GoLive" extension) to see the result. The outcome of the preview was a display of the text added in the HTML file on the screen. Confirming it works.

  * In order to verify the connection between the HTML and stylesheet, a css style rule was added to 
    the style.css file to test that it functions as expected. A rule to change the background color of the html body element was added. The outcome was as expeceted (background color of the added element changing to the color specified) confirming the functioning of the stylesheet (style.css file).

  * In planning the testing, a section by section aproach was adopted in developing the site. For each 
    section, the features were developed and tested before moving to the next section. As each section is developed, each feature is implemented, saved and run.

    The preview is then inspected/reviewd in the browser. Chrome Developer Tools is then used to make required changes as a result of errors in the design, display, or functionality  of the feature, and to test and preview these changes on the live site.

    When inspecting/reviewing is done and we're happy with the changes, the code change is then copied from Chrome Developer Tools and inserted in the corresponding part of the code on the system actually being used to develop the site. The changes are saved and the program is run again for that final verification and confirmation that the feature looks and feels like what was intended.

  * Functional testing was also carried out as unit testing was being done above. The functional 
    testing was done to verify that any changes made as part of the process of adding new features or functionality hasn't caused any break in the overall code and functionality of other features or changes implemented prior. This part of the testing process was also done on a section by section and feature by feature basis.

  * During testing, there were two main issues identified. Both in relation to the display of the site 
    when responsive. The logo was breaking up into the second line on some small screen sizes (see below).

![](/assets/images/logo-break1-scrn_shot.png)   ![](/assets/images/logo-break2-scrn_shot.png)

  * This was addressed by adding a media query reducing the size of the logo on these screens. As 
    indicated in the second diagram above, the issue was resolved.

  * The second issue was in connection with the navigation links breaking into the second line on some 
    small screen sizes, particularly on the Ipad, Ipad Pro, Ipad Mini, and Ipad Air screen sizes (see below).

![](/assets/images/nav-links-break1_scrn-shot.png)   ![](/assets/images/nav-links-break2_scrn-shot.png) 

  * This was addressed by adjusting the max-width for all media queiries such that it causes the hamburger menu feature to kick in, and the navigation links are hiden rather than breaking into the second line as indicated in the second screenshot above.

## Validator Testing

* HTML
    - No errors/warning were returned when passing all 4 html files through the official [W3C 
      validator](https://validator.w3.org/).        
           
* CSS
    - No errors/warnings were returned when passing the style.css file through the official [(Jigsaw)validator](https://jigsaw.w3.org/css-validator/).
       
## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the folowing steps...

  1. In the Github repository, locate and click the "Settings" button on the menu at the 
     top of the Repository (not top of the page).

  2. Looking at the menu on the left (under the "Code & automation section), scroll down
     until you locate "Pages" then click on it.

  3. Under "Build and deployment", select "Deploy from a branch" from the drop-down menu
     in the "Source" sub-section, and select "main" from the drop-down menu in the "Branch"
     sub-section.

  4. Click on the "Save" button. Once this is done, the page will be automatically refreshed
     with a detailed ribbon display at the top of the page to indicate the successful deployment.

The live link can be found here - <https://georgeikomi.github.io/living-the-simple-life/>

# Credits

  * Instructions on how to implement the use of Flexbox in structuring layout was taken from
    [MDN-documentation(Flexbox)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

  * Instructions on how to implement form validation on the Newsletter page was taken from
    [Specific-Scrimba-Tutorial](https://scrimba.com/learn/responsive/the-basics-of-styling-form-cN3Z7EfZ)

  * Instructions on how to implement the use box-shadow css property was taken from
    [MDN-documentation(box-shadow)](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow)

  * Instructions on how to implement toggle bar menu was taken from HTML & CSS (design and build 
    websites) Chapter 10: Introducing CSS, pg226-251, by John Duckett.

  * Further Instructions on how to handle the process and design was taken from HTML & CSS (design and build websites) Chapter 18: Process & design, pg452-471, by John Duckett. 





