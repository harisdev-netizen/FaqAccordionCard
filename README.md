# Frontend Mentor - FAQ Accordion Card

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

  - [The challenge](#the-challenge)
  - [Live Site Link](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

### The challenge

Your challenge is to build out this FAQ accordion card and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Your users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### links

- Live Site URL: [Faq Accordion Card](https://vigorous-khorana-271021.netlify.app)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS flex

### What I learned

Apply checkbox input to create Collapse instead of JavaScript

```html
<div class="question">
  <input type="checkbox" name="faq-btn" id="faq1" />

  <label for="faq1">
    <span>How many team members can I invite?</span>
    <img class="arrow-icon" src="images/icon-arrow-down.svg" alt="Arrow icon" />
  </label>
  <p>
    You can invite up to 2 additional users on the Free plan. There is no limit
    on team members for the Premium plan.
  </p>
</div>
```

```css
input[type="checkbox"] ~ p {
  display: none;
  line-height: 1.5;
  font-size: 12px;
}

input[type="checkbox"]:checked ~ p {
  display: block;
}
```

## Author

- Website - [Haris](https://github.com/harisdev-netizen)
- Frontend Mentor - [@harisdev-netizen](https://www.frontendmentor.io/profile/harisdev-netizen)
