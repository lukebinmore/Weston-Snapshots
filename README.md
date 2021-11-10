# Weston Snapshots!

**Weston Snapshots** is a site aimed at those based in Weston-super-Mare with a passion or interest in photography, looking to join a club/community of people with the same or similar interests.

The purpose of the site is to provide a point of contact for the club/community for new comers and interested members, as well as to act as an advertisement and informational page regarding the group and it's activities.

![AmIResponsive](media/weston-snapshots-mockup.png)

## Features

### Existing Features

* __Nagigation Menu__
  * The navigation menu can be found on every page, and provides the user with the ability to easily navigate to any page on the site.
  * Site pages included: Home, Gallery, Members, Join Us!
  * This feature is responsive in design, and will remain at the top of the page when scrolling unless on small screens.

![Navigation Menu](media/weston-snapshots-navigation.png)

* __Page Heading__
  * The page heading is present on every page, and provides some subtext to the current page.
  * This feature includes:
    * A panorama image showing off some members photos of Weston-super-Mare's seafront.
    * A page heading.
    * A short and interesting phrase relating to the page content.

![Page Heading](media/weston-snapshots-page-heading.png)

* __Footer__
  * The footer features provides quick access to social media sites relevant to Weston Snapshots.
  * Social sites included:
    * Facebook
    * Twitter
    * Youtube
    * Instagram
  * This feature encourages the user to keep up with the social offerings of the Weston Snapshots club/community.

![Footer](media/weston-snapshots-footer.png)

* __Club Ethos__
  * The club ethos section of the home page provides the user with some information about the club/community, and what they are about.
  * The aim of this section is to inform the user of what kinds of people make up the club/community, What they do when they meet, and how to join the club/community.

![Club Ethos](media/weston-snapshots-club-ethos.png)

* __Club Schedule__
  * The schedule section on the home page outlines the normal schedule of the club/community, demonstrating when they meet and what they do on those days.
  * This section should be updated if/when these times/activities change

![Schedule](media/weston-snapshots-schedule.png)

* __Gallery__
  * The gallery has been implemented to provide a space to show off photos taken by members, and to show interested members what subjects are usually on the end of the cameras.
  * This feature is valuble for the user as it provides the user with some scope of the following:
    * The capability of the current members
    * The amount they can learn and improve with the help of the group
    * The beautifull sites and locations in Weston-super-Mare that are ready and waiting to be photographed

![Gallery](media/weston-snapshots-schedule.png)

* __Members Page__
  * The members page shows the names and pictures of the current members (Those that have agreed to be included).
  * This is valuble for the user, as it shows the diversity in age, gender and backgrounds of the community, showing the club/community is inclusive of everyone.

![Members](media/weston-snapshots-members.png)

* __Join Us Page__
  * The signup page provides the user with a form to fill in to join the community and get started on their photography journey.
  * On completing the form, the user is taken to a thanks page that let's them know what will happen next, and thank them for joining.

![Join Us Form](media/weston-snapshots-joinus-form.png)
![Join Us Thanks](media/weston-snapshots-joinus-thanks.png)

### Future Features

* __Gallery Image Slider__
  * This possible feature would present the user with an image scroller when clicking on an image in the gallery.
  * This would allow the user to view images in a larger format, and allow them to scroll through the images one by one.

* __Schedule Calendar Link__
  * This possible feature would offer the user an iCal link to the schedule, allowing them to add it to their own calendars with an updating link.

* __Gallery Members Filter__
  * This would allow user's to filter the gallery to photos taken by a specific member.

## Testing

### Automated Testing

#### [Chrome DevTools - Lighthouse Report](https://developer.chrome.com/docs/devtools/)

##### Summary: 

* Desktop:
  * All pages have reduced performance score due to image file sizes and format.
    * Improved by compressing and converting all images to .jpg.
  * All pages have 3% loss on accessibility score, due to home icon link in top left corner not having decernable text.
    * Fixed by adding aria-label to icon.
  * All pages have a best practice score of 100.
  * All pages have an SEO score of 100.

* Mobile:
  * All pages have reduced performance score due to image file sizes.
    * Improved with futher compression.
  * Join Us Thanks page has drastically reduced performance score due to large icon.
    * Fixed by replacing icon with image.
  * All pages have an accessibility score of 100.
  * All pages have a best practice score of 100.
  * All pages have an SEO score of 100.

<details>
<summary>View Results</summary>

* ##### Desktop Mode:

