# Appointment Landing Page

## Course information

Stephanie Marzan
Summer C 2021
MMC5277: Web Design Principles


I,Stephanie Marzan, have read the point deduction list and understand that I will lose points for missing items.

### InBody Color Reference

Use the color picker to get the exact color that needs to be use in the text "InBody".

![InBody Logo](images/inbody.png)

#### Animation

The animation needs to be added to the image with an animation duration in order to work. Use position absolute to position the element where you want it to go.

```css

.smile-img{
  width: 150px;
  padding: 100px 0px;
  position: absolute;
  animation: move 18s forwards linear infinite;
  left: 0px;
  bottom: -780px;
}
```
Create a keyframe with the animation where you specify how the image coded above should translate.

```css

@keyframes move {
  from {
    transform: translateX(-100px)
  }

  to{
    transform: translateX(2000px)
  }
}
```

##### Resources

[Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#headers)
