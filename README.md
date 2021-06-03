
# Milestone Project 1

## Purpose 

The purpose of this site is to complete the first Milestone Project for the Code Institute's Full Stack Developer course and can can be found [here](https://cobobc.github.io/milestone_project_fob/index.html).

## FOB Beats Responsive website

![FOB site overview](assets/images/read_me/read_me_img.png)

Fionn O'Brien (FOB) requested a website to showcase his music production business. FOB requires a respnsive website to provide 
users with information about his music production, mastering, beat making,
and songwriting service. Coupled with a portal so potential customer can be directed to buy his beats. This store portal is very important as FOB looks to increase his sales.


## User Experience (UX)

### The users

#### First Time users

The first time user wants the following:

*   View clear and concise content on mobile.
*   Learn and understand what FOB Beats is about.
*   Understand the services offered.
*   Seemlessly navigated through the 5 pages of the site.
*   Easily connect with FOBs social platforms.

#### Returning Users

The returning user wants the following:

*   Purchase FOBs beats through the external link portal on the site.
*   Watch and take notes on FOBs step by step beat making tutorial.
*   Book a recording seesion via the contact form.

#### Frequent Users

The frequent user wants the following:

*   Use FOBs credit list as a continuous muscial source
*   To see when new beats arrive on the site

### Design

#### Colour Scheme

The main colours used are #343254 (purple), #f0b2d6, and floralwhite. These colours go well
with the FOB Beat logo and the collection of images seen in the gallery page and the main image on the home page.

#### Font

The **Quicksand** font is used through the whole site.

#### Imagery

FOB Beats has been in business for over 3 years so it has own logo and a great collection of photograpy which FOB has granted permission to use for this project.

#### Wireframes

For complete wireframes see this [PDF](assets/images/read_me/Wireframes_draft.pdf)


### Limitations

There were two limitations faced with no JavaScript funtionality, and they are:

*   The audio control used on the Music page could not be styled resulting in the basic design seen on that page.
*   The contact form does not send email requests.


## Features 

The features througout the site are to have a minimalist approach - less is more.

### Existing Features

*   Navigation bar

    *   Featured identically on every page that contains links to the Home, Music, Credits, Gallery, and Contact pages. The title in the nav bar provides the user with a link
        back to the home page. 
    *   The navigation options becomes contained in a responsive Bootstrap burger icon for tablet and mobile devices that provides the page option in a dropdown form. 

*   Footer

    *   Featured identically on every page and contains external links to FOBs main social platforms. Each external link has the attribute of target="_blank" which
        opens the link in a new tab, keeping the user on the site and allowing for seemless UX.
    *   The icons used a are taken from font-awesome.

*   Home page

    *   Provide a striking image of FOB, the logo and an immediate button to entice the user to visit the external store to buy FOBs beats. The image provides a professional look.
    *   Contains an About paragraph to introduce FOB.
    *   Provides short paragraphs to describe the Music and Credits page with Discover More buttons to entice the user click into those pages.
    *   The FOR SALE sign will be in Bootstap jumbtron form to draw in the user. This feature wil disapear for mobile via bootstraps d-none d-sm-inline attribute and the SHOP NOW 
        button alone will be enough to entice the user.

*   Music page

    *   The idea of this page is to provde beat (audio) samples by FOB, a shop portal button (similar to the home page) that brings the user to the site where they
        see all of FOBs beats and buy the music.
    *   The layout of this page flow top to bottom - the user start at the top and can play the smaple audio beats provided. As the user scrolls to the bottom of the samples
        they immediately have an option to go and buy the beats. The bottom of the page then provide a tutorial video about FOB makes his beats.
        This embeded youtube video give a good insight into the man and the process - making for well rounded UX.
    *   The background colour gradient from the purple to the pink then back to the purple at the bottom accompanies the top to bottom feel of the page.
    *   The audio sample section will use Bootstaps row grid system. Desktop and tablet will appear as two rows - image row and audio row. For mobile both willl be centered and
        the audio controls will position below their respective image.

*   Credits page

    *   This page will provide the user with FOBs credits/discograpy i.e. all the artist he has worked with. This information is very important to any musci producer
        because the user can see what FOB has produced and could potentially produce with a potentially intereested user.
    *   The first four artist are FOBs biggest and most successful to the date. The artists pictures and tracks FOB has produced or mastered for them will be given.
        The user then has the option to check out more of the artist via the their social platform external links which are displayed as icons (via font-awesome).
    *   The main artist section will use Bootstaps row grid system. Desktop and tablet will appear as two rows - image row and tracks produced by FOB row. For mobile both willl
        be centered and the tracks produced divs will position below their respective image.
    *   The page will provide a collasable list - provided by Bootstrap - for the user to open and view FOBs entire credit list. The each artist on the list will be an external link a relevant social 
        plaform of their own.