###### Home
![Chrome Devtools - Desktop Home](media/weston-snapshots-chromedev-desktop-home.png)
###### Gallery
![Chrome Devtools - Desktop Gallery](media/weston-snapshots-chromedev-desktop-gallery.png)
###### Members
![Chrome Devtools - Desktop Members](media/weston-snapshots-chromedev-desktop-members.png)
###### Join Us - Form
![Chrome Devtools - Desktop Join Us Form](media/weston-snapshots-chromedev-desktop-joinus-form.png)
###### Join Us - Thanks
![Chrome Devtools - Desktop Join Us Thanks](media/weston-snapshots-chromedev-desktop-joinus-thanks.png)

* ##### Mobile Mode:

###### Home
![Chrome Devtools - Mobile Home](media/weston-snapshots-chromedev-desktop-home.png)
###### Gallery
![Chrome Devtools - Mobile Gallery](media/weston-snapshots-chromedev-desktop-gallery.png)
###### Members
![Chrome Devtools - Mobile Members](media/weston-snapshots-chromedev-desktop-members.png)
###### Join Us - Form
![Chrome Devtools - Mobile Join Us Form](media/weston-snapshots-chromedev-desktop-joinus-form.png)
###### Join Us - Thanks
![Chrome Devtools - Mobile Join Us Thanks](media/weston-snapshots-chromedev-desktop-joinus-thanks.png)

</details>

#### [Chrome DevTools - Lighthouse Report](https://developer.chrome.com/docs/devtools/)

##### Summary:

<details>
<summary>View Results</summary>

</details>

#### Validator Testing

##### Summary:

All HTML and CSS pages passed validators with no errors or warnings.

<details>
<summary>View Results</summary>

* HTML
  * [index.html](https://lukebinmore.github.io/Weston-Snapshots/index.html)
    * No errors or warnings were returned when passing through the official [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Flukebinmore.github.io%2FWeston-Snapshots%2Findex.html)
  * [gallery.html](https://lukebinmore.github.io/Weston-Snapshots/pages/gallery.html)
    * No errors or warnings were returned when passing through the official [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Flukebinmore.github.io%2FWeston-Snapshots%2Fpages%2Fgallery.html)
  * [members.html](https://lukebinmore.github.io/Weston-Snapshots/pages/members.html)
    * No errors or warnings were returned when passing through the official [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Flukebinmore.github.io%2FWeston-Snapshots%2Fpages%2Fmembers.html)
  * [joinus-form.html](https://lukebinmore.github.io/Weston-Snapshots/pages/joinus-form.html)
    * No errors or warnings were returned when passing through the official [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Flukebinmore.github.io%2FWeston-Snapshots%2Fpages%2Fjoinus-form.html)
  * [joinus-thanks.html](https://lukebinmore.github.io/Weston-Snapshots/pages/joinus-thanks.html)
    * No errors or warnings were returned when passing through the official [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Flukebinmore.github.io%2FWeston-Snapshots%2Fpages%2Fjoinus-thanks.html)

* CSS
  * [index.html](https://lukebinmore.github.io/Weston-Snapshots/index.html)
    * No errors or warnings were returned when passing through the official [(Jigsaw) Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Flukebinmore.github.io%2FWeston-Snapshots%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
  * [gallery.html](https://lukebinmore.github.io/Weston-Snapshots/pages/gallery.html)
    * No errors or warnings were returned when passing through the official [(Jigsaw) Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Flukebinmore.github.io%2FWeston-Snapshots%2Fpages%2Fgallery.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
  * [members.html](https://lukebinmore.github.io/Weston-Snapshots/pages/members.html)
    * No errors or warnings were returned when passing through the official [(Jigsaw) Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Flukebinmore.github.io%2FWeston-Snapshots%2Fpages%2Fmembers.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
  * [joinus-form.html](https://lukebinmore.github.io/Weston-Snapshots/pages/joinus-form.html)
    * No errors or warnings were returned when passing through the official [(Jigsaw) Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Flukebinmore.github.io%2FWeston-Snapshots%2Fpages%2Fjoinus-form.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
  * [joinus-thanks.html](https://lukebinmore.github.io/Weston-Snapshots/pages/joinus-thanks.html)
    * No errors or warnings were returned when passing through the official [(Jigsaw) Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Flukebinmore.github.io%2FWeston-Snapshots%2Fpages%2Fjoinus-thanks.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

</details>

### Manual Testing



### Unfixed Bugs





## Deployment

Write about how the project has been deployed to GitHub, and how this was done.

Include link to live site.

## Credits

Provide credit where neccessary. I've written everything myself, so it's mainly content such as images.

Create a subsection for each type of content. E.G. Content on the site, Media e.c.t.