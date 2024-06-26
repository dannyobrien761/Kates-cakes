# Kates Cakes
## Kate's Cakes Project Outline

### Project Description:
Kate's Cakes is an online platform designed for a small business specializing in custom-made cakes and cupcakes. Customers can order cakes tailored to their preferences for any occasion, such as birthdays, graduations, and anniversaries. The website will feature a clear step-by-step ordering process, a gallery showcasing previously made cakes, and forms for placing orders and contacting the business.

### Project Goals:
The primary goal of Kate's Cakes is to streamline the ordering process for custom cakes and cupcakes, making it simple and efficient for customers to request personalized baked goods for their special events. By showcasing a gallery of past creations, the website aims to inspire potential customers and demonstrate the quality and creativity of the offerings.

### Target Audience:
The website is intended for individuals and families planning celebrations who seek unique, custom-made cakes and cupcakes. This includes people organizing birthdays, graduations, anniversaries, and other special occasions who desire a personalized touch for their desserts.

Kate's Cakes will be useful for its target audience by providing:
- A user-friendly ordering system that guides customers through the process of customizing their cakes and cupcakes.
- A gallery page that displays previous creations, offering inspiration and showcasing the business's capabilities.
- An ordering form and a contact form, making it easy for customers to place orders and get in touch with the business for any inquiries or special requests.

By meeting these needs, Kate's Cakes aims to enhance the customer experience, ensuring that each celebration is made sweeter and more memorable with personalized baked goods.

![responsivity Mockup](https://github.com/dannyobrien761/Kates-cakes/blob/main/media/am-i-responsive-kc1.PNG)

## Features
### Navigation Bar
**Description:** Featured on all pages, the fully responsive navigation bar includes links to the Home page, Gallery, and Order Form page, along with the Logo for easy identification.
**Value:** This section allows users to easily navigate the website from any device, ensuring a seamless and user-friendly experience.
### Hero Section
**Description:** The landing page features a hero section with a high-quality photograph of a custom cake and an overlay text that introduces Kate's Cakes.
**Value:** This section grabs the user's attention immediately, providing a visual representation of the business's offerings and setting the tone for the site's content.
![hero landing page image and navigation bar](https://github.com/dannyobrien761/Kates-cakes/blob/main/media/hero-section.PNG)
### Call to Action Section
**Description:** This section prominently displays the website logo and includes a direct link to the order form on the Contact page.
**Value:** It encourages users to take immediate action by making it easy to find and access the order form, streamlining the process of placing an order.
![tablet view of call to action section](https://github.com/dannyobrien761/Kates-cakes/blob/main/media/call-to-action-section.PNG)
### Reasons Section
**Description:** The reasons section features a branded image with a clip path and lists compelling reasons for customers to choose Kate's Cakes.
**Value:** This section builds trust and persuades potential customers by highlighting the benefits and unique selling points of ordering from Kate's Cakes.
![desktop view of reasons section](https://github.com/dannyobrien761/Kates-cakes/blob/main/media/reasons-section.PNG)
### Order Process Section
**Description:** This section provides a detailed, step-by-step explanation of the ordering process using <ul> tags, accompanied by a background image and responsive design elements.
**Value:** It ensures that customers understand how to place an order, making the process transparent and straightforward across all screen sizes.
![mobile view of order process section](https://github.com/dannyobrien761/Kates-cakes/blob/main/media/order-process-section.PNG)
### Gallery Page
**Description:** The gallery page showcases images of previous cake designs, allowing users to browse through various custom creations.
**Value:** This section inspires potential customers by displaying the range and quality of Kate's Cakes, helping them visualize their own custom orders.
![gallery desktop](https://github.com/dannyobrien761/Kates-cakes/blob/main/media/gallery.PNG)
### Contact Form Page
**Description:** This page includes a comprehensive form for ordering cakes and treats, with options for delivery or pickup,selecting occasion theme or event type, specifying quantity, type of cake, type of treat, date input for the order and an option to make additional notes to the order to make the custom cakes or treats even more special. 

I opted to used javascript to also toggle to display of the address text area field feature on the form. The display can be toggled on and off using a the radio button features for delivery or pick up and I didnt want users wasting time putting in the address if they are going to pick up the order themselves.  

The date feature on the form allows users to choose a date that the order will be made for but also only allows them to order two days in advance. This is a very specific feature to the needs of the business for kates cakes as the treats should be made fresh for a specific date for the occasion, but also the order should be recieved with advanced notice to prepare them. The solution I found to this particular problem was using JavaScript to validate a minimum allowable date in an input field of type "date".
**Value:** It simplifies the ordering process by providing all necessary options and ensuring users can accurately schedule their orders, enhancing the overall user experience.
![contact form](https://github.com/dannyobrien761/Kates-cakes/blob/main/media/contact-form.png)

### Features Left to Implement

- Another feature idea I would do If I were to progress the website would be to make an "add to order toggle button" which once selected the user could add to the current order a different selection of treats and cakes on the same order.

## Testing 

<ul>
<li>I tested that this page works in different browsers chrome, Firefox, safari
<li>I confirm that the navigation, hero, call-to-action, reasons, order process, gallery and contact texts are all readable and easy to understand. 
<li>I have tested and confirm the form works:requires entries in the critical fields, will only accept and email in the email field and the submit button works.
</ul>

### Bugs

#### Solved bugs
The stretched and zoomed image for the background in the gallery and contact pages appeared pixalated. but I liked the images and didn't feel the need to change them so I came up with a nice solution to add a container with a layer blur effect so the image does not appear pixalated but adds the desired effect of focusing the attention to the content on the page which is the gallery and the form on each respective page. 

### Validator Testing


- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

