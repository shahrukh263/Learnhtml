# 1. white-space

**white-space** CSS property text content mein whitespace (jaise space, tab, newline) ka handling ko control karne ke liye hoti hai. Is property ko use karke aap text content ke whitespace ka behaviour modify kar sakte hain.

**white-space** property ke alag-alag values hote hain:

1. **normal:** Default behaviour. Extra spaces, tabs, aur newlines ko ek space mein combine karta hai aur additional spaces ko ignore karta hai.
2. **nowrap:** Text content ko ek line mein display karta hai aur extra spaces ko ignore karta hai.
3. **pre:** Whitespace ko maintain karta hai jaise ki text file mein likha hua ho.
4. **pre-line:** Newlines ko maintain karta hai lekin extra spaces ko ignore karta hai.
5. **pre-wrap:** Newlines ko maintain karta hai aur extra spaces ko bhi maintain karta hai.
Niche kuch examples diye gaye hain:

```
p {
  white-space: normal; /* Default behaviour */
}
```

```
pre {
  white-space: pre; /* Maintain whitespace like in text file */
}
```

```
div {
  white-space: nowrap; /* Display in single line */
}
```

```
blockquote {
  white-space: pre-wrap; /* Maintain newlines and extra spaces */
}
```

Is prakar se, **white-space** property ka istemal text content mein whitespace handling ko customize karne ke liye hota hai.