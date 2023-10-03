# 1. border-radius

`border-radius` CSS property se aap ek element ke corners ko rounded (golakar) bana sakte hain. Is property se aapko rectangular elements ko bhi circular ya elliptical shape mein convert karne ki flexibility milti hai.

`border-radius` property ki value mein pixels, percentages, aur fractions ka upayog hota hai. Agar aap ek value specify karte hain toh wo value element ke char corners par apply hoti hai. Agar aap do values specify karte hain (e.g., `border-radius: 10px 20px;`), toh pehli value `top-left` aur `bottom-right` corners par apply hoti hai, aur doosri value top-right aur bottom-left corners par apply hoti hai.

Niche kuch examples diye gaye hain:

```
/* Rounded Corners for a Square */
div.square {
  width: 100px;
  height: 100px;
  background-color: lightblue;
  border-radius: 10px; /* All corners will be rounded */
}
```

```
/* Elliptical Shape */
div.ellipse {
  width: 150px;
  height: 100px;
  background-color: lightgreen;
  border-radius: 75px 25px; /* Horizontal radius, Vertical radius */
}
```

Is prakar se, `border-radius` property ka istemal element ke corners ko rounded banaane ke liye hota hai. Ye property visual design mein flexibility aur creativity ko enhance karti hai.