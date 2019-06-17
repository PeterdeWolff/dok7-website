# **Readme file for the Website DOK7.**

Below you will find a description of the website for clothing store “DOK7woensel”  built for the first milestone project of the Code Institute full stack developer program.
The site can be visited using the URL:  https://github.com/PeterdeWolff/dok7-website

DOK7 is a small clothing store for men and women.  The store continuously updates their collection according to the latest fashion.  Pictures of their collection are often shown on social media like facebook and instagram.  The website presents all the basic info like opening hours, address, brands, team, upcoming events and the possibility to leave a remark or question  on the contact page. 
The main goal of the website is to inform (potential) customers. To give them a website where they can find information about address and opening hours, the brands they sell, upcoming events etc. The website is a need next to various social media platforms like facebook, Instagram.
There is also a contact page where at this moment customers can ask  questions or leave a remark. In the future this might be updated and used for reviews and signing in for a newsletter.
At this moment the owner does not have the need to add online shopping to the site. Of course this might change and is therefore a feature to implement in the future.

## **Business goals of this website are:**
-	Provide the basic information to (potential) customers
-	Show brands they sell
-	Give a impression of the shop (using pictures)
-	Promote events

## **Customer goals of the website are:**
-	Find information about opening hours, address
-	Find the main brands they sell
-	Look for upcoming events
-	Ask any questions
-	See who is working there

## **UX**
Visitors of the website are (potential) customers searching for information, the people that are questioned all knew that the website does not offer an online shop.

The user stories below are initiated after interviews with several potential users and the owner of the shop.

## **User experience client stories are:**
-	As a new visitor to the website, I want to easily navigate the site, so I can find what I am looking for efficiently.
-	As a (new)  visitor to the website, I want to view what brands they are selling for women.
-	As a (new) visitor to the website, I want to view what brans they are selling for men.
-	As a (new) visitor to the website, I want to find general information about location and opening hours.
-	As a (new) visitor to the website, I want to see who is working there.
-	As a (new) visitor to the website, I want to see if and when there are upcoming events.
-	As a visitor or customer to the website I want to have the possibility to fill in a form, so I can make contact and ask 		questions or leave a remark. 
-	As a (new) visitor to the website, I would like to get an impression of the store.
-	As an interested visitor and/or (potential) customer I want to follow the store on social media to keep up with the latest 		updates.
-	As the owner of the shop I want to receive email addresses to be able to inform my (potential) customers via email.
-	As the owner of the shop I want (potential) customers to follow us on social media, so the website must have the option to 		redirect them to these platforms.

## **Technologies used**

