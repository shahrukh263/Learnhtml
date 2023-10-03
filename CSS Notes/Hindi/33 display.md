# 1. display

`display` CSS property element ka display behavior define karta hai, yani wo webpage par kis tarah se dikhayi dega. Is property se aap element ko `block, inline, inline-block`, ya other values ke roop mein display kar sakte hain.

Kuch commonly used `display` property values hote hain:

1. **block:** Element ek block-level element ki tarah behave karega, yani wo element ke baad new line shuru hoga aur uska full available width capture karega.

Example:

```
div.block-element {
  display: block;
}
```

2. **inline:** Element ek inline element ki tarah behave karega, yani wo element ke sath same line par rehkar sirf content ka width capture karega.

Example:

```
span.inline-element {
  display: inline;
}
```

3. **inline-block:** Element inline element ki tarah behave karega lekin uska `width, height`, aur `margin/padding` block element ki tarah set ho sakte hain.

Example:

```
button.inline-block-element {
  display: inline-block;
}
```

4. **none:** Element webpage par dikhayi nahi dega. Yani wo space nahi lega aur invisble ho jayega.

Example:


```
p.hidden-element {
  display: none;
}
```

5. **Other Block-level Values:** Jaise inline-table, list-item, table, table-cell, table-row, table-row-group, table-header-group, table-footer-group etc.

Example:

```
ul.list {
  display: list-item;
}
```

`display` property ke istemal se aap elements ko desired layout aur design ke according display kar sakte hain. Ye property layout management mein madad karti hai.