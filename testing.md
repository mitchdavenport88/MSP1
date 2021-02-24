# Milestone Project One

The live site can be viewed here - [alexandra davenport](https://mitchdavenport88.github.io/MSP1/)

[Main README file.](README.md)

## Testing

My code has been put through the following:
* W3C Markup validation.
  * index.html - passed.
  * about.html - failed.
    * I had written the h5 headings for the years within the ul tags as part of the list. 
I rectified this by removing the h5 elements out of the ul's and writing lists under each heading instead of one having 
one long list, I had to tweak my css styling too but it then passed at the second attempt.
  * work.html - passed.
  * contact.html - passed

* W3C CSS validation - one error and two warnings [(screenshot)](https://github.com/mitchdavenport88/MSP1/blob/master/readme-attachments/w3c_css%20_validator.jpg?raw=true).
  1. Warning 1 was that the validator doesn’t check imported style sheets - my google font import.
  2. Warning 2 was regarding the code I used off W3schools to hide the scroll bar on Chrome, Opera and Safari. 
I removed the code and tested it again on Chrome and the scroll bar appeared so I’m to ignore this warning as it worked during testing.
  3. Error 1 was again concerning the code I used off W3schools to hide the scroll bar but this time on Firefox telling 
me the property scrollbar-width: none; doesn’t exist. I removed the code and tested it again and the scrollbar appeared 
whereas before it was hidden so I’m happy it does exist.

* [AutoPrefixer.](https://autoprefixer.github.io/) Validates CSS for additional browsers.

### User Stories
I’m a curator who is planning an upcoming exhibition and I’ve been pointed towards Alex - 
I’d now like to **(1) see some examples of her work)**. I’d also like to **(2) find out abit about her)** and see what **(3)other exhibitions 
she has been involved in).** I like what I see and want to **(4) get in touch with her)** to discuss my upcoming exhibition.
1) Work page shows these examples and is easily to find in both the side bar and dropdown menu.
2) The about page talks about Alexandra and her work - again easily found in both the side bar and dropdown menu.
3) A list of exhibitions past, present and future can be found on the about page.
4) I can use the contact form found on the contact page found in both the side bar and dropdown menu's or click the 
email icon found in the footer on all pages (and on all devices) to email her.

I’m a student who is taught by Alex. As an aspiring artist **(1)I’d like to see her work** and use this as inspiration for my 
upcoming projects. I spend a lot of time on social media and I’d like to **(2)follow Alex on Instagram** as I like her work. 
I can also use her posts as research for my university work and **(3)keep an eye out for upcoming shows and exhibitions**.
1) Work page shows examples of her work and is easily to find in both the side bar and dropdown menu.
2) In the footer on all pages (and on all devices) there is a instagram icon, which will send the user to Alexandra's 
Instagram account in a new window.
3) A list of exhibitions past, present and future can be found on the about page. Also the user has the option to sign up 
to Alexandra's newsletter via mailchimp if they'd like to be kept in the loop. A link to which can be found in the footer 
on all pages (and on all devices) via the mailchimp icon.

I’ve recently seen some of Alex’s work at a gallery and would like to **(1)see more**. I’d like to informed of **(2)upcoming projects, 
exhibitions** and news so follow her on **(3)social media** and also **(4)subscribe to a mailing list**.
1) Work page shows more examples and is easily to find in both the side bar and dropdown menu. And the plan as outlined 
in the scope is to turn this section of the site into more of a portfolio adding more content and context to the work shown.
2) A list of planned exhibitions can be found on the about page.
3) Alex only has Instagram. In the footer on all pages (and on all devices) there is a instagram icon, which will send 
the user to Alexandra's Instagram account.
4) Next to the Instagram icon is the mailchimp icon by clicking this the user has the option to sign up to Alexandra's 
newsletter.

### Functionality


### Responsiveness


### Browser Compatibility
I have physically tested my website on Chrome, Firefox and Microsoft Edge on a desktop. It's also been tested on Safari 
with an iPad and iPhone 6. Firefox was also tested on just the iPhone 6.

I tested for responsiveness on other devices such as the Galaxy S9, iPhone 5, iPhone X and Kindle using Chrome DevTools along 
with the Responsive Design Mode on Firefox and the Inspect tool on Microsoft Edge to cover all bases. Whilst doing this I 
encountered one bug whilst doing this on Firefox, which I've documented below.

### Bugs & fixes
* Whilst using the Responsive Design Mode on Firefox i noticed the submit button on my contact page was hugging the bottom 
of the blue box my form is displayed in - 
[image here](https://github.com/mitchdavenport88/MSP1/blob/master/readme-attachments/firefox_iphone6_test(responsive-design-mode).png?raw=true). 
This isn't how I expected it to look as I have padding all around the box so there should be space between the button and 
the bottom of the box. But this was only occuring in Firefox. So I downloaded Firefox onto my phone to double check it and it 
displayed as expected and as shown on Egde and Chrome -
[image here](https://github.com/mitchdavenport88/MSP1/blob/master/readme-attachments/firefox_iphone6_test(actual-phone).png?raw=true).
So im putting this down to the Responsive Design Mode being a tool that replicates how it thinks it'll render but in this instance 
it doesnt actually render as predicted.

* Dropdown menu.