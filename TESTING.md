# WEIGHT UP Gym - Testing Details

[Main README.md File](https://github.com/shaun-davies/weight-up/blob/master/README.md)

## Testing

- [W3C CSS validation](https://jigsaw.w3.org/css-validator/)
- [W3C Markup Validation](https://validator.w3.org/)
The developer used W3C CSS Validation Service and W3C Markup Validation Service to check the validity of the website code.

The HTML Validator initially found 2 errors in the code:

1. *Error: Element ul not allowed as child of element h3 in this context.* 
- This was fixed by removing the h3 element which was not in use or needed.

2. *Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.*
- This was fixed by changing the section element to a div, as it was not necessary to start a new section.

## Bugs discovered

### Solved bugs:

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

### Home Page:
1. Navigation bar:

- Go to the "Home" page from a desktop.
- Change the screen size from desktop to tablet to verify that the navigation bar is responsive and switches from in line menu to burger icon dropdown menu at the appropriate place.
- When checking responsiveness of navbar, verify that there is no overflow causing size changes to menu items. 
- Click on the logo in the navigation bar and verify that it links to the home page.
- Click on each navigation menu item and verify that it links to the correct page.

2. Hero image:

- Go to Home page from a desktop.
- Confirm image is visible and is 100% width of the screen.
- Reduce the width of the window to confirm that the image resizes to mobile screen.
- Reduce and expand width of window to confirm that the overlay on top of image responds correctly and does not obscure important features.

2. Gallery:

- Resize Home page window size and confirm that the images decrease in numbers with screen size whilst retaining their quality and not obscurring any other features.

3. Equipment List:

- Resize Home page window and confirm that the list of Equipments and Facilities stay fitted inside the screen size.

4. Footer:

- Hover over each social media icon and confirm hover movement.
- Click on each icon to confirm it opens a separate tab for it's link.
- Reduce and expand width of window to verify that the footer is responsive and looks good on all device widths.

### About Page:
1. Navigation bar:

- Repeat verification steps done for navbar on Home page.
- Confirm that navbar code is identical on all html pages.

2. Page Content:

- Confirm that this page and its sections are responsive and fits the screen when window size changes.

3. Map:

- Confirm that Map is visible and is functional.
- Confirm that Map is responsive and fits the screen when window size changes.

4. Footer:

- Repeat verification steps done for Footer on Home page.
- Confirm that footer code is identical on all html pages.

### Classes:

1. Page Content:

- Confirm that this page and its sections are responsive and fits the screen when window size changes.

### Contact:

1. Contact form:

- Try to submit the empty form and verify that an error message about the required fields appears
- Try to submit the form with an invalid email address and verify that a relevant error message appears
- Try to submit the form with a file uploaded, verify that file selection process works.
- Try to submit the form with all inputs valid and verify that a success message appears.
- Reduce and expand width of window to verify that the form display behaves and centres the way expected, and that it looks good on all device widths.

## Further Testing:

1. Asked fellow riends and family to look at the site on their devices and report any issues they find.