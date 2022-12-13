# Homework 1 - Code Refactor 

## Description 

The Layout

The first thing I changed from the original mockup html code was to change the title form "Document" to "Horiseon" which makes a lot more sense as potantial clients will se the title of the page on the tab when they visit the website. 

Then I put a header at the original mockup code as well. 

The header element is used on a HTML page to represent introductory content or a set of navigational links so it made sense to organise the code with a header right after the head. It makes the page more accessible and more organised for readers and for the computer as well. 

On the CSS document, I changed the .header to header to make sure they matched and work together to make the page work. 

I also changed the <div> to <nav> in the header.  The <nav> html element is used to represent a section in the page which provides navigation links which could be related to the current document or, to other external documents. 

I also had to changed the header <div> into header <nav> on the CSS document. 


When necessary and possible I changed the code <div> and put down <nav> instead. That helps clearing the code so it is easier and more organised for other developers to see what is happening and what is coming next as well as making sure I'd followed a semantic structure which was part of the criteria for this project.

As accessibility is becoming a more and more important fact to be considered I used semantic tags all along the refactoring process.  

At the main section of the page, I changed the <div class=content> into <main> because it is the main part of the container and I added a <section> for each section correspondent to the services this company offers. That makes the coding more organised and we know it is a different section for each on of these services, with its images, images descriptions, headlines and atributes. 

For each one of this sections I added an id and a class and I've called them "services" because these are the servies this company offers to their clients. That helped making it easier, as well as quicker to work on the CSS document as they are all going to have the same style. 

For each one of these sections, a description to the image was added to help with the SEO and visibility on goodle ranking. 

All the images of these 3 sections were resized as well to make sure the site can downloaded into other people's brownser's quick enough.

On the CSS file I updated its respectives styles and renamed them as "services" as well so both files are algined with each other and make sense for the readers and the computer. 

For the content at the sidebar of the webpage, I replaced <div> to <aside> which helps to make the HTML code more organised for other developers as well as it follows semantic structure. The <aside> tag is used to represent content aside form the content it is placed on the main section of the page. The <aside> tag should be indirected related to the main content of the page and it is also helpful to use it as you can use CSS to style the <side> element. 

I inserted a class atribute at the <aside> section to help with styling these classes on the CSS document. The class atribute called "benefits" was used at the CSS document to style all the "benefit" class in the same way having ti type the code only once. That saved me time as I did not spent time doing redundant work. 

I also changed the <div class="benefit-lead"> <div class="benefit-brand"> and <div class="benefit-cost"> into <div class="benefit"> only to make it simpler as the longer, previous name wasn't needed. 

On the CSS file there was a lot of redundancy around "benefit-lead", "benefit-brand" and "benefit-cost" and because they are all from the same class and all have the same style I deleted them and used only .benefit  as a class atribute in the respective styles.


On the footer section of the page I changed the <div class=footer> into <footer> so we keep the standards and semantic structure asked for accessibility. 










Your GitHub profile is an extremely important aspect of your public identity as a developer. A well-crafted one allows you to show off your work to other developers as well as potential employers. An important component of your GitHub profile—and one that many new developers often overlook—is the README.md file.

The quality of a README often differentiates a good project from a bad project. A good one takes advantage of the opportunity to explain and showcase what your application does, justify the technologies used, and even talk about some of the challenges you faced and features you hope to implement in the future. A good README helps you stand out among the large crowd of developers putting their work on GitHub.

There's no one right way to structure a good README. There is one very wrong way, however, and that is to not include a README at all or to create a very anemic one. This guide outlines a few best practices. As you progress in your career, you will develop your own ideas about what makes a good README.

At a minimum, your project README needs a title and a short description explaining the what, why, and how. What was your motivation? Why did you build this project? (Note: The answer is not "Because it was a homework assignment.") What problem does it solve? What did you learn? What makes your project stand out? 

Lastly, if your project is deployed, include a link to the deployed application here.

If you're new to Markdown, read the GitHub guide on [Mastering Markdown](https://guides.github.com/features/mastering-markdown/).

If you need an example of a good README, check out [the VSCode repository](https://github.com/microsoft/vscode).


## Table of Contents 

If your README is very long, add a table of contents to make it easy for users to find what they need.

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)


## Installation

What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running.


## Usage 

Provide instructions and examples for use. Include screenshots as needed. 

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

```md
![alt text](assets/images/screenshot.png)
```


## Credits

List your collaborators, if any, with links to their GitHub profiles.

If you used any third-party assets that require attribution, list the creators with links to their primary web presence in this section.

If you followed tutorials, include links to those here as well.


## License

The last section of a good README is a license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, use [https://choosealicense.com/](https://choosealicense.com/)


---

🏆 The sections listed above are the minimum for a good README, but your project will ultimately determine the content of this document. You might also want to consider adding the following sections.

## Badges

![badmath](https://img.shields.io/github/languages/top/nielsenjared/badmath)

Badges aren't _necessary_, per se, but they demonstrate street cred. Badges let other developers know that you know what you're doing. Check out the badges hosted by [shields.io](https://shields.io/). You may not understand what they all represent now, but you will in time.

## Features

If your project has a lot of features, consider adding a heading called "Features" and listing them there.

## Contributing

If you created an application or package and would like other developers to contribute it, you will want to add guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own.


