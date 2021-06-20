# WEIGHT UP Gym - Testing Details

[Main README.md File](https://github.com/shaun-davies/weight-up/blob/master/README.md)

## Testing

- [W3C CSS validation](https://jigsaw.w3.org/css-validator/)
- [W3C Markup Validation](https://validator.w3.org/)
-- The developer used W3C CSS Validation Service and W3C Markup Validation Service to check the validity of the website code.

The HTML Validator initially found 2 errors in the code:

1. *Error: Element ul not allowed as child of element h3 in this context.* 
- This was fixed by removing the h3 element which was not in use or needed.

2. *Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.*
- This was fixed by changing the section element to a div, as it was not necessary to start a new section.

##Bugs discovered

###Solved bugs:

1. Bootstrap Framework not working, particularly toggle button unresponsive in Navbar
- Solved by adding Bootstrap script in Body of code.

2. When deployed links between pages not working
- Solved by ammending relative file paths

3. When on small screen size table in Classes page spilling out of div, therefore not responsive.
- Solved by adding *table-layout: fixed* to Style.css

4. When on small screen size contact form spilling out of div, therefore not responsive.
- Solved by wrapping table in a row.

## Testing client stories from UX section of README.md

1.	As a new visitor to the website, I want to easily navigate the site, so I can find what I need efficiently.
- A clear Navigation Bar in the header of each page allows for easy navigation to any where on the website 

2.	As a new visitor to the website, I want view the gym’s gallery, and see what facilities are available.
- On the Home page there is a gallery showing the gym and it's available facilities
- On the Home page there is a section describing what equipment and facilities are at the gym

3.	As a new visitor to the website, I want see what fitness classes are on offer.
- In the Classes page which can be easily seen in the Navigation bar there is a table showing all fitness classes that the gym offers and the scheduled times of these classes.

4.	As a potential client, I want to know what offers are available for membership.
- On the Home page cover text advertises what offers are available
The user can contact the gym through the contact form in Contact to ask about offers

5.	As a potential client, I want to know where the gym is located and if there is car parking available.
- On the Info page there is information on the gym and specifically its availability for on-site parking with membership

6.	As an interested client, I want to know how to contact the gym for membership.
- In the cover text on the Home page there is a link to contact the gym to ask about offers and membership
- The Contact page allows for contact through a message form

7.	As an interested observer and/or potential client, I want to follow the gym on social media, so I can keep up with its latest news and events.
- On each page within the Footer there are four Icons which link to the gyms social media pages.

8.	As a returning client to the website, I want to know what time a particular fitness class is.
- In the Classes page a Fitness Class timetable can be seen showing the different times that classes are offered.

## Manual (logical) testing of all elements and functionality on every page.