# [PRIMARY.PIGMENTS](https://primarypigments.github.io/Primary.Pigments)


I created Primary Pigments to fill a need in the community.  There are many people who are in need of support or wanting to create but do not have access to an option that is simple and local.

Primary Pigments goals are to encourage emotional resilience, nurture self-esteem and self-awareness, promote insight, enhance social skills, minimize and find solutions for conflicts and distress, and create harmony in societal and ecological change. We aim for people who had traumas in their lives and are stuck in this moment. We are also happy with individuals who want to grow creatively and be social. We intend to give our community the opportunity to express their inner thoughts, while helping them to better understand and make sense of their emotions and their mental health. The goals ideas and ideals are not achieved through interacting with the website, instead this site acts as a vessel to guide the user to join and to meet at the events. 
Primary Pigments website makes the effort to keep the information simple and not overbearing so that the users is not  overwhelmed and moves on somewhere else for their creative and/self help needs. We do this by explaining 3 componest about our club, "what to expect, our goals, meetings" followed by corresponding paintings.
We also present a series of paintings from our members. These represent the possibilities healing can be achieved through art.  Our contact page is also simple. We do ask potential members to provide their name, email. postal code, a password used to gain access to the meetings, an agreement of being respectful, phone number, and we do ask potential members to introduce themselves in a short message. We have had great success thus far and now we want to present this club to the surrounding areas of Kakenstorf to find more people who can use this service.



Deployed site as an example:
https://ui.dev/amiresponsive?url=https://primarypigments.github.io/Primary.Pigments



![screenshot](documentation/mockup.png)




### Colour Scheme


I chose this color scheme because it is easy on the eyes and brings a calming feeling,  I believe my users are looking form a site that are these things and will in turn get them to join, 

As for the background color I decided to use Cssgradient. https://cssgradient.io/
For Website color scheme I used Google http://google.com

I will explain the uses of the various colors below, starting from top to bottom.


The main background color uses a linear-gradient:

```css
linear-gradient(90deg, rgba(240, 239, 239, 1) 0%, rgba(246, 247, 242, 1) 22%, rgba(236, 242, 228, 1) 100%, rgba(246, 247, 242, 1) 100%);
```

- `#272b54` : This is the border color.
- `#272b54` : This is the accent color.
- `#272b54` : This is the main text color.
- `#f6f7f2` : This is used for Icon color.
- `#4d4f47` : This is used for shadow.


When you add a colour to the palette, the URL is dynamically updated, making it easier for you to return back to your colour palette later if needed.


