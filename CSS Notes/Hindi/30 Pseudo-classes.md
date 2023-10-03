# 1. Pseudo-classes

`Pseudo-classes` CSS selectors hote hain jo specific states ya actions par apply hote hain, jaise ke element ka hover, active, visited, ya focus state. `Pseudo-classes` element ke normal state se alag behavior define karte hain.

`Pseudo-classes` ke syntax mein colon (`:`) ka upayog hota hai. Niche kuch commonly used `pseudo-classes` diye gaye hain:

1. **hover:** Jab mouse pointer element par hover karta hai, toh is pseudo-class se define ki gayi styles apply hoti hain.

Example:

```
a:hover {
  color: red; /* Text color will change to red on hover */
}
```

2. **active:** Jab element active (`click`) hota hai, toh is pseudo-class se define ki gayi styles apply hoti hain.

Example:

```
button:active {
  background-color: green; /* Button background color will change to green when clicked */
}
```

3. **visited:** Jab hyperlink pehle se visit kiya gaya ho, toh is pseudo-class se define ki gayi styles apply hoti hain.

Example:


```
a:visited {
  color: purple; /* Visited links will have purple text color */
}
```

4. **focus:** Jab element focus milta hai, jaise input field par click karke, toh is pseudo-class se define ki gayi styles apply hoti hain.

Example:

```
input:focus {
  border-color: blue; /* Input field border color will change to blue when focused */
}
```

5. **nth-child():** Is pseudo-class se aap specific position par element ko target kar sakte hain. Isme argument ke roop mein aap number, even, odd, formulas jaise expressions use kar sakte hain.

Example:

```
li:nth-child(odd) {
  background-color: lightgray; /* Alternate list items will have light gray background */
}
```
**Pseudo-classes:**

6. **:checked:** Input elements (checkbox/radio) ko select kiya gaya ho to style apply hota hai.

7. **:disabled:** Disabled elements par style apply hota hai.

8. **:empty:** Element empty ho to style apply hota hai.

9. **:enabled:** Enabled elements par style apply hota hai.

10. **:first-child:** Element ka pehla child select karke style apply hota hai.

11. **:first-of-type:** Element ka pehla specified type ka child select karke style apply hota hai.

12. **:in-range:** Input elements ke value specified range mein ho to style apply hota hai.

13. **:invalid:** Invalid input elements par style apply hota hai.

14. **:lang(language):** Element jo specified language mein ho us par style apply hota hai.

15. **:last-child:** Element ka last child select karke style apply hota hai.

16. **:last-of-type:** Element ka last specified type ka child select karke style apply hota hai.

17. **:link:** Visited state se pehle (jab link pehli baar dikhata hai) link par style apply hota hai.

18. **:not(selector):** Specific selector ke opposite elements par style apply hota hai.

19. **:nth-last-child():** Element ka specified position par last se select karke style apply hota hai.

20. **:only-of-type:** Parent element mein ek hi specified type ka child ho to us par style apply hota hai.

21. **:only-child:** Parent element mein ek hi child ho to us par style apply hota hai.

22. **:optional:** Input elements jo required nahi ho unpar style apply hota hai.

23. **:out-of-range:** Input elements jo specified range ke bahar ho unpar style apply hota hai.

24. **:read-only:** Read-only input elements par style apply hota hai.

25. **:read-write:** Read-write input elements par style apply hota hai.

26. **:required:** Required input elements par style apply hota hai.

27. **:root:** Document ke root element par style apply hota hai.

28. **:target:** Targeted (URL ke end me hash se define kiya gaya) element par style apply hota hai.

29. **:valid:** Valid input elements par style apply hota hai.

30. **:visited:** Visited state ke baad (jab link pehle dikh chuka hai) link par style apply hota hai.

Yeh `Pseudo-elements` aur `Pseudo-classes` aapke website ya web application ke specific styling aur user interaction ko customize karne mein madad karte hain

`Pseudo-classes` ko istemal karke aap elements ke various states aur interactions ko customize kar sakte hain. Isse aap user experience aur design ko enhance kar sakte hain.