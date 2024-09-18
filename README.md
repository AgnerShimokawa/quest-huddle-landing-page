## Table of Content

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)


## <h2 id="overview">Overview</h2>

### <h3 id="the-challengeo">The Challenge</h3>

The challenge was to create a responsive header, body and footer using flex, having a different layout for desktop view and mobile view.

### Screenshot

Desktop View 1920x1080
![](./src/design/Screenshot%202024-08-11%20234421.png)
Mobile View 375x685

![](./src/design/Screenshot%202024-08-12%20000219.png)

### Links

- URL for hte solution on GitHUb: [Link GitHub](https://github.com/AgnerShimokawa/quest-huddle-landing-page)
- URL of the live site: [Link of site](https://agnershimokawa.github.io/quest-huddle-landing-page/)

## <h2 id="my-process">My Process</h2>

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### <h3 id="what-i-learned">What I Learned</h3>

With this project I've learned that to use the pluggin, PerfectPixel, you need to set the resolution of your screen to be that of the resolution of the screen that the image was created. My screen resolution by default is 1920X1080, so I couldn't make the proportions to work until I realized that the image was created with a resolution of 1440X900, then things started to fit better. However, by the end of the day, I reverted back to my default resolution, and forgot to change when I came back to the project, only to measure things with the wrong resolution again, making eveything look crooked and out of place. After that I decided to eyeball everything and making the adjustments in a "this seems close" kind of a way.

Another thing was to change the font size according to the size of the screen. using:

```css
.main .main-container .main-text h2 {
   font-size: calc(1.7vw + 1.7vh);
}
```

With this the font size is calculated with the viewport of the screen. It was very useful since initially the image was responsive, but the font size stayed the same, creating a unbalence as a whole, and also it created unnecessary scroll bars.
However, the rate with which the image and the font size decreased wasn't fast enough, to go around that I had to create a few media queries to force change the size of the elements to make it look better in smaller screen sizes. 

It was a project with a little bit of complexity when it comes to responsiveness at my current level, when things got decentralized as I decreased the size of the screen at times it got a little bit frustrating, however, with all that I have learned and made note of, and serching "can I do that?", helped a lot to achieve the final result. Most likely the solution is much simpler than what I've done, but this was the "easiest" way that I've found.