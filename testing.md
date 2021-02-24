# Milestone Project One - Testing

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