I used [Google](https://www.w3schools.com/colors/colors_picker.asp) to generate my colour palette.

![screenshot](documentation/color/color_272b54.png)
![screenshot](documentation/color/color_f6f7f2.png)
![screenshot](documentation/color/linear_gradient.png)
![screenshot](documentation/color/color_4d4f47.png)

### Typography

**Icons**

As for icons I decided to use for my website [Font Awesome](https://fontawesome.com/) library.

**Fonts**

 I've integrated Google Fonts to find a typeface that compliments the website's aesthetic. For the main text, I've chosen Roboto Mono due to its optimization for readability on screens across a wide variety of devices and reading environments. I've applied with a "sans-serif" fallback.

## User Stories


- As a new site user, I would like to nurtrue my creativity, so that I can better express myself.
- As a new site user, I would like to move forward in my life, so that I can minimize my depression.
- As a new site user, I would like to try a new approch to working through my trauma, so that I can appricate the present moment.
- As a new site user, I would like to help people because I am a psycologist , so that I can find new ways of treating my patince.
- As a new site user, I would like to show my support as the mayor of Kakenstorf, so that I can be involed of the well being of my community.


- As a returning site user, I would like to join the commmunity, so that I can start something new.
- As a returning site user, I would like to share this community to my friends, so that I can have friends who can join me.
- As a returning site user, I would like to look up the send a message to Primary Pigments, so that I can retrieve my password, and join the next meeting.
- As a returning site user, I would like to look at the painting I made, so that I can so share the paintings to my social media.
- As a returning site user, I would like to look at the beautiful paintings again , so that I can build the curage to join.



## Wireframes

 
To follow best practice, wireframes were developed for mobile, tablet, and desktop sizes.
I've used [Balsamiq](https://balsamiq.com/wireframes) to design my site wireframes.

### Desktop Wireframes

<details>
<summary> Click here to see the Desktop Wireframes </summary>

Home
  - ![screenshot](documentation/wireframes/wireframe_desktop_home.png)

About
  - ![screenshot](documentation/wireframes/wireframe_desktop_gallery.png)

Contact
  - ![screenshot](documentation/wireframes/wireframe_desktop_contact.png)

Gallery
  - ![screenshot](documentation/wireframes/wireframe_desktop_confirmation.png)



</details>

### Tablet Wireframes

<details>
<summary> Click here to see the Tablet Wireframes </summary>

Home
  - ![screenshot](documentation/wireframes/wireframe_tablet_home.png)

About
  - ![screenshot](documentation/wireframes/wireframe_tablet_gallery.png)

Contact
  - ![screenshot](documentation/wireframes/wireframe_tablet_contact.png)

Gallery
  - ![screenshot](documentation/wireframes/wireframe_tablet_confirmation.png)


</details>

### Mobile Wireframes

<details>
<summary> Click here to see the Mobile Wireframes </summary>

Home
  - ![screenshot](documentation/wireframes/wireframe_smatphone_home.png)

About
  - ![screenshot](documentation/wireframes/wireframe_smartphone_gallery.png)

Contact
  - ![screenshot](documentation/wireframes/wireframe_smartphone_contact.png)

Gallery
  - ![screenshot](documentation/wireframes/wireframe_smartphone_confirmation.png)

</details>

## Features

### Existing Features

- **Navbar**

    
 The navigation bar allows you the opportunity to prioritize the content you want visitors to read. It also enables you to take your visitor on a journey, from the most important pages.

![screenshot](documentation/navbar.png)

-**Hero image**

- Our hero image adds a personal touch that immediately builds credibility and trust for our brand. Because people are highly visual, having high-quality, fullscreen imagery at the top of your page can help create a positive first impressin.We also added our location to the image so that the users know immediately where we are located.


![screenshot](documentation/hero.png)

- **Social Media Link Bar**

- A Social Media Link Bar helps us increase brand awareness, increase engagement, help grow followers, and increase accessibility.

![screenshot](documentation/social_media.png)

**Contact Form**

- Our contact form is important to the user because it gives them the option to join immediately. This section is also fully tested and sends a confirmation back


![screenshot](documentation/contact_form.png)

**Contact Form Reminder**

- This future is impotant for the user becasue it reminds the user when they forget to fill out one of the sections.

![screenshot](documentation/contact_form_reminder.png)

**Confirmation Page**

-Confirmation page can work as an indicator of successful contact. One of our users may send us a message using the online form. It is also a helpful reminder to keep the password for the in person meetings. 


![screenshot](documentation/confirmation.png)


### Future Features


Link to the Primary Pigment whatsapp group
    This is where special events/guest and up-to-date meetings will go.
- Testominies page
    - this will help those who are unsure to join
- Mental health and Proffonial artist joining and infutmation page
    - This will help those who want to provide a service within the community to ensure safe practices and propper technquiies are being applied.


## Tools & Technologies Used

- [HTML](https://en.wikipedia.org/wiki/HTML) used for the main site content.
- [CSS](https://en.wikipedia.org/wiki/CSS) used for the main site design and layout.
- [CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp) used for an enhanced responsive layout.
- [Git](https://www.atlassian.com/git) used for version control. (`git add`, `git commit`, `git push`)
- [GitHub](https://github.com) used for secure online code storage.
- [GitHub Pages](https://pages.github.com) used for hosting the deployed front-end site.
- [Gitpod](https://gitpod.io) used as a cloud-based IDE for development.


## Testing

For all testing, please refer to the [TESTING.md](TESTING.md) file.

## Deployment

The site was deployed to GitHub Pages. The steps to deploy are as follows:

- In the [GitHub repository](https://github.com/primarypigments/primary.pigments), navigate to the Settings tab 
- From the source section drop-down menu, select the **Main** Branch, then click "Save".
- The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://primarypigments.github.io/Primary.Pigments)

### Local Deployment

This project can be cloned or forked in order to make a local copy on your own system.

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://github.com/primarypigments/primary.pigments) 
2. Locate the Code button above the list of files and click it 
3. Select if you prefer to clone using HTTPS, SSH, or GitHub CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash or Terminal
5. Change the current working directory to the one where you want the cloned directory
6. In your IDE Terminal, type the following command to clone my repository:
	- `git clone https://github.com/primarypigments/primary.pigments.git`
7. Press Enter to create your local clone.

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/primarypigments/primary.pigments)

Please note that in order to directly open the project in Gitpod, you need to have the browser extension installed.
A tutorial on how to do that can be found [here](https://www.gitpod.io/docs/configure/user-settings/browser-extension).

#### Forking

By forking the GitHub Repository, we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original owner's repository.
You can fork this repository by using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/primarypigments/primary.pigments)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!

### Local VS Deployment

The only major difference i have see is when i the site is live using an apple product is the menu on the contact page turns blue.


## Credits

### Content

| Source | Location | Notes |
| --- | --- | --- |
| [Markdown Builder](https://tim.2bn.dev/markdown-builder) | README and TESTING | tool to help generate the Markdown files |
| [Chris Beams](https://chris.beams.io/posts/git-commit) | version control | "How to Write a Git Commit Message" |
| [Code Institute](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LRFX101+2023_Q2/courseware/e805068059af42af87681032aa64053f/7525117e5cd144daa2a7b0c57843bbee/) | Setting up the basic HTML structure: Part 1 | 
| [Sentry](https://sentry.io/answers/how-do-i-auto-resize-an-image-to-fit-a-div-container/#:~:text=To%20fix%20this%2C%20we%20can,contain%E2%80%9D%20and%20%E2%80%9Ccover%E2%80%9D.) | Resize Image |
| [StackOverflow](https://stackoverflow.com/questions/16670931/hide-scroll-bar-but-while-still-being-able-to-scroll) |Hide Scrollbar |
| [W3Schools](https://www.w3schools.com/howto/howto_css_custom_scrollbar.asp) | entire site | how to custom scrollbar |
| [YouTube](https://www.youtube.com/watch?v=BlSp2ertu_8) | Hide Scrollbar | tutorial hide scrollbar |
| [Images](https://www.bing.com/create) | entire site | used for creating images |
| [Content Design](https://tobiasahlin.com/blog/common-flexbox-patterns/#alternating-grid) | gallery page | alternating gallery |
| [Page and Color Design](https://www.youtube.com/watch?v=KAG5wNPdoTw) | background | where I leard about Gradient color |
| [Layout Design](https://www.godaddy.com/resources/skills/how-to-build-a-3-page-website) | entire site | used for gathering ideas |
| [Layout Design](https://en.99designs.de/web-design/contests/page-website-template-46414) | entite site | used for gathering ideas |
| [RBGA Color Picker](https://rgbacolorpicker.com/) used for styleing content.
| [CSS Color Picker](https://www.google.com/) | entire site | used for picking color or fonts and background |
| [Gradient Color Picker](https://cssgradient.io/) | background | used for backround color |
| [CSS SCROLLBAR](http://youtube.com) | entire site | used to learn how to hide scrollbars |
| [Html Responsive Form](https://www.w3schools.com/howto/howto_css_responsive_form.asp) | contact pgae | Used for the basic outline for a form |
| [Input type password](https://www.w3schools.com/tags/att_input_type_password.asp) | contact page | Used for putting a passwpord in my form |
| [Styling Form](https://www.youtube.com/watch?v=okbByPWS1Xc) | contact form | Used for ideas and css styling |
| [Transitions](https://www.w3schools.com/css/css3_transitions.asp) | contact form | Used to for transitions for form |
| [Image Converter](http://https://www.freeconvert.com/webp-converter) | gallery page | Used to covert images to webp |
| [Typing page content](https://www.google.com/docs/about/) | entire site | Used for spell check for the text |

### Media

| Source | Location | Type | Notes |
| --- | --- | --- | --- |
| [Favicon Generator](https://realfavicongenerator.net/favicon_result?file_id=p1hggvtne11k221od61hr51qbalja6) | entire site | image | favicon on all pages |
| [Hero Image](https://dribbble.com/shots/19877346-Depression/attachments/14975065?mode=media) | entire site | image | hero image for home page |
| [Website Images](https://www.bing.com/images/create?FORM=GENILP) | enitre site | images | all images for website except Hero image, can not provide every link to all the images i used do to the images are tied to my peronal microsoft account |

### Acknowledgements

- I would like to thank my awesome Code Institute mentor I really appriciate all that he has done for me, [Tim Nelson](https://github.com/TravelTimN) for their support throughout the development of this project.
- I would like to thank the [Code Institute](https://codeinstitute.net) tutor team for their assistance with troubleshooting and debugging some project issues.
- I would like to thank the [Code Institute Slack community](https://code-institute-room.slack.com) for the moral support; it kept me going during periods of self doubt and imposter syndrome.
- I would like to thank my partner Coleen and my 3 children Lucille Mo and Octiavio, for believing in me, and allowing me to make this transition into software development.
- I would like to thank Agentur für Arbeit, for supporting me in my career development change towards becoming a software developer.


# Testing

Return back to the [README.md](README.md) file.



The Primary Pigments website has met the objectives set by all parties involved. It's responsive on various screen sizes, ensuring clean and crisp images without excessive empty space. Users can easily navigate and contact us through the contact form or social media. The content is concise, and the design is uncluttered, providing a user-friendly experience.


## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

The URL will look something like this:

- https://validator.w3.org/nu/?doc=https%3A%2F%2Fprimarypigments.github.io%2Fprimary.pigments%2Findex.html


| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fprimarypigments.github.io%2Fprimary.pigments%2Findex.html) | ![screenshot](documentation/html_validation_index.png) | Consider using the h1 element as a top-level heading only warning |

| Gallery | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fprimarypigments.github.io%2FPrimary.Pigments%2Findex.html) | ![screenshot](documentation/html_validation_gallery.png) | obsolete iframe warnings |

| Contact | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fprimarypigments.github.io%2FPrimary.Pigments%2Fgallery.html) | ![screenshot](documentation/html_validation_contact.png) | Section lacks heading warning |


| Confirmation | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fprimarypigments.github.io%2FPrimary.Pigments%2Fconfirmation.html%3Ffirst_name%3Db%26last_name%3Db%26password%3Db%26confirm_password%3Db%26interest_select%3DCreativity%26email_address%3Db%26phone_number%3Db%26about%3Db%26postal_code%3Db%26agreed%3Don) | ![screenshot](documentation/html_validation_confirmation.png) | Section lacks heading warning |
|


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Home | [W3C](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fprimarypigments.github.io%2FPrimary.Pigments%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![screenshot](documentation/css_validation_home.png) |No Error Found. |

| Gallery | [W3C](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fprimarypigments.github.io%2FPrimary.Pigments%2Fgallery.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![screenshot](documentation/css_validation_gallery.png) |No Error Found.|

| Contact | [W3C](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fprimarypigments.github.io%2FPrimary.Pigments%2Fcontact.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![screenshot](documentation/css_validation_contact.png) | No Error Found. |


| Confirmation | [W3C](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fprimarypigments.github.io%2FPrimary.Pigments%2Fconfirmation.html%3Ffirst_name%3Ds%26last_name%3Ds%26password%3Ds%26confirm_password%3Ds%26interest_select%3DSelf%2BHelp%26email_address%3Ds%26phone_number%3Ds%26about%3Ds%26postal_code%3Ds%26agreed%3Don&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![screenshot](documentation/css_validation_confirmation.png) | No Error Found. |
|

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fprimarypigments.github.io%2Fprimary.pigments) | ![screenshot](documentation/css_validation_style.png) | Pass: No Errors |


## Browser Compatibility

Recommended browsers to consider:
- [Chrome](https://www.google.com/chrome)
- [Edge](https://www.microsoft.com/edge)
- [Safari](https://support.apple.com/downloads/safari)
- [Opera](https://www.opera.com/download)

Sample browser testing documentation:

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | About | Contact | etc | Notes |
| --- | --- | --- | --- | --- | --- |
| ![Chrome](https://raw.githubusercontent.com/TravelTimN/markdown-builder/main/assets/img/chrome.png) | ![screenshot](documentation/browser/browser_chrome_home.png) | ![screenshot](documentation/browser/browser_chrome_gallery.png) | ![screenshot](documentation/browser/browser_chrome_contact.png) | ![screenshot](documentation/browser/browser_chrome_confirmation.png) | Works as expected |
| ![Firefox](https://raw.githubusercontent.com/TravelTimN/markdown-builder/main/assets/img/firefox.png) | ![screenshot](documentation/browser-firefox-home.png) | ![screenshot](documentation/browser-firefox-about.png) | ![screenshot](documentation/browser-firefox-contact.png) | ![screenshot](documentation/browser-firefox-etc.png) | Works as expected |
| ![Edge](https://raw.githubusercontent.com/TravelTimN/markdown-builder/main/assets/img/edge.png) | ![screenshot](documentation/browser/browser_edge_home.png) | ![screenshot](documentation/browser/browser_edge_gallery.png) | ![screenshot](documentation/browser/browser_edge_contact.png) | ![screenshot](documentation/browser/browser_edge_confirmation.png) | Works as expected |
| ![Safari](https://raw.githubusercontent.com/TravelTimN/markdown-builder/main/assets/img/safari.png) | ![screenshot](documentation/browser/browser_safari_home.png) | ![screenshot](documentation/browser/browser_safari_gallery.png) | ![screenshot](documentation/browser/browser_safari_contact.png) | ![screenshot](documentation/browser/browser_safari_confirmation.png) | Minor CSS differences |
| ![Opera](https://raw.githubusercontent.com/TravelTimN/markdown-builder/main/assets/img/opera.png) | ![screenshot](documentation/browser/browser_opera_home.png) | ![screenshot](documentation/browser/browser_opera_gallery.png) | ![screenshot](documentation/browser/browser_opera_contact.png) | ![screenshot](documentation/browser/browser_opera_confirmation.png) | Minor differences |


## Responsiveness


I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | About | Contact | etc | Notes |
| --- | --- | --- | --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/responsive_home_mobile.png) | ![screenshot](documentation/responsive_gallery_mobile.png) | ![screenshot](documentation/responsive_contact_mobile.png) | ![screenshot](documentation/responsive_confirmation_mobile.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/responsive_home_tablet.png) | ![screenshot](documentation/responsive_gallery_tablet.png) | ![screenshot](documentation/responsive_contact_tablet.png) | ![screenshot](documentation/responsive_confirmation_tablet.png) | Works as expected |
| Desktop | ![screenshot](documentation/responsive_home_desktop.png) | ![screenshot](documentation/responsive_gallery_desktop.png) | ![screenshot](documentation/responsive_contact_desktop.png | ![screenshot](documentation/responsive_confirmation_desktop.png) | Works as expected |

| Ipad Pro | ![screenshot](documentation/responsive_home_ipadpro.png) | ![screenshot](documentation/responsive_gallery_ipadpro.png) | ![screenshot](documentation/responsive_contact_ipadpro.png) | ![screenshot](documentation/responsive_confirmation_ipadpro.png) | Works as expected |


## Lighthouse Audit


I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse_home_mobile.png) | ![screenshot](documentation/lighthouse_home_desktop.png) | Some minor warnings |
| Gallery | ![screenshot](documentation/lighthouse_gallery_mobile.png) | ![screenshot](documentation/lighthouse_gallery_desktop.png) | Some minor warnings |
| Contact | ![screenshot](documentation/lighthouse_contact_mobile.png) | ![screenshot](documentation/lighthouse_contact_desktop.png) | Slow response time due to large images |
| COnfirmation | ![screenshot](documentation/lighthouse_confirmation_mobile.png) |  | COnfirmation | ![screenshot](documentation/lighthouse_confirmation_desktop.png) |


## User Story Testing

⚠️⚠️⚠️⚠️⚠️ START OF NOTES (to be deleted) ⚠️⚠️⚠️⚠️⚠️

Testing user stories is actually quite simple, once you've already got the stories defined on your README.

Most of your project's **features** should already align with the **user stories**,
so this should as simple as creating a table with the user story, matching with the re-used screenshot
from the respective feature.

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to nurtrue my creativity, so that I can better express myself. | ![screenshot](documentation/site_user_creativity.png) |
|As a new site user, I would like to help people because I am a psycologist , so that I can find new ways of treating my patince. | ![screenshot](documentation/site_user_psycologist.png) |
| As a new site user, I would like to try a new approch to working through my trauma, so that I can appricate the present moment.| ![screenshot](documentation/site_user_approch.png/feature03.png) |
| As a returning site user, I would like to share this community to my friends, so that I can have friends who can join me. | ![screenshot](documentation/social_media.png) |
| As a returning site user, I would like to look at the painting I made, so that I can so share the paintings to my social media. | ![screenshot](documentation/site_user_share.png) |
| As a returning site user, I would like to look at the beautiful paintings again , so that I can build the curage to join. | ![screenshot](documentation/site_user_paintings.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/feature07.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/feature08.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/feature09.png) |
| repeat for all remaining user stories | x |

## Bugs

⚠️⚠️⚠️⚠️⚠️ START OF NOTES (to be deleted) ⚠️⚠️⚠️⚠️⚠️

This section is primarily used for JavaScript and Python applications,
but feel free to use this section to document any HTML/CSS bugs you might run into.

It's very important to document any bugs you've discovered while developing the project.
Make sure to include any necessary steps you've implemented to fix the bug(s) as well.

**PRO TIP**: screenshots of bugs are extremely helpful, and go a long way!

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

- JS Uncaught ReferenceError: `foobar` is undefined/not defined

    ![screenshot](documentation/bug01.png)

    - To fix this, I _____________________.

- JS `'let'` or `'const'` or `'template literal syntax'` or `'arrow function syntax (=>)'` is available in ES6 (use `'esversion: 11'`) or Mozilla JS extensions (use moz).

    ![screenshot](documentation/bug02.png)

    - To fix this, I _____________________.

- Python `'ModuleNotFoundError'` when trying to import module from imported package

    ![screenshot](documentation/bug03.png)

    - To fix this, I _____________________.

- Django `TemplateDoesNotExist` at /appname/path appname/template_name.html

    ![screenshot](documentation/bug04.png)

    - To fix this, I _____________________.

- Python `E501 line too long` (93 > 79 characters)

    ![screenshot](documentation/bug04.png)

    - To fix this, I _____________________.

## Unfixed Bugs

⚠️⚠️⚠️⚠️⚠️ START OF NOTES (to be deleted) ⚠️⚠️⚠️⚠️⚠️

You will need to mention unfixed bugs and why they were not fixed.
This section should include shortcomings of the frameworks or technologies used.
Although time can be a big variable to consider, paucity of time and difficulty understanding
implementation is not a valid reason to leave bugs unfixed.

If you've identified any unfixed bugs, no matter how small, be sure to list them here.
It's better to be honest and list them, because if it's not documented and an assessor finds the issue,
they need to know whether or not you're aware of them as well, and why you've not corrected/fixed them.

Some examples:

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

- 

- For PP3, when using a helper `clear()` function, any text above the height of the terminal does not clear, and remains when you scroll up.

    ![screenshot](documentation/unfixed-bug02.png)

    - Attempted fix: I tried to adjust the terminal size, but it only resizes the actual terminal, not the allowable area for text.


- When validating HTML with a semantic `section` element, the validator warns about lacking a header `h2-h6`. This is acceptable.

    ![screenshot](documentation/unfixed_bug_section.png)

    - Attempted fix: this is a known warning and acceptable, and my section doesn't require a header since it's dynamically added via JS.

    - When validating HTML with a semantic `H1` element, the validator warns to Consider using the h1 element as a top-level heading only`. This is acceptable.

    ![screenshot](documentation/unfixed_bug_section.png)

    - Attempted fix:  this is a known warning and acceptable, and my section doesn't require a changing the H1 header due to the size of the heading is appropriate for the intended use.
 
 - When validating HTML with a semantic `section` element, the validator warns about lacking a header `h2-h6`. This is acceptable.

    ![screenshot](documentation/unfixed_bug_h2.png)

    - Attempted fix: this is a known warning and acceptable, and my section doesn't require a header since it's a contact form.
-
⚠️⚠️⚠️⚠️⚠️ START OF NOTES (to be deleted) ⚠️⚠️⚠️⚠️⚠️

If you legitimately cannot find any unfixed bugs or warnings, then use the following sentence:

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

There are no remaining bugs that I am aware of.
 


[def]: https://cssgradient.io/