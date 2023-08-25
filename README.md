# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

<!-- Desktop Verison -->
![Alt text](<Screenshot (209).png>) 
![Alt text](<Screenshot (210).png>) 
![Alt text](<Screenshot (211).png>) 
![Alt text](<Screenshot (212).png>)
![Alt text](<Screenshot (213).png>)


<!-- Mobile Version -->
![Alt text](<Screenshot (214).png>)
![Alt text](<Screenshot (215).png>)
![Alt text](<Screenshot (216).png>)
![Alt text](<Screenshot (217).png>) 
![Alt text](<Screenshot (218).png>)
![Alt text](<Screenshot (219).png>) 
![Alt text](<Screenshot (220).png>)
![Alt text](<Screenshot (221).png>) 

## My process

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned
Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

In this challenge one of my major learnings was being able to use grid to either display a particular section one below another or beside each other. It really taught me how we can use grid to make our work more responsive. 


```html
        <div class="split-2">
            <div class="computer-image-container">
                <img src="images/image-computer.png" alt="large computer">
            </div>

            <div class="snippets-content-container text-center">
                <div>
                  <h3 class="text-dark">Quick Search</h3>
                    <p class="description">
                    Easily search your snippets by content category, web address,
                    application, and more.
                    </p>
                </div>
            </div>
```

```css
 .split-2 {
        grid-template-columns: repeat(2, 1fr);
    }
```


### Continued development
Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

I' ve found that using grid makes your layouts more responsive, so that's an area in css I want to perfect. 



## Author
- Frontend Mentor - [@cacti00](https://www.frontendmentor.io/profile/cacti00)
- Twitter - [@charles_ken7](https://www.twitter.com/charles_ken7)



