# 1. text-transform

**text-transform** CSS property text content ke case (maamoolan uppercase, lowercase, ya capitalize) ko modify karne ke liye hoti hai. Is property ko use karke aap text ko visually transform aur format kar sakte hain.

**text-transform** property ke alag-alag values hote hain:

1. **none:** Koi bhi case transformation nahi hoti hai (default behavior).
2. **capitalize:** Har word ke pehle character ko uppercase kar deti hai.
3. **uppercase:** Har character ko uppercase mein transform kar deti hai.
4. **lowercase:** Har character ko lowercase mein transform kar deti hai.
5. **full-width:** Text ko full-width characters mein transform kar deti hai (Japanese aur Chinese text ke liye).

Niche kuch examples diye gaye hain:

```
p {
  text-transform: uppercase; /* Uppercase text */
}
```

```
a {
  text-transform: capitalize; /* Capitalize first letter of each word */
}
```

```
span {
  text-transform: lowercase; /* Lowercase text */
}
```

Is prakar se, **text-transform** property ka istemal text content ke case ko modify karne ke liye hota hai, jisse aap text content ko visually customize kar sakte hain.