# 1. Pseudo-elements

`Pseudo-elements` CSS selectors hote hain jo element ke specific parts, jaise ke content, before, ya after, par apply hote hain. `Pseudo-elements` actual DOM (Document Object Model) mein exist nahi karte, lekin aap unko use karke element ke parts ko CSS ke through style kar sakte hain.

`Pseudo-elements` ke syntax mein :: ka upayog hota hai (lekin older versions of CSS mein : bhi use ho sakta hai). Niche kuch commonly used `pseudo-elements` diye gaye hain:

1. **::before:** Is pseudo-element se aap element ke content ke pehle ek virtual element create kar sakte hain aur us par styles apply kar sakte hain.

Example:

```
p::before {
  content: ">> "; /* Adds ">> " before every <p> element's content */
  font-weight: bold;
}
```

2. **::after:** Is pseudo-element se aap element ke content ke baad ek virtual element create kar sakte hain aur us par styles apply kar sakte hain.

Example:

```
a::after {
  content: " (link)";
  color: gray;
}
```

3. **::first-line:** Is pseudo-element se element ke first line par styles apply kar sakte hain.

Example:


```
h1::first-line {
  font-size: 1.5em;
  color: blue;
}
```

4. **::first-letter:** Is pseudo-element se element ke first letter par styles apply kar sakte hain.

Example:


```
p::first-letter {
  font-size: 1.2em;
  color: red;
}
```

5. **::marker:** ::marker pseudo-element se aap ordered (`<ol>`) aur unordered (`<ul>`) lists ke liye list item ke markers (bullets ya numbers) ko style kar sakte hain.

Example:

```
li::marker {
  color: red; /* List item markers will be red */
}
```

6. **::selection:** ::selection pseudo-element se aap text selection ko style kar sakte hain. Yani jab user text ko select karta hai, toh us selected text ka background color aur text color change kar sakte hain.

Example:

```
::selection {
  background-color: yellow; /* Selected text will have yellow background */
  color: black; /* Selected text will have black text color */
}
```

`Pseudo-elements` ka istemal karke aap element ke specific parts ko style karke creative designs aur effects create kar sakte hain. Isse aap typography aur layout ko bhi customize kar sakte hain.