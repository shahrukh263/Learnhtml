# 1. Background

`background` CSS property element ke background styling ko control karne ke liye istemal hoti hai. Is property se aap background color, image, repeat behavior, attachment, aur position ko define kar sakte hain.

`background` property ke alag-alag values aur unke sub-properties hote hain:

1. **background-color:** Is property se element ka `background` color set kiya jata hai.

Example:

```
div {
  background-color: lightblue; /* Sets background color to light blue */
}
```

2. **background-image:** Is property se element ke background mein image set kiya jata hai.

Example:

```
div {
  background-image: url('image.jpg'); /* Sets background image */
}
```

3. **background-repeat:** Is property se background image ka repeat behavior set kiya jata hai. Values mein repeat, repeat-x, repeat-y, aur no-repeat hote hain.

Example:

```
div {
  background-repeat: no-repeat; /* Background image will not repeat */
}
```

4. **background-attachment:** Is property se background image ke attachment behavior ko set kiya jata hai. Values mein scroll aur fixed hote hain.

Example:

```
div {
  background-attachment: fixed; /* Background image will be fixed */
}
```

5. **background-position:** Is property se background image ki starting position set ki jati hai. Position values mein pixels, percentages, aur predefined keywords (`top, bottom, left, right, center`) ka upayog hota hai.

Example:

```
div {
  background-position: center top; /* Sets background position to center top */
}
```

Is prakar se, background property ka istemal element ke background styling ko customize karne ke liye hota hai. Ye property design aur visual appearance ko enhance karne mein madad karta hai.