# Homework 1 - Code Refactor 

## Description 

The Layout

The first thing I changed from the original mockup html code was to change the title form "Document" to "Horiseon" which makes a lot more sense as potantial clients will se the title of the page on the tab when they visit the website. 

Then I put a header at the original mockup code as well. 

The header element is used on a HTML page to represent introductory content or a set of navigational links so it made sense to organise the code with a header right after the head. It makes the page more accessible and more organised for readers and for the computer as well. 

On the CSS document, I changed the .header to header to make sure they matched and work together to make the page work. 

I also changed the div to nav in the header.  The nav html element is used to represent a section in the page which provides navigation links which could be related to the current document or, to other external documents. 

I also had to changed the header div into header nav on the CSS document. 


When necessary and possible I changed the code div and put down nav instead. That helps clearing the code so it is easier and more organised for other developers to see what is happening and what is coming next as well as making sure I'd followed a semantic structure which was part of the criteria for this project.

As accessibility is becoming a more and more important fact to be considered I used semantic tags all along the refactoring process.  

At the main section of the page, I changed the div class=content into main because it is the main part of the container and I added a section for each section correspondent to the services this company offers. That makes the coding more organised and we know it is a different section for each on of these services, with its images, images descriptions, headlines and atributes. 

For each one of this sections I added an id and a class and I've called them "services" because these are the servies this company offers to their clients. That helped making it easier, as well as quicker to work on the CSS document as they are all going to have the same style. 

For each one of these sections, a description to the image was added to help with the SEO and visibility on goodle ranking. 

All the images of these 3 sections were resized as well to make sure the site can downloaded into other people's brownser's quick enough.

On the CSS file I updated its respectives styles and renamed them as "services" as well so both files are algined with each other and make sense for the readers and the computer. 

For the content at the sidebar of the webpage, I replaced div to aside which helps to make the HTML code more organised for other developers as well as it follows semantic structure. The aside tag is used to represent content aside form the content it is placed on the main section of the page. The aside tag should be indirected related to the main content of the page and it is also helpful to use it as you can use CSS to style the side element. 

I inserted a class atribute at the aside section to help with styling these classes on the CSS document. The class atribute called "benefits" was used at the CSS document to style all the "benefit" class in the same way having ti type the code only once. That saved me time as I did not spent time doing redundant work. 

I also changed the div class="benefit-lead" div class="benefit-brand" and div class="benefit-cost" into div class="benefit" only to make it simpler as the longer, previous name wasn't needed. 

On the CSS file there was a lot of redundancy around "benefit-lead", "benefit-brand" and "benefit-cost" and because they are all from the same class and all have the same style I deleted them and used only .benefit  as a class atribute in the respective styles.


On the footer section of the page I changed the div class=footer into footer so we keep the standards and semantic structure asked for accessibility. On the CSS file I also changed it from .footer into footer to make sure it is all adjusted! 


# Deployed link:
https://melissapazzanese123.github.io/homework-1-challenge/



## Usage 

# Screenshot link:
https://github.com/melissapazzanese123/homework-1-challenge/tree/main/assets/images


## Credits

List your collaborators, if any, with links to their GitHub profiles.

If you used any third-party assets that require attribution, list the creators with links to their primary web presence in this section.

If you followed tutorials, include links to those here as well.


## License

MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


---

## Badges

![badmath](https://img.shields.io/github/languages/top/nielsenjared/badmath)

Badges aren't _necessary_, per se, but they demonstrate street cred. Badges let other developers know that you know what you're doing. Check out the badges hosted by [shields.io](https://shields.io/). You may not understand what they all represent now, but you will in time.




