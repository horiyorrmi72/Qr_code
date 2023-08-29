# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![desktop view](./images/Screenshot_2023-08-29%20Frontend%20Mentor%20QR%20code%20component%20desktop%20view.png)
![mobile view](./images/Screenshot_2023-08-29%20Frontend%20Mentor%20QR%20code%20component(1)%20mobile%20view.png)




### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS Flex

### What I learned

centralizing a division element and it's content with the use of css positioning and transform by setting its position to absolute which results in the positioning of the element out of it's relative enviroment then set it's position from the top to 50% and using the translate function of the css transform to justify the positioning.

```css
.container{
  display: flex;
  flex-direction: column;
  width:330px ;
  background-color: hsl(0, 0%, 100%);
  border-radius: 5%;
  position: absolute;
  top: 50%;
  transform:translate(0,-50%) ;   
      
    }
```

### Continued development

future features will include responsiveness on all screens as this is done only targeting screens of 1440px and that of 375px.
And might probably add more features as it comes to mind in the future.

## Author

- Website - [Yusuf Ridwan | Horla](https://horiyorrmi72.github.io/)
- Frontend Mentor - [@horiyorrmi72](https://www.frontendmentor.io/profile/horiyorrmi72)
- Twitter - [@horla_techs](https://twitter.com/horla_techs)
# qr_code
