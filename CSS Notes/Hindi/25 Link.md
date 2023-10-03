# 1. link

Anchor links, ya `<a>` tags, HTML mein hyperlinks ko represent karte hain. Yeh hyperlinks text, images, ya other elements ko dusre web pages, documents, resources, ya locations tak link karne ke liye istemal hote hain. Jab user in par click karta hai, toh associated URL par redirect ho jata hai.

Niche ek anchor link ka simple example diya gaya hai:


```<a href="https://www.example.com">Visit Example Website</a>```

1. **link:** Yeh pseudo-class unvisited anchor links ko target karta hai. Iske dwara aap unvisited links ke liye color aur text decoration set kar sakte hain.

Example:

```
a:link {
  color: blue; /* Blue color for unvisited links */
  text-decoration: underline; /* Underline unvisited links */
}
```

2. **visited:** Yeh pseudo-class visited anchor links ko target karta hai, jo pehle se visit kiye gaye hote hain. Iske dwara aap visited links ke liye color aur text decoration set kar sakte hain.

Example:

```
a:visited {
  color: purple; /* Purple color for visited links */
}
```

3. **hover:** Jab mouse pointer link par hover karta hai, toh yeh pseudo-class link ko target karta hai. Iske dwara aap links ke hover state ke liye style define kar sakte hain.

Example:

```
a:hover {
  color: red; /* Red color for hovered links */
  text-decoration: none; /* Remove underline on hover */
}
```

4. **active:** Jab link ko click karte waqt, toh yeh pseudo-class link ko target karta hai. Iske dwara aap links ke active (click) state ke liye style define kar sakte hain.

Example:

```
a:active {
  color: green; /* Green color for active links */
}
```

In pseudo-classes ko istemal karke aap anchor links ko **unvisited, visited, hover, aur active** states mein visually customize kar sakte hain. Isse users ko interaction ke baare mein feedback milta hai aur web page ka user experience behtar hota hai.