# Alexandra Davenport

### Milestone Project One

Alexandra Davenport is a London based artist working primarily with performance, photography and text. 
She already has a basic wordpress site - [www.alexdavenport.com](https://alexdavenport.com/); which shows examples of her 
work, collaborations and publications but she struggles to maintain and style this as many artists do. 

Since 2018 Alexandra has been lecturing at the Arts University Bournemouth and with this new direction would 
like a cleaner, more professional looking website so she can share her journey with others. 

## Demo

The live site can be viewed here - [alexandra davenport](https://mitchdavenport88.github.io/MSP1/).

GitHub repository can be viewed here - [mitchdavenport88/MSP1](https://github.com/mitchdavenport88/MSP1).

![Site Mockup](readme-attachments/ami.responsivedesign.is(1).jpg)

## UX

### Strategy
The aim is to improve the current site by streamlining the existing one by removing irrelevant information and 
sections to find a balance between an artistic / professional aesthetic and feel.

Reasons for the site:
* Self-promotion.
* To show her portfolio / body of work to others.
* To help people get in touch with her.

### User Stories
1. I’m a curator who is planning an upcoming exhibition and I’ve been pointed towards Alex - 
I’d now like to see some examples of her work. I’d also like to find out abit about her and see what other exhibitions 
she has been involved in. I like what I see and want to get in touch with her to discuss my upcoming exhibition.

2. I’m a student who is taught by Alex. As an aspiring artist I’d like to see her work and use this as inspiration for my 
upcoming projects. I spend a lot of time on social media and I’d like to follow Alex on Instagram as I like her work. 
I can also use her posts as research for my university work and keep an eye out for upcoming shows and exhibitions.

3. I’ve recently seen some of Alex’s work at a gallery and would like to see more. I’d like to be informed of upcoming 
projects, exhibitions and news so follow her on social media and also subscribe to a mailing list.

### Scope - Functionality
* The site must be easy to navigate around.
* Unlike most artist's websites it must be well presented and visually appealing.
* Be minimalistic to reflect her work.
* Function as expected.

### Scope - Content
As we are using this site to self-promote we need to meet these requirements:
* Tell the audience who we are and what we do.
* Show the audience our work.
* List where we are showing work and where we’ve shown work.
* Show features in the press we’ve had.
* Make it easy to get in touch by email, social media or contact form.

I'd like the work section to be more like an online portfolio; with each project having a page to itself 
talking about the project in more detail and showing more images, videos and sketches but in more structured and user 
friendly way than currently done.

Alex has selected 12 projects that she’d like to continue displaying – meaning an additional 12 pages, which isn’t feasible 
or necessary at this time. We can keep this to one page for the time being and show an image that represents each project 
with the intention of this section of the site evolving over time. This would lead us to adding more pages (a page for each 
project) in the future, which will add more content and context to each project and the current work page acting as a 
visual contents page, linking to each of these project pages.

### Structure
Based on the content required in the scope this website will consist of 4 pages:
* A home / landing page, which will feature an image of Alex’s work.
* An about page, telling the user about Alex’s work and her work / exhibition history.
* Work page – as touched upon in the scope will show examples of Alex’s work with the view of extending this over time.
* Contact (contact form).

The site will have navigational links in the sidebar (on desktops) and in the header and footer (on tablet and mobile 
devices), which will feature on each page. Not only will this create a better space for displaying information but meaning 
the site will be easy to navigate around whilst the user will have access to her Instagram, the option to email Alex and 
to subscribe to her newsletter (via mailchimp) at any point.

### Skeleton
* Initial idea - [sketch](https://github.com/mitchdavenport88/MSP1/blob/master/wireframes/wireframe%20-%20sketch.jpg?raw=true).
* Home wireframes - [desktop](https://github.com/mitchdavenport88/MSP1/blob/master/wireframes/home%20_%20landing.png?raw=true) / 
[mobile](https://github.com/mitchdavenport88/MSP1/blob/master/wireframes/home%20_%20landing%20(mobile).png?raw=true).
* About wireframes - [desktop](https://github.com/mitchdavenport88/MSP1/blob/master/wireframes/about.png?raw=true) / 
[mobile](https://github.com/mitchdavenport88/MSP1/blob/master/wireframes/about%20(mobile).png?raw=true).
* Work wireframes - [desktop](https://github.com/mitchdavenport88/MSP1/blob/master/wireframes/work.png?raw=true) / 
[mobile](https://github.com/mitchdavenport88/MSP1/blob/master/wireframes/work%20(mobile).png?raw=true).
* Contact wireframes - [desktop](https://github.com/mitchdavenport88/MSP1/blob/master/wireframes/contact.png?raw=true) / 
[mobile](https://github.com/mitchdavenport88/MSP1/blob/master/wireframes/contact%20(mobile).png?raw=true).

### Surface
I’ve spoken about creating balance between an artistic and professional aesthetic throughout this site, implementing a 
minimalistic feel which I feel is suited to a website of this kind. 

Aesthetically I’ve liked the idea of a fixed side bar from the get go, so I plan on having this on every page with links 
to the other pages on here. A logo and a footer containing social media links will also feature at the top and bottom of 
this side bar, meaning you can access any page or contact details quickly and from any other page on the site. This side bar 
will collapse to a drop down menu in the header with the social links remaining at the foot of the page on smaller devices.

In keeping which my minimalistic approach I’ve chosen to use two colours that contrast one another and will use these 
throughout - #FAFAFA (white) and #366788 (blue), which I found using [ColorHunt.](https://colorhunt.co/) A lot of the images 
I plan on using are light in colour – so the white complements these whilst the blue offers a contrast where needed. I’m 
also planning on using the google font “Inter”, which is a sans-serif font similar to what she uses now. This imported 
google font along with the use of letter spacing in my CSS will help me achieve this professional and artistic look. 

The imagery used throughout this site will be a reflection on Alex herself being a photographer / artist first and foremost. 
The background of the home / landing page will be a full size image of Alex performing. A large image will also be used 
on the contact page as I feel it’s important to showcase her work where possible – I want the images to do the work really 
and add content and context where applicable. All Imagery will be supplied by Alex.

## Features

### Page layout
* Each page has been split into two sections; navigation and content. The navigation part of the page remains the same on 
all four pages with only the active classes on the menu changing.
* The content section of each page differs and features content relevant to that page.
* Responsive at all breakpoints. The page layout will change to something more suited to smaller devices when needed. 
Navigational elements are then housed in a dropdown menu found at the top of the page alongside the logo. Social links remain 
at the foot of the page while content is shown between them.

### Navigational
* Navigational elements are laid out the same regardless of what page you’re on.
* The logo is always in the top left of the page. This also has a secondary function as a link back to the home page. 
* Navigation links on lg devices are shown in the side bar on the left of the page.
* On md and smaller devices these links are housed in a dropdown menu found top right in the header next to the logo, 
where you’d expect to find it. The menu will toggle on/off on the press of a button, which you’d also expect. The button 
features the Font Awesome icon “fa-bars”, which is associated with this function. 
* I’ve put an active class on page links, which will underline and make the link bolder to inform the 
user of what page they are on.
* I've also used a hover class on the navigation links, which enlarges the text when hovered over, encouraging interaction.
* Icons represent the social links at the foot of the page. Each icon is associated with the intended 
destination and clicking them will send the user there via a new window/tab. I’ve used the same hover class feature on 
these again to encourage interaction. 

### Home
* Features an image from Alex’s most known collection of work: Circuit Training (exercises in self-doubt). This fills 
the entire content container.

### About
* An image will appear in the top left of the content container. This has a matching text box overlay that’s used throughout 
the work content. This image is responsive as it gets hidden on small devices.
* Text will appear inline with image when the image is displayed. Once the image is hidden this text will fill the width 
of the page.
* The quote has slightly larger font and will stand out more as I’ve used a background colour and inverted the colours.
* The exhibition and press lists are styled the same as the quote but are broken up by headings; breaking up 
any big blocks of colour. 
* Any list items that have external links have a similar hover class found on the navigation links, which enlarges the 
text when hovered over, encouraging interaction.

### Work
* Images are displayed in a masonry grid using column counts. The number of columns required will depend on screen 
size, making the content responsive. 
* The title of each piece of work is overlaid over each image, maintaining the look and feel of the site. 

### Contact
* The background of this page is another image of Circuit Training (exercises in self-doubt).
* Contact form is clearly shown in the fore-ground. This form fills the full screen width at a smaller breakpoint to 
make it suitable for smaller devices. 
* The form is set to `method=“POST”` and will send the data to the code institute form dump at the moment.
* Form inputs use `type=“text”` or `type=“email”` to accept inputs of that type only. All inputs are labelled and have
a `placeholder` so it’s clear what goes into each field.
* Text-area provides a space where a user can write a message to Alex. 
* Submit button is clearly labelled and changes colour when hovered over / pressed.
* All inputs are set to `required` so no empty forms can be sent.

### Features left to implement
* As mentioned in the scope I’d like to develop the work section of the site into more of an online portfolio, 
with each page having its own individual page. This page would give more details about Alex’s work and include more 
imagery, videos and sketches. The existing work page will act as a visual contents page – directing users to each 
individual project page.


## Technologies

* HTML & CSS.
* Gitpod (IDE).
* Git, GitHub, GitHub Pages. Used for version control, hosting my repository and hosting my site.
* [Balsamiq.](https://balsamiq.com/) Used for drawing the wireframes.
* [Bootstrap (v5.0).](https://getbootstrap.com/) Used for grid layout, responsive design and basic styling in some instances.
* [Font Awesome](https://fontawesome.com/).
* [Google Fonts](https://fonts.google.com/).
* JavaScript. Used to make the dropdown menu work on smaller devices. 
* [tinypng.com.](https://tinypng.com/) Compressed the image files used throughout.
* [Am I Responsive?.](http://ami.responsivedesign.is/) Produced the mock-up shown above.
* [Beautifer.](https://beautifier.io/) Cleaned up my code.
* W3C [HTML](https://validator.w3.org/) & [CSS](https://jigsaw.w3.org/css-validator/) validator.
* [AutoPrefixer.](https://autoprefixer.github.io/) Validated CSS for additional browsers.

## Testing

Separate testing document can be found here - [testing.md.](TESTING.md)

## Deployment

### Adding and committing files
I’ve been using Gitpod to write my code and using the terminal within to add, commit and push code from my workspace to 
GitHub where it is stored remotely as shown in the course content. 

1. When I have made a couple of minor additions / changes or one large change or addition I add the file in question to 
the staging area by typing in the terminal `git add .` the full stop will add all new files. If I want to be more 
selective I can type in the file name e.g. index.html or the files pathway e.g. assets/css/style.css instead of the full 
stop.
2. I now want to save my changes to the local repository by typing `git commit –m “ ”` into the terminal. Between the “ ” 
I'll write a concise message detailing what this commit has done.
3. When I either want to upload all my changes for the day or view on GitHub Pages I push all the commits I’ve previously 
done to GitHub using the `git push` command. When GitHub Pages is set up for the repository in question it will automatically 
pick up these changes and display the most up to date version that has been pushed.

### Deploying to GitHub Pages
1. Once logged into GitHub I navigated to my MSP1 repository via my repositories.
2. Selected settings in the menu at the top of the screen.
3. I scrolled down to the section 'GitHub Pages' near the bottom of the page.
4. Under 'Source' I changed the dropdown so it read Branch:master as this is the branch I'm using.
5. The page refreshes, meaning this was successful. Changes do take a while to take effect.
6. To retrieve the link I had to go back to the GitHub pages section via settings (like in step 3) where it's displayed.

### Cloning
Taken from GitHub's documentation on cloning, which can be found 
[here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop).

1. Once logged into GitHub, navigate to the repository you wish to clone.
2. Next to the green Gitpod button there's a button that reads code, click this. 
3. To clone the repository using HTTPS, copy the link whilst HTTPS is selected.
4. Open your local IDE of choice and open the terminal.
5. Navigate to the working directory of where you want the cloned directory to be.
6. Type `git clone` in the terminal and then paste the link that you selected in step 3. Press enter.
7. The clone is created in your current working directory (`cwd`).

## Credits

### Content
* All text was taken from Alex’s existing site.
* All images were also supplied by Alex. 

### Code
* I used [Bootstrap (v5.0)](https://getbootstrap.com/) for grid layout, responsive design and simple styling.
* The original drop down menu used for navigation on smaller devices was taken from 
[W3schools](https://www.w3schools.com/css/css_dropdowns.asp). I've kept some of the CSS from this.
* During testing it was suggested I changed my drop down menu to another one also found on 
[W3schools](https://www.w3schools.com/bootstrap4/bootstrap_navbar.asp) as it funtion's better.
* The basic code to achieve the masonry grid on the work page was taken from 
[css-tricks](https://css-tricks.com/seamless-responsive-photo-grid/).
* To refresh my memory on forms I watched the following on
[YouTube](https://www.youtube.com/watch?app=desktop&v=GMH3rNTN4IQ&t=579s). I used the basic code shown on this as a Skeleton 
and built off this adding my own labels, id's and writing the css to style the form.
* I disabled the resizable property of text area used on the contact form by using this code on the 
[Tutorial Republic](https://www.tutorialrepublic.com/faq/how-to-disable-resizable-property-of-textarea-using-css.php).

### Acknowledgements
* Alex Davenport again for allowing me to do this site based on her and supplying the content.
* [SophieKahn.net](https://www.sophiekahn.net/) inspired the fixed side bar that I used.
* Jim_Lynx's [MS1 Planning Session on YouTube](https://youtu.be/sH0m9N875SU).
* Tutor support at Code Institute for their help when required.
* Brian Macharia for the feedback in my mentor sessions and aiding in the planning and execution of this site.
* Ciaran Brady, Jade Quinn and Stefan Carter for taking the time to look at my site and giving feedback via 
slack's #peer-code-review channel.
* README examples - [AJGreaves](https://github.com/AJGreaves/portrait-artist/blob/master/README.md) / 
[Haley Schafer](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/README.md) / 
[crypticCaroline](https://github.com/crypticCaroline/ms1-plantfactory/blob/master/README.md).
* README template - [CodeInstitute.](https://github.com/Code-Institute-Solutions/readme-template)