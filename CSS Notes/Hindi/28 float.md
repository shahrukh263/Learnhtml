# 1. float

`float` CSS property webpage ke elements ko left ya right side mein float (position) karne ke liye istemal hoti hai. Is property se aap elements ko normal flow se bahar lekar unhe horizontally align kar sakte hain.

`float` property ke alag-alag values hote hain:

1. **left:** Element ko left side mein float kiya jata hai. Isse element ke right side mein content flow hota hai.

/* Left Float */
div.left-float {
  float: left;
}

2. **right:** Element ko right side mein float kiya jata hai. Isse element ke left side mein content flow hota hai.

/* Right Float */
div.right-float {
  float: right;
}

3. **none:** Default value. Element ko float nahi kiya jata hai aur wo normal flow mein rehta hai.

/* No Float */
p.no-float {
  float: none;
}

4. **clear:** Agar aap ek element ko clear property ke sath use karte hain, toh wo element float elements ke sath conflict ko handle karta hai aur specified side se float elements ko clear karta hai.

/* Clear Float */
div.clear-float {
  clear: both;
}


Is prakar se, `float` property ka istemal elements ko left ya right side mein float karne ke liye hota hai. Ye property layout aur design mein madad karta hai, lekin modern CSS approaches mein float ki jagah flexbox aur grid jaise techniques ka upayog kiya jata hai.