# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)

## My process

Since the way element are supposed to be placed, i used flexbox to get the job done.
I simply created a container where the qr-code img is placed, same as the text.
I setted border radius to the container and the qr-code img inside.
Then after the page rendered as wanted on regular desktop screen,
I though about importing @media-queries for the mobile version but
since the page has no responsive element, there is no need to.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

While working on this project, I trained my flexbox skills,
solving minor problems with or without internet research.

I also started organizing my css code, thing I wasn't used to so 
I started practicing it.

Exemple:
```css
.container {
    display: flex;
    flex-direction: column;
    flex-flow: wrap;
    align-self: center;
    justify-self: center;
    order: 1;
    
    height: 420px;
    width: 250px;
    padding: 15px;
    margin: auto;
    border-radius: 15px;
    
    overflow: hidden;
    /* check if it work */
    object-position: center;

    text-align: center;
    font-weight: 400;
    font-size: 15px;

    background-color: hsl(0, 0%, 100%);
}
```
Here I separate all flexbox properties first, 
then the element size, margin and padding,
I also separate text size and position properties,
and in the end I place the background color or text color.

### Continued development

I need to understand the functionning of certains properties like 
``position`` or ``box-sizing``

## Author

- Frontend Mentor - [@Obamasixgaming](https://www.frontendmentor.io/profile/Obamasixgaming)
