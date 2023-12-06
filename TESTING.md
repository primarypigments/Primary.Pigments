# Testing
​
Return back to the [README.md](README.md) file.
​

The Primary Pigments website has met the objectives set by all parties involved. It's responsive on various screen sizes, ensuring clean and crisp images without excessive empty space. Users can easily navigate and contact us through the contact form or social media. The content is concise, and the design is uncluttered, providing a user-friendly experience.
​
## Code Validation
​
### HTML
​
I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.
​
The URL will look something like this:
​
- https://validator.w3.org/nu/?doc=https%3A%2F%2Fprimarypigments.github.io%2FPrimary.Pigments%2Findex.html
​
​
| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fprimarypigments.github.io%2FPrimary.Pigments%2Findex.html) | ![screenshot](documentation/html_validation_index.png) | Consider using the h1 element as a top-level heading only warning |
| Gallery | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fprimarypigments.github.io%2FPrimary.Pigments%2Findex.html) | ![screenshot](documentation/html_validation_gallery.png) | obsolete iframe warnings |
| Contact | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fprimarypigments.github.io%2FPrimary.Pigments%2Fgallery.html) | ![screenshot](documentation/html_validation_contact.png) | Section lacks heading warning |
| Confirmation | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fprimarypigments.github.io%2FPrimary.Pigments%2Fconfirmation.html%3Ffirst_name%3Db%26last_name%3Db%26password%3Db%26confirm_password%3Db%26interest_select%3DCreativity%26email_address%3Db%26phone_number%3Db%26about%3Db%26postal_code%3Db%26agreed%3Don) | ![screenshot](documentation/html_validation_confirmation.png) | Section lacks heading warning |
|
​
​
### CSS
​
I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.
​
| Entire Sire | [W3C](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fprimarypigments.github.io%2FPrimary.Pigments%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![screenshot](documentation/css_validation_home.png) | No Error Found. | |Known Warning  ::-webkit-scrollbar is a vendor extended pseudo-element |
​
​
## Browser Compatibility
​
Recommended browsers to consider:
- [Chrome](https://www.google.com/chrome)
- [Edge](https://www.microsoft.com/edge)
- [Safari](https://support.apple.com/downloads/safari)
- [Opera](https://www.opera.com/download)
​
- I've tested my deployed project on multiple browsers to check for compatibility issues.
​
| Browser | Home | Gallery | Contact | Confirmation | Notes |
| --- | --- | --- | --- | --- | --- |

| Chrome | ![screenshot](documentation/browser/browser_chrome_home.png) | ![screenshot](documentation/browser/browser_chrome_gallery.png) | ![screenshot](documentation/browser/browser_chrome_contact.png) | ![screenshot](documentation/browser/browser_chrome_confirmation.png) | Works as expected |

| Edge | ![screenshot](documentation/browser/browser_edge_home.png) | ![screenshot](documentation/browser/browser_edge_gallery.png) | ![screenshot](documentation/browser/browser_edge_contact.png) | ![screenshot](documentation/browser/browser_edge_confirmation.png) | Works as expected |

| Safari | ![screenshot](documentation/browser/browser_safari_home.png) | ![screenshot](documentation/browser/browser_safari_gallery.png) | ![screenshot](documentation/browser/browser_safari_contact.png) | ![screenshot](documentation/browser/browser_safari_confirmation.png) | Minor CSS differences |

| Opera | ![screenshot](documentation/browser/browser_opera_home.png) | ![screenshot](documentation/browser/browser_opera_gallery.png) | ![screenshot](documentation/browser/browser_opera_contact.png) | ![screenshot](documentation/browser/browser_opera_confirmation.png) | Minor differences |
​
## Responsiveness
​
I've tested my deployed project on multiple devices to check for responsiveness issues.
​
| Device | Home | Gallery | Contact | Confirmation | Notes |
| --- | --- | --- | --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/responsive_home_mobile.png) | ![screenshot](documentation/responsive_gallery_mobile.png) | ![screenshot](documentation/responsive_contact_mobile.png) | ![screenshot](documentation/responsive_confirmation_mobile.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/responsive_home_tablet.png) | ![screenshot](documentation/responsive_gallery_tablet.png) | ![screenshot](documentation/responsive_contact_tablet.png) | ![screenshot](documentation/responsive_confirmation_tablet.png) | Works as expected |
| Desktop | ![screenshot](documentation/responsive_home_desktop.png) | ![screenshot](documentation/responsive_gallery_desktop.png) | ![screenshot](documentation/responsive_contact_desktop.png) | ![screenshot](documentation/responsive_confirmation_desktop.png) | Works as expected |
| Ipad Pro | ![screenshot](documentation/responsive_home_ipadpro.png) | ![screenshot](documentation/responsive_gallery_ipadpro.png) | ![screenshot](documentation/responsive_contact_ipadpro.png) | ![screenshot](documentation/responsive_confirmation_ipadpro.png) | Works as expected |
​
## Lighthouse Audit
​
I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.
​
| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse_home_mobile.png) | ![screenshot](documentation/lighthouse_home_desktop.png) | Some minor warnings |
| Gallery | ![screenshot](documentation/lighthouse_gallery_mobile.png) | ![screenshot](documentation/lighthouse_gallery_desktop.png) | Some minor warnings |
| Contact | ![screenshot](documentation/lighthouse_contact_mobile.png) | ![screenshot](documentation/lighthouse_contact_desktop.png) | Slow response time due to large images |
| Confirmation | ![screenshot](documentation/lighthouse_confirmation_mobile.png) |![screenshot](documentation/lighthouse_confirmation_desktop.png) | Some minor warnings |  
​
## User Story Testing
​

| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to nurture my creativity, so that I can better express myself. | ![screenshot](documentation/site_user_creativity.png) |
|As a new site user, I would like to help people because I am a psychologist , so that I can find new ways of treating my patience. | ![screenshot](documentation/site_user_psycologist.png) |
| As a new site user, I would like to try a new approach to working through my trauma, so that I can appreciate the present moment.| ![screenshot](documentation/site_user_approch.png) |
| As a returning site user, I would like to share this community with my friends, so that I can have friends who can join me. | ![screenshot](documentation/social_media.png) |
| As a returning site user, I would like to look at the paintings I made, so that I can share the paintings on my social media. | ![screenshot](documentation/site_user_share.png) |
| As a returning site user, I would like to look at the beautiful paintings again , so that I can build the courage to join. | ![screenshot](documentation/site_user_paintings.png) |
|As a site administrator, I should be able to use the navbar, so that I can navigate through the other pages on the website. | ![screenshot](documentation/navbar.png) |
| As a site administrator, I should be able to click on an image on the gallery page, so that I can see the images in an enlarged view. | ![screenshot](documentation/gallery_view.png) |
| As a site administrator, I should be able to be directed to our social media pages, so that I can ensure our community grows. | ![screenshot](documentation/social_media.png) |


## Bugs
​
## Unfixed Bugs
​
- For PP3, when using a helper `clear()` function, any text above the height of the terminal does not clear, and remains when you scroll up.
​
    ![screenshot](documentation/unfixed-bug02.png)
​
    - Attempted fix: I tried to adjust the terminal size, but it only resizes the actual terminal, not the allowable area for text.
​
​
- When validating HTML with a semantic `section` element, the validator warns about lacking a header `h2-h6`. This is acceptable.
​
    ![screenshot](documentation/unfixed_bug_section.png)
​
    - Attempted fix: this is a known warning and acceptable, and my section doesn't require a header since it's dynamically added via JS.
​
    - When validating HTML with a semantic `H1` element, the validator warns to Consider using the h1 element as a top-level heading only`. This is acceptable.
​
    ![screenshot](documentation/unfixed_bug_section.png)
​
    - Attempted fix:  this is a known warning and acceptable, and my section doesn't require a changing the H1 header due to the size of the heading is appropriate for the intended use.
 
 - When validating HTML with a semantic `section` element, the validator warns about lacking a header `h2-h6`. This is acceptable.
​
    ![screenshot](documentation/unfixed_bug_h2.png)
​
    - Attempted fix: this is a known warning and acceptable, and my section doesn't require a header since it's a contact form.
-
[def]: https://cssgradient.io/

