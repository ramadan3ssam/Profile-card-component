# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview
 simple design of personal card using HTML & CSS only without any framework or JS

### The challenge

- Build out the project to the designs provided

### Screenshot

![](https://github.com/ramadan3ssam/Profile-card-component/blob/main/images/screenshot.png)


### Links

- Solution URL: [solution URL here](https://github.com/ramadan3ssam/Profile-card-component)
- Live Site URL: [live site URL here](https://ramadan3ssam.github.io/Profile-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS3 custom properties
- Flexbox


### What I learned

I learn how to make best use of flex property as the code below:

```html
    <div class="stats">
       <div class="stat-block">
          <h3>80K</h3>
           Followers
        </div>
        <div class="stat-block">
           <h3>803K</h3>
            Likes
         </div>
         <div class="stat-block">
            <h3>1.4K</h3>
            Photos
          </div>
    </div>
```
```css
.card .stats {
    display: flex;
    border-top: 1px solid hsl(0, 0%, 59%);
    margin-top: 20px;
    padding: 20px;
    justify-content: space-between;
    align-items: center;
}

.card .stats .stat-block {
    font-weight: 400;
    font-size: 11px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    flex-basis: 30%;
    color: hsl(227, 10%, 46%);
}
```


## Author

- Codepen - [Ramadan Essam](https://codepen.io/ramadan3ssam)
- Frontend Mentor - [@ramadan3ssam](https://www.frontendmentor.io/profile/ramadan3ssam)
- Twitter - [@ramadan3ssam](https://www.twitter.com/ramadan3ssam)
- Facebook - [Ramadan Essam](https://www.facebook.com/ramadan3ssam)


