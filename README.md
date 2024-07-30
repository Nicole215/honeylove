# Honey Love
Welcome to Honey Love, a page about a local Beekeeper, his busy Bees and their Honey, which can be bought. This sites targets tourists to Torgau who quickly want to check, what to do next whilst strolling through the town. Typically those tourists are either cyclist traveling light or people of 60 years and older. 
You can visit the live site [here](https://nicole215.github.io/honeylove/)
![responsivenes](https://github.com/user-attachments/assets/eea4bf4c-a27d-42a4-afe9-784bdc3c9cd5)

# User Experience (UX)
### Target Audience
- People living in Torgau and around, who are looking for fresh organic honey.
- People visiting Torgau, who want to experience more than museums and grab a unique souvenir.
- Vendors looking for large quantities of honey to sell on.
### User Stories
#### As a site visitor
- I want to be able to determine the site's purpose at a glance.
- I want to be able to easily navigate the site.
- I want to be able to identify the content of each site.
- I want to be able to contact the Beekeeper to buy honey or visit the bees.
- I want to be able to see it all on the smaller screen of a mobile phone.
#### As the sites administrator
- I want to be able to quickly update the sorts of honey sticking to the design.
# Design
This site was designed with tourists on bikes and elderly people in mind. It was built with a mobile-first approach, as most tourists travel light and would access the site via phone or other mobile device. Therefore the site is clearly structured with the navigation bar open at all times to allow the users to grab the full content and it's purpose at a glance. The site has no educational purpose. Therefore the Bees page is focussed only on inmpressive facts to gain respect for the Bees and their work.
### Wireframes
The design and structure for this website was created in [Balsamiq](https://balsamiq.com/). The designs produced were desktop versions only.
![layout_main](https://github.com/user-attachments/assets/bfd5ae6a-b455-4301-a2e9-03ba48a605ff)
![layout_contact](https://github.com/user-attachments/assets/303407a1-ed4f-4856-90a7-8375f2e35ab8)

### Color Scheme
- Brown and a light yellow were chosen as the colors to represent the colors of honey and bees. The brown frame around each content reminds of honeycomb-frames.
- Colors were picked using Coolors
- ![colors](https://github.com/user-attachments/assets/b4d429d3-6e46-42b8-8648-0f47f4ad9a37)
- Contrast was tested using WebAIM
- ![contrast](https://github.com/user-attachments/assets/8d2159f2-f864-4606-b856-70d8d4512c58)

### Fonts
- "Open Sans" was chosen for it's simple look, with a backup font of sans-serif.
- It was chosen for its unobtrusive look, what makes it easy to read.
- The font was selected from [Google Fonts](https://fonts.google.com/).
# Features
Honeylove is designed and structured to make accessing information as easy for the user as possible.
### Existing Features
#### Navigation Bar
- The navigation bar is present at the top of all pages of the site. It includes links to Home page, Bees page, Honey page and Contact page.
- It is fully visible in mobile version as well, to provide an overview of the content and make navigation easy.
- The current page is highlighted with a brownish underline.
- ![navbar](https://github.com/user-attachments/assets/69ecf67d-0048-46d5-a7bc-25402812b6d1)

#### Video on landing page
- I have decided against a hero image and instead imbedded a short video of the beekeeper working on the bees. The video gives a quick preview of what to expect during a visit.
- ![video](https://github.com/user-attachments/assets/b1ba7933-ac04-487e-9c3f-3af2216753e6)

#### Main Content
- All main sections throughout the site maintain a consistent layout and styling. Whilest the styling reminds of honeycomb-frames, this design also makes it easier for the user to know which picture and information goes together.
- Only the landing page sticks out by not having a frame around the information provided. The intention behind this layout is, that the landing page is about humans, whereas the Bees page, Honey page and Contact page are focused on bees and bees products.
- ![main_content](https://github.com/user-attachments/assets/1cecf328-80b4-4bbf-944e-78976dc9594d)

#### Footer
- The footer element contains 3 icons, linking to the main social media platforms.
- The footer is consistent throughout all pages.
- The icons are styled in the sites primary color.
- ![footer](https://github.com/user-attachments/assets/f5904faf-3001-4aec-837e-f799aae03b4c)

#### Address and Map iframe
On the last page of the site the users can find the address with a map iframe.
#### Contact Form
- Also on the last page of the site the user will find a contact form to fill in either a desire to visit the bees or buy honey. This is mainly to check availability beforehand.
- Name, email and feedback are mandotory fields. 
- Submitting the form will take the user to the form dump page provided by Code Institute.
- ![contact](https://github.com/user-attachments/assets/3bcebc3e-e37b-4742-b06a-1b3da9746651)

### Future Features
1. Include shipping costs
- To provide a better experience for vendors, I would include a table containing shipping costs.
# Testing
### Validator Testing
- HTML - all four pages were tested with the same result
- ![htmltest](https://github.com/user-attachments/assets/9d37e6c4-febb-406f-9b76-1cdd2977834c)

- CSS
- ![csstest](https://github.com/user-attachments/assets/e4416b1a-0987-4876-bbef-2774b4338dd5)

- Accessibility, Performance, Best Practice, SEO (tested with Lighthouse Chrome DevTools)
### Browser Testing
- Layout: The site got tested on mobile phones, tablets and laptops for its responsivnes.
- Functionality: All links, navigation and form submit functions got tested in different browsers.

| Browser | Layout | Functionality |
| --- | --- | --- |
| Chrome | :heavy_check_mark: | :heavy_check_mark: |
| Edge | :heavy_check_mark: | :heavy_check_mark: |
| Firefox | :heavy_check_mark: | :heavy_check_mark: |
| Samsung Browser | :heavy_check_mark: | :heavy_check_mark: |

### Manual Testing

| Feature | Expect | Action | Result |
| --- | --- | --- | --- |
| Navbar | When clicked, the respective page will open | Click all navbar items | All respective pages open when clicked |
| Social link icons | All links open linked pages in new tab | Click all individual icons | All social media sites open in new tab |
| Google Map | Google Map to open in new tab when enlarge gets clicked, no accidental opening / Maps offers to open in App on mobile phone | Click on Map | Opens only when clicked enlarge / Map wants to open in App on mobile phone |
| Form submit button | Form submits when submit button is clicked | Fill out form and click submit | CI form dump page opens and displays content |
| Required form fields | Required fields will be highlighted if not filled correctly when clicking submit | Fill out incorrectly | Form highlights missing or incorrectly filled fields, does not submit |

# Technologies Used
### Languages
- HTML
- CSS
### Wireframes
- Balsamiq
### Libraries
- Google Fonts
### Platforms
- Github
- Gitpod
### Other Tools
- Coolors
- WebAIM
- Fontawesome
- Favicon
# Deployment
1. I deployed the site via GitHub pages via the following procedure:
- From the projects repository, go to the setting tab
- From the left-hand menu, selct the Pages tab
- Under the source section, select the Main branch from the drop-down menu,, leave the folder on root and click save
- After a few minutes the page will refresh and provide a link to the deployed site
# Bugs
In the dev tool preview for mobile both iframes, the video and the google maps, would overlap the fixed navigation bar. It did not do so on an actual mobile phone. Hoewever, the issue could be fixed easily using z-index.
# Credits and contact
### Credits
- For putting pictures in a box I used W3
- For iframe styling I also used W3
- For installing an error page, I followed the step by step instruction by GitHub
### Content
- All media used is my own. What I know about bees and honey I learned from my father, the senior beekeeper of the family.
- Fonts were taken from Google Fonts.
- Social Media icons were taken from Font Awesome.
- Favicon
### Contact
The address used on the contact page is real and honey can be bought Monday to Sunday from 8 am to 8 pm. The Beekeeper speaks little english. If you need a translator or want to order a bucket full of honey, you can contact me: Daria215@gmail.com

