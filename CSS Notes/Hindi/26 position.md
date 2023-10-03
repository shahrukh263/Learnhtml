# 1. position

CSS mein position property element ko webpage ke layout mein kaise position kiya jaye, isko define karta hai. Is property ka istemal element ko absolute, relative, fixed, ya static position mein rakhne ke liye hota hai.

position property ke alag-alag values hote hain:

1. **static:** Default value. Element normal flow mein rehta hai. Top, bottom, left, right properties ka koi effect nahi hota.

```
/* Static Position */
p.static {
  position: static;
}
```

2. **relative:** Element normal flow mein rehta hai lekin **top, bottom, left, aur right** properties ke saath istemal karke uski position ko relative to its normal position set kiya ja sakta hai.

```
/* Relative Position */
div.relative {
  position: relative;
  top: 20px;
  left: 30px;
}
```

3. **absolute:** Element normal flow se bahar hota hai aur uski position parent element ya ancestor element ke relative position se relative set ki jaati hai. Agar koi ancestor element relative position na ho toh `<html>` element ke relative position se set hoti hai.

```
/* Absolute Position */
div.absolute {
  position: absolute;
  top: 50px;
  right: 0;
}
```

4. **fixed:** Element viewport (browser window) ke relative set hota hai, yani wo hamesha screen ke ek fixed position par rehta hai, scroll karne par bhi.

```
/* Fixed Position */
div.fixed {
  position: fixed;
  bottom: 0;
  left: 0;
}
```

5. **sticky:** Element normal flow mein rehta hai jab tak wo viewport se bahar nahi hota. Agar wo viewport se bahar ho jata hai toh uska position fixed ho jata hai, lekin scroll karne par wapas relative ho jata hai.

```
/* Sticky Position */
div.sticky {
  position: sticky;
  top: 0;
}
```

Is prakar se, position property ka istemal element ko webpage mein desired position par set karne ke liye hota hai. Ye property layout aur design ke customization mein madad karta hai.




