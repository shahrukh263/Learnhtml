### 01 a Tag:

Anchor tag ya hyperlink HTML mein ek aisa tag hai jo kisi dusre webpage, file ya section se link banane ke liye use kiya jata hai. 
Iske liye, hum href attribute ka istemal karte hain.

Ek basic example ke liye, agar hum ek hyperlink banana chahte hain jo Google ki website pe jaaye, toh hum is tarah se code likh sakte hain:

```
<a href="https://www.google.com">Google</a>
```

Is code mein `<a>` tag hyperlink ko represent karta hai, `href` attribute hyperlink ki URL ko specify karta hai, aur "Google" text link ke anchor text ko darshata hai.

Hum agar isko image ke saath bhi use karna chahein toh uske liye hum is tarah se code likh sakte hain:

```
<a href="https://www.google.com">
  <img src="google-logo.png" alt="Google logo">
</a>
```

Is code mein `<img>` tag image ko represent karta hai, `src` attribute image ki url ko specify karta hai, `alt` attribute image ke liye alternative text provide karta hai aur `<a>` tag image ko hyperlink mein wrap kar deta hai. 

Is tarah se hum HTML mein anchors ko use karke apne webpages mein links create kar sakte hain.

### 02 area Tag:
"area" tag HTML mein ek aisa tag hai jiski madad se hum "image maps" ko banate hain. Image map ka matlab hota hai ki ek image ke different parts par click karne 
se hum different links ya actions ko trigger kar sakte hain.

Example ke liye, maan lo ki humein ek image hai jismein 4 different sections hain. Har section par click karne se humare users ko alag-alag pages pe jaana hai. 
Toh hum "area" tag ka use karenge.

example code:

```
<img src="myImage.jpg" usemap="#myMap">

<map name="myMap">
  <area shape="rect" coords="0,0,100,100" href="page1.html">
  <area shape="rect" coords="100,0,200,100" href="page2.html">
  <area shape="rect" coords="0,100,100,200" href="page3.html">
  <area shape="rect" coords="100,100,200,200" href="page4.html">
</map>
```

Is code mein, "img" tag humein image show kar raha hai, aur "usemap" attribute mein humne map ka naam specify kiya hai. Map ka naam "myMap" hai.

Fir, "map" tag ke andar, humne "area" tag ka use kiya hai. Har "area" tag mein humne "shape" attribute mein rectangle shape specify ki hai, aur "coords" 
attribute mein rectangle ke coordinates diye hai. Iske baad, "href" attribute mein humne link ya action specify kiya hai 
jo ki uss area ke click hone par trigger hoga. Iss tarah se, hum "area" tag ka use karke ek image map bana sakte hain jise click karne par humare users 
different links ya actions ko trigger kar sakte hain.

### 03 aside Tag:
Aside tag HTML mein ek semantic tag hai jo content ko wrap karta hai jiski wajah se ye aur zyada readable aur structured banta hai. 

Ye tag typically article ya section ke saath use hota hai jahan humein additional information provide karni hoti hai, 
lekin wo content article ya section ke main flow se thoda alag ho. Ye information related ho sakta hai article ke author,
date, tags, categories, ya koi bhi addtional information jo user ke liye helpful ho.

Ek example ke tor par sochiye ki aap ek recipe website run kar rahe hain, to aapki recipes ke saath aap ingredients list, nutritional information, 
cookware suggestions, ya koi cooking tips bhi share karna chahte hain. In sabhi additional information ko aside tag ke andar rakh sakte hain. 

Yeh ek example  snippet hai jo is concept ko demonstrate karta hai:

```
<article>
  <h2>Pakistani Biryani Recipe</h2>
  <p>Ingredients: Rice, Chicken, Tomatoes, Onions, Spices</p>
  <p>Cooking Time: 45 minutes</p>
  
  <aside>
    <h3>Nutritional Information</h3>
    <ul>
      <li>Calories: 500</li>
      <li>Protein: 20g</li>
      <li>Fat: 10g</li>
      <li>Carbohydrates: 80g</li>
    </ul>
  </aside>
</article>
```

Is example mein, biryani recipe article aside tag ke andar Nutritional Information ke saath wrap kiya gaya hai. 
Ye information helpful hai readers ke liye jo diet aur nutrition par focus karte hain.