-	HTML5
-	CSS3
-	[BootstrapCDN](https://www.bootstrapcdn.com/)
    **Bootstrap4** is used to simplify the structure of the website and make the website responsive easily.
-	[Google Fonts](https://fonts.google.com/)
    **Google fonts** is used to style the website fonts.
-	[Cloud9](https://c9.io) is used for building the website
-	[Github](https://github.com/) is used for the repository hosting service

## **Mockup**

[Mockup](../assets/images/mock-up dok7.pdf)


## **Features**
At this moment the website consist of 5 pages. Home, about, women, men and contact page.
Each page features a header with a responsive navbar (hamburger menu for mobile) with company logo on the top left and a footer with social media links and logo of the shopping center on the right.  The social media links are not yet linked to the social media platforms. 

The company logo act as a home button and will redirect to the home page. The navbar will highlight in green the page you are visiting.
The “home” and “about” page also have a top-bar that show opening hours and on large screens also  the phone number of the shop.
A video giving an impression of the shop is placed on the “about”page 

### **Home**
The “home” page features a picture of the shop as background. Furthermore there are 3 text boxes. On large screens the boxes are inline.  On the right site the text box for event info, in the middle a general text and on the right side info about extra opening hours.

### **About**
The “about”page Consist of general information of the shop and shopping center. It represents the team who is working there including a picture. Next to this there is a video (.mp4) to give an impression of the shop.  A .mp4 file  is supported by all HTML5 browsers and comes with a standard playbar.

### **Women**
The “women” page shows all the brands with their logo’s.  By clicking in the logo of the brand you will be redirected the de website of that brand.  There are also to pictures of the shop

### **Men**
The “men” page is the same as the women pages, only using  the brands for men.

### **Contact**
The “contact” page shows the address and opening hours of the shop. It also features a contact form for questions and remarks. The form has 3 fields;  name, email and comment.  All the fields are required. The field for email is has also a check on using the “@” sign.  
The form will be directed to an email address (not yet implemented)

## **Features left to implement**
In the future I would like to add a few extra services like:
-	The GDPR requirements, 
-	A blog, where customers can leave their review
-	easy option for uploading new pictures by the owner (in combination with social media)
-	online purchasing
-	Dutch translation

## **Testing**

All pages are checked using the W3C CSS validiation and W3C Markup validation. 

### **Testing Client stories**

-	As a new visitor to the website, I want to easily navigate the site, so I can find what I am looking for efficiently.
	*A visitor easily go through the site using the navigation bar.  The logo always redirect to the landings/home page. The navbar 	item of the page you are  will have a green background.*
	
-	As a (new)  visitor to the website, I want to view what brands they are selling for women.
	*The page women  will show the logo’s of the brands the shop is selling.  Clicking on the image will direct you to the website 		of the brand. The website is opened in a new tab.*
	
-	As a (new) visitor to the website, I want to view what brands they are selling for men.
	*The page men  will show the logo’s of the brands the shop is selling.  Clicking on the image will direct you to the website of 	the brand. The website is opened in a new tab.*
	
-	As a (new) visitor to the website, I want to find general information about location and opening hours.
	*The address of the shop is shown in the footer of the landings-page and also at the contact page.  Opening hours are visible on 	  large screens in the top-bar and also on the contact page. Additional opening hours and or events are shown in the text blocks 	  on the landings-page.*
	
-	As a (new) visitor to the website, I want to see who is working there.
	*The about page has some general information of the shop and the team, the shopping center. There is a picture of the team and 		video of the inside of the shop. The video uses the standard settings/playbar of HTML5;*
	
-	As a (new) visitor to the website, I want to see if and when there are upcoming events.
	*Events and extra opening hours are displayed on the landings/home page*
	
-	As a visitor or customer to the website I want to have the possibility to fill in a form, so I can make contact and ask 		questions or leave a remark. 
	*On the contact page there is a form with three required fields.  The fields are: name, email and an open field for 			remarks/questions. The email address is checked on the use of the “@”sign. The form is not yet directed to an email address.*
	
-	As a (new) visitor to the website, I would like to get an impression of the store.
	*Every page except the contact page has pictures of the shop. On the about page is also a video.*
	
-	As an interested visitor and/or (potential) customer I want to follow the store on social media to keep up with the latest 		updates.
	*The social media icons can be found in the footer on every page of the website. The icons are not yet directed to the social 		media platforms*
	
-	As the owner of the shop I want to receive email addresses to be able to inform my (potential) customers via email.
	*The owner of the store can use to website to present their latest fashion and to announce upcoming events like extra opening 		hours or sales. The owner receives customer info via the form what they can use for direct communication with the customer.*		
	*NOTE!!  The GDPR requirements are not yet in place to ask permission for sending newsletters and/or promotional information. 
	For now there is no wish for selling online.  Visitors can reserve a certain piece by sending an email or fill in a submission 		form via the website.*
	
-	As the owner of the shop I want (potential) customers to follow us on social media, so the website must have the option to 		redirect them to these platforms.
	*The social media icons can be found in the footer on every page of the website. The icons are not yet directed to the social 		media platforms.*

## **Functionalities**

- The navbar is responsive and will convert to an hamburger menu on medium and small screens.

- When hovering over the navigation buttons, the background will be green

- The company logo has a “home” function on all pages.

- The first navigation button “about” should direct to the “about” page.  On the about page you will find some history of the store and   what they stand for. Also a pictures of the team and video are available here. The play bar of the video is the standard of HTML5. The   volume can bet set in the play bar even as the screens size of the video.

- The  navigation button “women” should direct to the “women” page.  On this page you will find the brands for women and some pictures.   The brand logo’s are also linked to their website. All links will be opened in a new tab using the target = “blank” rule.

- The navigation button “men” should direct to the “men” page.  On this page you will find the brands for men and some pictures.  The     brand logo’s are also linked to their website. All links will be opened in a new tab using the target = “blank” rule.

_ The navigation button “contact” should direct to the “contact” page.  On the contact page you will find the address details and         opening hours. Also the form will be present here. You can leave your email address and a remark/question.  The email field is           required and in case there is an invalid submission the error “invalid email address” will be noted.

  (There is not yet  a checkbox for the opt-in where you give permission to use the email address to sent promotional information)

- Site is responsive for all screen sizes. This is checked by changing the screen size from desktop to tablet (ipad) to mobile.

- In the footer there are links to the social media platforms “facebook”, “Instagram” , “linkedIN”and  pinterest.  Hovering over the       icon will change the background color into orange.

- The icons are not yet directed to their platforms

- On the contact page the  Questions and remarks are not shown on the site.  The send button is not yet activated. 


## Deployment

This project was developed using the [Cloud9 IDE](https://c9.io), committed to git and pushed to GitHub using the built in function within cloud9. 

The site can be visited using the URL:(https://github.com/PeterdeWolff/dok7-website)


#### General information

The owner of the store can use to website to present their latest fashion and to announce upcoming events like extra opening hours or sales. The owner receives customer info via the form what they can use for direct communication with the customer.  NOTE!!  There must be an opt-in to ask permission for sending newsletters and/or promotional information.

For now there is no wish for selling online.  Visitors can reserve a certain piece by sending an email or fill in a submission form via the website.
