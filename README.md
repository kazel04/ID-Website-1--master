# Psyche Info Website

The purpose of the website is to inform users about the purpose of the new social project, Psyche, as well as provide the means for users to send enquiries about the social project.

 
## Design Process
 
The website is catering to users who want to know more about the social project, most likely mental health professionals, journalists and youths.
These users would want to understand more about the project and learn about the vision and purpose of the project.

Hence, the website's content is designed to meet the needs and expectations of these different groups of users and displays the purpose of the social project through non-text means.

For example, smooth and futuristic animations such as circular particle movements and bright primary colours place emphasis on the future-oriented aspect of the project.
Meanwhile, the homepage utilises a mixture of two animations edited from open source designs in order to convey the image of candlelights among a bed of stars.
These designs have a subliminal message of hope, futurism and human warmth.

The key value that the website is providing to users is an interactive and non-conventional explanation on what the Psyche social project is through the use of aesthetic features and short summaries.
These short summaries are included in the mainpage section of the website which links to additional webpages which contain more detailed information about specific aspects of the project. 
These aspects include the vision, team, current work and contact information.

To facilitate requests for more information from users, the contact page also links out to a seperate form for users to send their enquiries to the project organisers.

A few user stories are included here:
- As a student interested in mental health, I want to look through the website to find out what the social project is working on, so that I can further understand what the social project is contributing to Singapore's mental healthcare system.
- As a journalist covering new technologies, I want to understand the new technologies that the project is developing so that I can understand the technologies used for mental healthcare today which would help with my reporting and articles.
- As a student who is looking into volunteering opportunities, I want to look through the website's vision page to understand whether the project's goals align with mine, and find out how I can contact the organisation for volunteering.

Wireframe for the project is in this repository as ID_S10222282_KohEnYang_Assg1_wireframe.


## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Interactive particle text - Allows users to interact with the particle animation and get an idea of our core technologies used as well as future-oriented work.
- Click-To-Scroll - Provides an unorthodox way for users to scroll through the sections of the mainpage, making the website more memorable
- Responsive Navigation Menu - Allows users to navigate around the website
- Short Summaries - Provides users with a simple summary of the different aspects of our work and an option to learn more
- Main Content Pages - Provides more information on the different areas of our work


In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Interactive Product Demonstrations once a beta version is complete
- Mailing list/update list option for people to keep updated with the progress of the project
- Interactive team page where the users can click on the images to learn more about each team member

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Particles.js](https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js)
    - The project uses **particles.js** to provide particle animations

- [Material+Icons](https://fonts.googleapis.com/icon?family=Material+Icons)
    - The project uses **Material+Icons** to assist with the particle animation creation


 - [Materialise CSS](https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js)
    - The project uses **Materialise CSS** as the UI component libary to aid in the design of the form page




## Testing

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Enquiry.html" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

2. Index Page:
    1. Go to the Index.html page
    2. Try to move the cursor over the animation and verify that the animation will be in motion
    3. Try to click on the webpage and check that the page will jump to the next section


3. Top navigation bar
    1. Click on each link in the navigation bar and ensures that they link to the correct page
    2. Ensure that the navigation bar appears for each main webpage
    3. Ensure that the navigation bar appears as a hamburger menu when the mobile view is used

4. Main Webpages
    1. Go to each of the main webpages
    2. Ensure that the animation is correctly formatted for mobile and web views
    3. Try to click on the webpage and check that the page will jump to the next section
    4. Ensure that the buttons link to the correct webpage


In the mobile view, the index.html file will show plain text over an animated background instead of animated text, and the text will be smaller due to size limitations
The top navigation bar will be shown as a hamburger menu which can be expanded when clicked.

Meanwhile, the animations and text formatting for the main webpages and information pages will be different to fit the size constraints.

In the web view, the index.html file will show the animated text and all of the full menu options.
The main webpages and information pages will also show lengthier explanations with full menu options.

An interesting problem was the issue of formatting where the text appeared in odd places in the mobile view and required checks and edits to correct them.
Another problem was the issue of animations not being loaded properly in the mobile view and required edits or even total changes in order to make the webpages look presentable.

## Credits

### Content (except for form page)
- The text and images are all from myself (except for form page icons)
- Animations and form are improved upon and modified from open source code from Codepen
- Form page icons are from Material+Icons

### Media
- The assets used such as the heart notch and triangles were created from Adobe XD.

### Acknowledgements

This website references open source code from multiple source, and all open source are modified and improved upon.
Some modifications and improvements made would be the fusion of multiple pieces of code, altering the colours and rotation of the animations, expanding or reducing the size of certain designs and many more other edits.


References:

Text-To-Particles: https://codepen.io/Mamboleoo/pen/obWGYr
Stars With ParticleJS: https://codepen.io/bob6664569/pen/rOzmve
Top Nav Bar: https://www.w3schools.com/howto/tryit.asp?filename=tryhow_js_topnav
Particle Orb: https://codepen.io/natewiley/pen/GgONKy
Helix: https://codepen.io/michal-marchewczyk/pen/mjYLjP