*   Gallery

    *   Provides the user with supporting photograph images of FOB and his style.
    *   The photos are professionally taken and provide professional look.
    *   Bootstraps grid system is used here - For desktop the photo display in three rows. For tablet the photos display in two rows.
        The photos are displayed in one row for mobile.

*   Contact

    *   Provide the user with a contact form to contact FOB to book recording session or just general queries.


### Features Left to Implement

*   Final decision on colour code to be made. The pink will remain but perhaps a deeper navy might work best.
*   Try to incorporate the FOB logo into the navigation bar for each page.


## Technologies Used

*   HTML - Used for the structure of the website.

*   CSS - Used to style the website.

*   [Bootstrap](https://getbootstrap.com/) - used throughout the site for layout and styling. Imported JavaScript/Query for each page to support the reponsive navigation bar burger icon for
    tablet and mobile.

*   [Google Fonts](https://fonts.google.com/) - provided the *Quicksand* font used throughout the website.

*   [Font Awesome](https://fontawesome.com/) - provided the scocail media icons used on the Footer.

*   [Google Chrome Developer Tools](https://developer.chrome.com/docs/devtools/open/) - used to inpect each page, debug and mostly to test different CSS styles.

*   [GitHub](https://github.com/) - hosting site to store the wensites source code and Git pages used to deploy the live site.

*   [Gitpod](https://gitpod.io/workspaces) - the version control to, check status, add, commit and push code to GitHubs repository for storage.

*   [Microsoft PowerPoint](https://office.live.com/start/powerpoint.aspx) - used to create the wireframes.

*   [PX converter](https://nekocalc.com/px-to-rem-converter) - to covert px values to rem values.

*   [Codepen](https://codepen.io/) - used to help create the contact form on the contact page.

*   [YouTube Help](https://support.google.com/youtube/answer/171780?hl=en) - used to help embeed the youtube video and start video from the time necessary for the music page.




## Testing

### Testing Strategy

1.  Complete three whole site testing acting as a first time user, returning user and a frequent user.

    **NOTE:** All tests will be condected for desktop, tablet and mobile.

1.  Run all pages through the [W3C HTML Validator](https://validator.w3.org/).

1.  Run all pages through the [W3C CSS Validator](http://www.css-validator.org/).


### Test Results

#### Validation Results

*   line 49 Error: The element button must not appear as a descendant of the a element. (index.html)


*   Error: The frameborder attribute on the iframe element is obsolete. Use CSS instead.

    From line 120, column 29; to line 120, column 299 (music)


*   Error: Element h3 not allowed as child of element button in this context. (Suppressing further errors from this subtree.)

    From line 158, column 33; to line 158, column 36 (credits)


*   Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.

    From line 153, column 13; to line 153, column 43 (credits)


*   403	.feedback-input	Value Error : padding only 0 can be a unit. You must put a unit after your number : 0.813 (css)


#### User Results

##### First Time users

The first time user wants the following:

*   View clear and concise content on mobile
    *   ...
*   Learn and understand what FOB Beats is about.
    *   ...
*   Understand the services offered.
    *   ...
*   Seemlessly navigated through the 5 pages of the site.
    *   ...
*   Easily connect with FOBs social platforms.
    *   ...

#### Returning Users

The returning user wants the following:

*   Purchase FOBs beats through the external link portal on the site.
    *   ...
*   Watch and take notes on FOBs step by step beat making tutorial.
    *   ...
*   Book a recording seesion via the contact form.
    *   ...

#### Frequent Users

The frequent user wants the following:

*   Use FOBs credit list as a continuous muscial source
    *   ...
*   To see when new beats arrive on the site
    *   ...


## Deployment?

## Credits



<!-- # FOB Beats

## UX

Who is the website for?



## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.

### Existing Features

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

* Another feature idea

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

## References

    *   Bootstrap for nav bar
    *   https://codepen.io/ZachSaucier/pen/AIJpe (Contact Form)
    *   youtube video code copied from embed option on youtube
    *   https://getbootstrap.com/docs/4.0/components/collapse/ - for collapse element on credits.html  -->