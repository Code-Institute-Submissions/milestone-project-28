# King Performance Therapy
This is a website for a Chartered Physiotherapy and Personal Training business that allows prospects to gather an understanding of the services on offer and to allow them to fill out a form where they can request a specific time for an appointment.
https://edking94.github.io/milestone-project-1/
## UX
- This website is for any individual who is seeking physiotherapy or personal training, as they are in pain or want to get into shape respectively. 
- It allows each user to learn more about the services on offer and to request a time for the appointment type they would like. 
- The goal is to drive users to "book-now.html" (using call to actions) to fill out this form which will result in a phone call being made to them by the sales/admin team to confirm their booking.
###User Journey
#### User X: 
- As a prospective physiotherapy customer (user X) I can learn more about the product by clicking on the services page in the navbar or "more info" in the physio card in the services section on the homepage. 
- I read about how Physio can help me with my pain. 
- A call to action immediately follows the content I was reading which leads me to booking.html where I fill out the form and await for my booking to be confirmed. 
- IF I do not desire to fill out a booking form but I am also wanting to learn more, I can click on the “About Me” page or contact King Performance Therapy directly using the many contact forms/contact page which is designed for this purpose.
#### User Y: 
- As a prospective personal training client (user Y) ) I can learn more about the product by clicking on the services page in the navbar or "more info" in the personal training card in the services section on the homepage. 
- I read about how Personal Training can help me with my weight loss.
- A call to action immediately follows the content I was reading which leads me to booking.html where I fill out the form and await for my booking to be confirmed. 
- IF I do not desire to fill out a booking form but I am also wanting to learn more, I can click on the “About Me” page or contact King Performance Therapy directly using the many contact forms/contact page which is designed for this purpose.

#### Link to balsamiq for wireframe: 
https://balsamiq.cloud/sy63kqw/pun0db2

## Features
- Primary Goal Of Features – Drive users X + Y to book-now.html so that they seek a booking
- Secondary Goal Of Features – Increase the understanding the users have about the services or the provision of the services and then drive them to the book-now.html page 
### Existing Features
#### Call to actions 
- There are 9 "book now" buttons scattered across all of the pages strategically placed after a piece of content that increases the User's understanding of the services. These call to action buttons lead directly to book-now.html which is the primary goal of the UX.
#### Booking Form (Pimrary Goal) 
- allows users X+Y to request a booking at their preferred time for Physiotherapy or Personal Training appointment by having them fill out the booking form on book-now.html.
#### Contact Form (Secondary Goal) 
- allows users X+Y to ask questions to the business about the business. Contact forms are available on every page to facilitate this.
#### More-info (Secondary Goal) 
- these links lead directly to the relevant section of the service that the user requested more information on. Once the user has consumed the extra information there is a call to aciton button awaiting them which will lead them to book-now.html if they feel the understanding of the service is sufficient.
#### Map (Secondary Goal) 
- The iframe of google maps allows users to see where the business is so that they know it is possible to get there.
#### Testimonials (Secondary Goal) 
- Testimonials are there to illustrate to the user that this service has helped others with their problems, therefore it can help them.
### Other Feature Ideas
- Having a cliniko (scheduling software) API embedded into the page book-now.html so patients can actually make their own bookings which would reduce the length of the sales cycle; similar to this https://kingpt.ie/book-now/ . 
- Have a consent form page. Once the patient books online using the above cliniko software they receive a confirmation email which contains a link to the consent form page which is similar to this https://kingpt.ie/consent-form/ . This page would not be located in the NavBar as it would interrupt the initial UX.
## Technologies Used: 
- **html**
- **CSS**
- <a href= "https://getbootstrap.com/">**Bootstrap**</a> - The Project uses Boostrap to facilitate responsiveness across device types and to use the extensive pre-built component library to expedite the construction of the site. 
- <a href="https://getbootstrap.com/">**Font Awesome**</a> - The Project uses Font Awesome for its social media, mail and telephone icons as this gives a beter user experience. 
- <a href="https://www.google.ie/maps">**Google Maps**</a> - The Project uses Google Maps to allow the user to see where King Performance Therapy is located. 
- <a href="https://formdump.codeinstitute.net/">**Code Institute Form Dump**</a> - The Project uses the form dump as there is currently no back-end for this project where the data from the forms can be stored
## Testing
- **Call to actions**: 
- All 9 call to action buttons were used and resulted landing on the book-now.html page. 
- It would be ideal to have an animation for the landing on the book-now.html page to improve the UX.

**Contact-Forms + booking-form**: 
- Attempted to submit empty forms to verify that an error message about the empty fields appears. 
- Attempted to submit single empty "required" fields to verify that an error message appears. 
- Attempted to submit an email address in the wrong format to verify that an error message appears. 
- Submitted full form in correct format to verify that the form works; the form dump page appears to verify this.
- Issue 1: 
- The name attribute was missing from all forms so no data was being sent/displayed to the form dump. This was fixed.
- Issue 2:
- The data submitted in the booking form is jumbled up and not in the order that it was filled in on the front-end. It is believed that this is due to dividing some of the page up into 2 columns within rows; this issue currently remains there.

#### More-info: 
- The more-info links that are linked to the Physiotherapy Section on services.html worked correctly; the same process was undertaken for the more-info links that are linked to the Personal Training section on services.html. 
- It would be ideal to have a landing animation for this to improve the UX.

#### Header responsiveness: 
- At and less than 1025px width the Navigation menu and logo became too bunched together so a media query was used to get rid of the logo and to have a drop-down menu for the navbar to improve the user experience.

#### Page responsiveness:
- Throughout the project at and less than 515px the whole right side of every page became increasingly white as the width of the screen decreased. It was always unknown why this was happening as many attempts to solve the problem using developer tools were made. However, around the time that the header media query was implemented this issue started to happen at and less than 401px in width. It currently remains there and does not highlight when observed using developer tools.
- Images used in this prject were initially far too big which was slowing down the load time. Image have to be replaced with versions under 500KB.
#### Images 
- Many attempts were made to have “footerlogo.jpg" in the left corner of the header and the footer; however, after many attempts it proved to be too difficult and time consuming to do ti well enough. The words "King Performance Therapy" sufficed as the logo for the header and the footer was left alone.
#### Loading time
- Hero Image is far too big, therefore loading time is too slowing.
- Many attempts were made to compress hero image to reduce loading time but this led to image having a severe lack of focus which was uncomfortable to view.
- A trade off was made: slower loading time for a better visual experience for the user.
- All other images in the prject were compressed to be around 500KB in size.
## Deployment 
- Landed on the github page for my milestone project at this link https://github.com/edking94/milestone-project-1
- Clicked into Settings on the above page.
- Scrolled down to "GitHub Pages" section.
- Published the master branch which is available at this link https://edking94.github.io/milestone-project-1/

Credits 
Content 
The text for section Y was copied from the Wikipedia article Z Media The photos used in this site were obtained from ... Acknowledgements I received inspiration for this project from X
