# 1. color

CSS (Cascading Style Sheets) mein color property text ka color define karne ke liye istemal hoti hai. Yeh property webpage ke text elements ko visually represent karne ke liye use hoti hai.

color property ko hexadecimal, RGB, RGBA, HSL, ya color ke naam ke roop mein define kiya ja sakta hai.

Niche kuch examples diye gaye hain:

1. **Hexadecimal Color**: Hexadecimal color code ek 6-digit code hota hai jisme R (Red), G (Green), aur B (Blue) values ka combination hota hai. Har digit 0 se 9 aur A se F tak kisi bhi combination ka ho sakta hai.

```
p {color: #FF5733; /* Orange color */}
```

2. **RGB Color**: RGB color code mein aap Red, Green, aur Blue values ka combination integer numbers (0 se 255) mein dete hain. Ye numbers ek comma ke saath likhe jate hain.

```
h1 {  color: rgb(0, 128, 255); /* Blue color */}
```

3. **HSL Color**: HSL ka matlab hai "Hue, Saturation, Lightness." HSL color model ek tareeka hai jisse colors ko define kiya jaata hai CSS mein. Is model mein rang ko "Hue" (udbhav), "Saturation" (saturayshan), aur "Lightness" (prakaar) ke parameters se describe kiya jaata hai.

Hue (Udbhav): Hue 0 se 360 degree ke beech mein hota hai aur rang ke adhyayan ko darshata hai. 0 degree red ke saman hota hai, 120 degree green ke, aur 240 degree blue ke.

Saturation (Saturayshan): Saturation 0% se 100% tak ki range mein hoti hai aur isse color ki vividness ya intensity ko darshaya jaata hai. 0% saturation grey tone ko dikhata hai, jabki 100% saturation vivid aur vibrant colors ko dikhata hai.

Lightness (Prakaar): Lightness bhi 0% se 100% range mein hoti hai aur isse color ka lightness ya darkness ko darshaya jaata hai. 0% lightness black ko, aur 100% lightness white ko represent karta hai.

HSL color model se color define karne ka ek udaharan:


```
p {color: hsl(210, 50%, 50%); /* Teal color */}
```