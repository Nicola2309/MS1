## Testing

The testing process is described below. it includes:
- Testing User Stories
- Checking website compatibility on different browsers
- Checking responsiveness of design on all screen sizes
- Validating HTML, CSS and JavaScript code
- Manually testing the functionality of all links
- Manually testing the sign up form with client's requests

To return to the previous document, click [here](https://github.com/Nicola2309/MS1/blob/master/README.md)

### Testing User Stories

These following tests were conducted to test the experience of each user reported earlier.

#### Project stakeholder
The creator's of this website aim is to connect effectively the last majority of positive feedbacks to the website structure.
Specifically, making people know what and from whom are they buying in a relaxing and minimal environment to navigate in.

#### New Customers Comments, New Users

*User one (who is an occasional tourist):*
- As this customer liked the company after casually wallking in the village, the customer would come to the website to learn more. Testing the customer's process of navigation leads to the following journey through the website:
    * Home: The mobile user would be prompted with a presentation of the company's expertise and its values, the user can decide immediately and freely the page of interest in the website.
    * 'About Us': In this part, the user would come to know the people behind the company, the company's history and evolution. In the second half of the page the user would read other customers' experiences and then decide whether to go further in the navigation and check the menu's or get the company's contacts.
    * 'Menu&Delivery': Here the user can click the menu's links and see what the company has to offer, and order if the customer happens to be in the company. As a side important effect it improves safety during these virus times. The customer can scroll down and see also on and off menu products, which can be ordered mainly as a delivery option.
    * 'Contacts': This page helps the user in keeping in touch with the company, or complete a form for special requests the user might already have. The user can fill the form, describe briefly the occasion in which the service is required and the products the user needs.
- This user would leave knowing everything that has chosen to know about the company, confident that receiving a good service and quality products happens constantly in this company.

*User two (who's living slightly out of the company's delivery routes):*
- As this user might already know the company, its products, and services, the user's will is to get delivered the products home, despite the living location position. To do that there are a few options:
    * Use the navigation bar and select immediately the 'Contacts' Page.
    * It is possible to see the Location, Phone Number and Email Address and the Social Media accounts of the company by accessing the 'Home' Page and every other page and scrolling down to the footer. 
    It is also possible to click on the Whatsapp icon in the footer, and get redirected to the 'Contacts' Page.
    * Offering differently located solutions eases the user's contact process. The variety of contact methods described above allowes the user to choose their most familiar, and leaves a positive user experience.
- However, if the user decides to be updated with the company's activities it is possible to:
    * Follow the company on its Social Media accounts to get real time updates of the fresh made products and programmed events.

#### Regular Customers Comments, Regular Users

*User one (regular visitor of the village in which the company is located):*
- This customer have visited the company earlier and finds it reliable on different aspects. To organise a time saving visit, the website is used in this way:
    * The user accesses the Menu Page and checks the products needed according to the arrival time at the company. The chosen items might be for lunch, aperitivo, or elaborate icecream products.
    * The user can then decide to use the form in the website to ask for a reservation and explain all the requests at once, and Submit them.
    * The user can utilize any other contact option the website provides.

*Customer two (customer in need for a personalized product)*
- This user needed a special birthday cake, and asked for it this way:
* The user accesses the 'Home' Page of the website and clicked on the 'Contact' Page.
* The user filled in the form specifying the description of the personalized cake in its final part.


#### Tablet user

As a tablet user, this user wanted to have a positive experience of all aspects of the website design. They would navigate the website in the same way as the first new user described above, with these differences:
- Certain elements are presented in rows, as opposed to columns to allow a visually satisfying experience. 
- The navbar menu differs from the mobile's one since it is not collapsed, it has all the navigation elements through the navbar, filling the wider space the navbar has on a tablet, and being visually satisfying.
- Any user, including the tablet ones, can decide to download the menu's and take a look at them anytime.
The user would discover that the website is fully functioning on a smaller screen and would leave positive and willing to return again.

### Validating the HTML and CSS 

#### HTML

My HTML code was passed through the [W3C Markup Validation Service](https://validator.w3.org/).
Doing so brought up the errors below that I solved in the following ways:
 - *index.html* - The navbar `role="navigation"` was not needed to be included, so I deleted it, and the code passed the tests.
 - *aboutus.html* - I was shown that I did not need to include the `type="text/javascript"` in my script tag to my local JavaScript myScript.js file. I removed this from all the pages and the code then passed the tests.
 - *menu&delivery.html* -  This file passed without any errors.
 - *contacts.html* - This file also passed without errors.

 #### CSS

 I checked my CSS code with the [W3C Markup Validation Service](https://jigsaw.w3.org/css-validator/). 
This test produced `background-clip="text"` property as an error, I had to remove that and the gradient, choose a single color for my icons instead of the double colors miming the Logo ones. I will use polyfill as I have better JS skills.

### Testing  compatibility with different browsers

I manually tested the website on the following web browsers, checking that buttons, responsiveness and design worked as planned:
- Google Chrome 
- Mozilla Firefox 
- Ecosia

### Testing the design's responsiveness on several screen sizes

I manually tested the design of the live project by doing the following:
- Using Google Developer Tools to view the project on devices with different screen sizes.
- Asking for feedback from friends and family who opened and interacted with the project on their devices.

#### Results and changes

- These manual tests led to changes in image height, margins and padding of certain features targeted with media queries, which can be viewed by seeing changes to my project through the [commit history](https://github.com/Nicola2309/MS1/commits/master). 

### Manually testing the functionality of all links

The following tests were made to see that all links responded as they should:
- Social media links were clicked on to make sure that they open in a new tab at the correct corresponding landing page.
- Menu and Footer bar items were clicked on from each page to make sure that they navigate to the correct page and that they are correctly shown as 'active' when selected.
- The Requests 'Submit' button only accepts the form when it has been completed with all required fields filled in. Once done so and clicked, the 'Submit' sends the data to the company.
- Clicking on the logo in the menu bar leads the user back to the home page.

### Manually testing the 'Requests' form

In order to test the success of the code, I tried submitting the form without meeting the requirements. 

#### Results and changes


The form produced the correct error message as expected, as shown below. There were therefore no necessary changes to make.
![Error message on requests form](https://github.com/Nicola2309/MS1/blob/master/img/READMEimgs/form-testing.png)

[Return to previous document here](https://github.com/Nicola2309/MS1/blob/master/README.md).


