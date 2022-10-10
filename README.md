# Code assesment - Exercise 1 - No Framework
This project is a part of the hiring process. 
After assessing the amount of work and the given time to complete the task, I decided that the best solution would be not to use any framework. 
The proper configuration itself could take up to 30% of the time, so I decided to go with the most optimal way (no framework). 
Based on the general rule of thumb that says **you should write your own styling, do not use "pre-made" tools and utilities.** I decided to focus on writing styles 

## Instructions to run the project
Just open `index.html` at the root level, no additional command required.

## Potential improvements

#### Impovements for the end project.
- Render nav items on **hamburger menu** icon click and add [animation](https://codepen.io/alvarotrigo/pen/MWEJEWG?editors=1100)
- Add animation for the banner content, probably to slide in animation from the left and right sides && make them visible in transition.
- Add some [border color animation](https://codepen.io/Takumari85/pen/RaYwpJ) for the search input.
- Add [**ARIA**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA) attributes to improve accessibility. 
- Use **Relative Units** in styles instead of pixels.
- Add **LOGO** in the header. It makes easier to navigate to the home page by clicking on the logo, plus it increases brand awareness =) 
- I would **rewrite breakpoint mixins** to be a function and accept dimensions as a parameter.
- Store some of the style values as a sass variables.
- **Conditional rendering.** Render nav item menu arrow based on number of children elements. Do not display any. 
- Add **SASS linter**.
- Add **head meta tags** to improve SEO
- Find the original font-family

#### Impovents for the code assessment
- Provide project (Exercise #1, Exercise #2) description to better understand the audience


## Stack
HTML - 35.2%
SCSS - 64.8% 

> `normalize.css` was added for style consistency purposes, since initial styles may differ from browser to browser.

> **The original implementation may vary from the Figma design.** I tried to implement a pixel perfect design, but some of the values are inconsistent. For example, the header left padding is 23px and the right one is 25px, so i improved a bit.
