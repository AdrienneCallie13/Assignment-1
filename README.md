Summary:

'Around Us' travel websites provide a platform for destination management corporations to supplant local travel agencies. The goal of travel websites is to give information on tourist destinations, whether they be local or worldwide. When arranging vacations to places users are unfamiliar with, users may need to do some research. 

There are three main menus under the 'Explore' menu:

•	Firstly, on the 'Flight' page, the user can book a flight ticket before travel.

•	Secondly, under 'Travel Destination', users are able to book the accommodation according to their needs. This is because the website page provides a function for users to range the accommodation price, stay dates, as well as locations.

•	Thirdly, in the 'Experiences', users are able to book a theme park ticket, museum entry ticket, and many more.

With 'Around Us', not only make people's lives easier by planning and booking their travel, but it is also a sharing platform from people around the world to share their travel destination, provide feedback, recommendation, and suggestion about the holiday experience.


Asset list:

There are some main asset lists that I am going to use on my project, which include:

Index.html: This is my website's home page. The majority of the site's functionality will be found on this page. This include metadata for responsiveness. On each page, the Vue apps listed below will be displayed.
style.css, app.js, and app.vue are all included in this static HTML page.

Style.css: Styling the web pages by interacting with HTML elements and using media queries for effectively display of the website responsiveness. Style.css linked in HTML page.

app.js: Using JavaScript on web page helps to create responsive, interactive elements for web pages, aims to enhancing the user experience. app.js linked in HTML page.

App.vue: includes all of the other Vue components. Single file.

Vue components:

Search.vue: This component will accept the user's text input and provide a list of travel destination that match the keywords. 

FormVerification.vue: This verification component is to verifies that all necessary fields are filled out.

Calender.vue: The calendar component will be display on the ‘flight’, ‘travel destination’ and ‘experiences’ search bar for user to decide what date are they going to go for a holiday.  

PhotoCarousel.vue: Using v-card component to display bunch of travel photography captured by experience travellers. This photo carousel will be render under ‘Documentation’ on the ‘support’ page. 

ChatBox.vue: This component allow user to ask inquiry using the live chat feature. 

ContactUs_Call.vue: Create a pop-up box that contains company’s call centre number by using modal component under contact page (call). It is allowed user to ask inquiry through phone call. 

AlertSubmit.vue: Using v-else to create a pop-up alert box after a user manage to create an account.   

GuestsCounter.vue: This component will work well with buttons.  By selecting how many guests, the system will be redirect user to a suitable accommodation according to the number of the guests. 
 
OptionList.vue: Using list rendering to create options on my “Become a host” form by listing several options to identify and verify users.
 
Review.vue: I will apply v-model on my registration form as well as creating a message box for user to write their travel review. 


Product Purpose:

•	Target audience

Traveller 

This travel website could benefit for traveller from all around the world. We want to provide experience for users by solving the concerns of lacking information about accommodation and target destination. In this website, Traveller able to access more options about affordable accommodation and target destination. 

<img width="599" alt="Traveller persona" src="https://user-images.githubusercontent.com/87454125/128650545-c39431e7-201a-4ef1-9f9a-01e7a8290332.png"> Traveller Persona.

Housewife

This website seeks to target housewife who has children and always have plan for a family trip. The ability to find kid and family friendly travel destination from our website give advantages for a family who wants to have a peaceful and efficient travel. 

<img width="599" alt="Housewife persona" src="https://user-images.githubusercontent.com/87454125/128650459-22329162-acc8-442b-afc5-8142b760867f.png"> Housewife Persona.

•	Creativity demonstration 

An easily navigated site map.

Having a well-organized navigation. Using dropdowns in the navigation menu so that the users can find the information under each heading from any page.

Include necessary elements that will improve the value of the website.

By create elements that are functional and enhance the user experience on the website. Such as, high-quality travel photography or interactive elements to have visually appealing website. 

Instant reservations.

By using API to integrate any booking system on the website. The benefit of booking engines is that simply adding a plugin into the website, it also can obtain real-time information on available rooms and pricing.

Components explanation:

Intended behaviour

Vue complex components explanation:

Conditional Rendering: I will be using “v-if” and “v-else to show the tickets availability under the ‘Explore’ page. As well as an alert for user who typed incorrectly on the sign-up or sign-in page.  

