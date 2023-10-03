# 1. overflow

CSS property overflow element ke content ke bahar ki visibility aur scrolling ko control karne ke liye istemal hoti hai. Is property se aap define kar sakte hain ki kya hoga agar element ke content uske specified dimensions se bahar jata hai.

overflow property ke alag-alag values hote hain:

1. **visible:** Default value. Content element ke bounds se bahar bhi dikhayi dega. Agar content bounds se bahar jata hai, toh wo content element ke bahar dikh sakta hai.

```
/* Visible Overflow */
div.visible-overflow {
  overflow: visible;
}
```

2. **hidden:** Content element ke bounds se bahar ka content dikhayi nahi dega. Isse content ka koi hissa visible nahi hoga.

```
/* Hidden Overflow */
div.hidden-overflow {
  overflow: hidden;
}
```

3. **scroll:** Agar content element ke bounds se bahar jata hai, toh horizontal aur vertical scrollbars dikhenge, jinse user content ko scroll karke dekh sakta hai.

```
/* Scroll Overflow */
div.scroll-overflow {
  overflow: scroll;
}
```

4. **auto:** Agar content element ke bounds se bahar jata hai, toh scrollbars dikhayi denge sirf agar content bounds se bahar jata hai. Agar content bounds ke andar hai, toh scrollbars dikhayi nahi denge.

```
/* Auto Overflow */
div.auto-overflow {
  overflow: auto;
}
```

Is prakar se, overflow property ka istemal element ke content ke bahar ki visibility aur scrolling ko control karne ke liye hota hai. Ye property content ka handling aur layout mein madad karta hai.