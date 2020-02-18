<h1>King Performance Therapy</h1>

<p>This is a website for a Chartered Physiotherapy and Personal Training business that allows prospects to gather an understanding of the services on offer and to allow them to fill out a form where they can request a specific time for an appointment.<p>

<h2>X</h2>

<p>This website is for any individual who is seeking physiotherapy or personal training, as they are in pain or want to get into shape respectively.</p> <p>This website allows each user to learn more about the services on offer and to request a time for the appointment type they would like. The goal is to drive users to "book-now.html" (using call to actions) to fill out this form which will result in a phone call being made to them by the sales/admin team to confirm their booking. </p>

<p>As a prospective physiotherapy customer (user X), I want to learn more about the product; so I click on services in the navbar or "more info" in the physio card in the services section on the homepage. I read about how Physio can help me with my pain. As I am reading I decide that I need this service which leads me to click on the call to action at the end of the information that leads me to booking.html where I fill out the form and await for my booking to be confirmed.</p>

<p>As a prospective personal training client (user Y) I read about how this service may benefit me; I also realised that personal training is provided by chartered physiotherapists so they have to know what they're talking about and they may be able to help me with my chronic back at the same time. I am a bit hesitant to pay for one session as I know this may not be enough but I am delighted to see that there is a special offer on. I click one of the many "book-nows" scattered across the website which leads me to book-now.html where I fill out the booking form and await a phone call.</p>

<p>Link to balsamiq for wireframe: https://balsamiq.cloud/sy63kqw/pun0db2</p>

<h2>Features</h2>
<uL>
<li>index.html - the home page allows users to get a sense of what the business is about. The Hero-image facilitates this with a nice picture of the logo on the shorts. There are many call to action buttons on this page in each section which lead to book-now.html where the user can request a booking, which is the goal of the website.</li>

<li>services.html - This page allows users to familiarise themselves with Physiotherapy and Personal Training; with the hope that this increase in understanding of what is ebing provided will prompt the user to click the call to action and follow through with the goal of the website which is to fill out the form on booking.html.</li>

<li>contact.html - This page is solely for users to contact the business. It is a nicer version of the "contact us" sections that are placed on other pages. A secondary goal of the website would be for the user to fill out this form with any questions or queries as this action shows that they have a high degree of interest in the services which means they are good prospects.</li>

<li>about.html - This Page allows the user to understand who is providing the services, what they provide and why they provide it.</li>

<li>book-now.html - The primary goal of the website is to ge tthe user to this page to fill out the form requesting an appointment. Many call to actions on all of the other pagesof the website are there to facilitate this process.</li>
</ul>
<h3>Existing Features</h3>

Call to actions - There are 9 "book now" buttons scattered across all of the pages strategically placed after a piece of content that increases the User's understanding of the services. These call to action buttons lead directly to book-now.html.

Booking Form - allows users X+Y to request a booking at their preferred time for Physiotherapy or Personal Training by having them fill out the booking form on book-now.html.

Contact Form - allows users X+Y to ask questions to the business about the business. Contact forms are available on every page to facilitate this.

More-info - these links lead directly to the relevant section of the service that the user requested more information on. Once the user has connsumed the extra information there is a call to aciton button awaiting them which will lead them to book-now.html if they feel the understanding of the service is sufficient.

Map - The iframe of google maps allows users to see where the business is so that they know it is possible to get there.

Testimonials - Testimonials are there to illustrate to the user that this service has helped others with their problems, therefore it can help them.

Another feature idea -  Having a cliniko (scheduling software) API embedded into the page book-now.html so patients can actually make their own bookings which would reduce the length of the sales cycle; similar to this https://kingpt.ie/book-now/ .
Another Feature idea - Have a consent form page. Once the patient books online using the above cliniko software they recieve a confirmation email which contains a link to the consent form page which is similar to this https://kingpt.ie/consent-form/ .

Technologies Used
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

html
CSS
<a href="https://getbootstrap.com/">Bootstrap</a> - The Project uses Boostrap to facilitate responsiveness across device types and to use the extensive pre-built component library to expeditite the construction of the site.
<a href="https://getbootstrap.com/">Font Awesome</a> - The Project uses Font Awesome for its social media, mail and telephone icons as this gives a beter user experience.
<a href="https://www.google.ie/maps">Google Maps</a> - The Project uses Google Maps to allow the user to see where King Performance Therapy is located.
<a href="https://formdump.codeinstitute.net/">Code Institute Form Dump</a> - The Project uses the form dump as there is currently no back-end for this project where the data from the forms can be stored

Testing

Call to actions - All 9 call to action buttons were used and resulted landing on the book-now.html page.

Contact-Forms + booking-form - Empty forms and single empty "required" fields were left blank when each form was submitted and they did not submit. The wrong format for email addresses were attempted and it did not submit. The full form in the correct format was then attempted and it resulted in the correct format for the form-dump page provided by the code institute displaying all of the data that was provided by the user.
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals. One issue that was encountered at the beginning of the testing process for all of the forms was that there was no date displayed when the form was submitted to the form dump; it was soon realised that the "name" attribute had been left out of all of the inputs for all of the forms. This was very quickly rectified.

More-info - The more-info links that are linked to the Physiotheapy Section on services.html worked correctly. It would be ideal to have a nicer animation for this to improve the UX; the same was process was undertaken for the more-info links that are linked to the Personal Training section on services.html.


Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits
Content
The text for section Y was copied from the Wikipedia article Z
Media
The photos used in this site were obtained from ...
Acknowledgements
I received inspiration for this project from X