Event Handling: Using “v-on” to monitor DOM events and activate JavaScript as they are triggered. I will implement this on my booking ticket page as the user able to decide how many tickets they would like to purchase. 

List Rendering: It is used to create a list of items generated from an array and display it on a webpage. 

Declarative rendering: It is allowing us to render data to the DOM using simple template syntax in Vue. To interpolate the needed data in the DOM, double curly brackets are applied as placeholders.

Form input binding: Using “v-model” on form input and text area components to build two-way data connections. 


User intention and goals: 

<img width="389" alt="user story 1-3" src="https://user-images.githubusercontent.com/87454125/128650621-7618b62a-27df-48ee-aec7-f3188ac0c5e8.png"> 
<img width="389" alt="user story 4-8" src="https://user-images.githubusercontent.com/87454125/128650625-f66d21b4-d265-438b-ba92-caa7067366ed.png">
<img width="386" alt="user story 9-10" src="https://user-images.githubusercontent.com/87454125/128650623-09c471d3-1d6f-41c2-98af-439f9af27de4.png"> 

UX/UI design

To have visual aesthetic website, there are few colours schemes that I’m going to implement them on my website. 

<img width="422" alt="Screen Shot 2021-08-09 at 10 14 30 am" src="https://user-images.githubusercontent.com/87454125/128650673-9dde6e1a-efa5-486e-9d8b-61b8de1c6acc.png"> color palette.

The main colour of the website will be the #807C82 and #D9D3D1. Instead of using black and white, I used slightly light black colour and fade white to avoid boring and eye-hurting interface. Beside colours, I also consider using illustration to styling the website.  

The most important UI/UX feature is the functionality. Because it is a travel service website, it will have a lot of functionality such as search engine, navigation bar for accessing the information, and buttons. I aim to have multi-pages HTML, so the homepage is the main page of the website with lots of pages link to it. Using CSS to build a card layout and media object will be applied after the landing page.

On this first version proposal, I have created four UI designs for both mobile and web on Figma.

<img width="695" alt="website homepage" src="https://user-images.githubusercontent.com/87454125/128650737-7b293207-30a5-4d0c-ac4c-91bdd07aebf1.png"> Homepage. 

<img width="340" alt="explore" src="https://user-images.githubusercontent.com/87454125/128650996-f8aae547-3a9a-47ab-8de8-de83b7c306d3.png"> User story 1.

<img width="340" alt="service" src="https://user-images.githubusercontent.com/87454125/128650988-e651a4af-d3b9-49c8-9752-8fd55675226c.png"> User story 5 and 6.

<img width="340" alt="support" src="https://user-images.githubusercontent.com/87454125/128650976-9f0d7418-57b6-4b36-9dc8-8b236f18b19d.png"> User story 3,4, and 10.

<img width="340" alt="community" src="https://user-images.githubusercontent.com/87454125/128650986-fd54d1fc-a979-4b0d-9825-fc1946e91096.png"> User story 2.

<img width="525" alt="user story 9" src="https://user-images.githubusercontent.com/87454125/128651147-6765fed5-4b32-4d90-8d4a-f78a81d50191.png"> User story 9.

<img width="525" alt="user story 2" src="https://user-images.githubusercontent.com/87454125/128651151-bd8a7722-95a6-4bc8-bc05-5cad39c012dd.png"> User story 2.

<img width="525" alt="user story 8" src="https://user-images.githubusercontent.com/87454125/128651141-e284df9e-2fec-4e07-9ef1-7664d615f344.png"> User story 8.

Web system summary: 

Below is the user journey through the website's primary functions. After user enter the website, they may access the website's functionality via homepage.

The following features will be available on this website:

•	Additional information about travel under the services menu.

•	Users able to book flight, accommodation, and other fun experiences under ‘Explore’ menu.

•	To change languages for the entire website, guide, and live chat will be provided under ‘Support’ menu.

•	Users also able to share their experiences under the ‘community’ menu.

<img width="355" alt="Screen Shot 2021-08-09 at 10 56 25 am" src="https://user-images.githubusercontent.com/87454125/128651282-5fe77230-d715-4e87-a703-d6531ac006e9.png"> Web system functionality.

