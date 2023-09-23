# 1. CSS box model

CSS Box Model ek concept hai jo HTML elements ke layout aur spacing ko define karta hai. Har HTML element ko ek box ke roop mein consider kiya jata hai jisme content, padding, border, aur margin shamil hote hain. Box Model se elements ke size, spacing, aur positioning ko control kiya jata hai.

Box Model ke components:

1. **Content**: HTML element ka actual content hota hai, jaise text, images, videos, etc.

2. **Padding**: Content aur border ke beech ka space hota hai. Padding element ka background color aur border se alag rakhne mein madad karta hai.

3. **Border**: Padding aur margin ke beech ka border hota hai. Border ka size, style, aur color define kiya ja sakta hai.

4. **Margin**: Border aur surrounding elements ke beech ka space hota hai. Margin ek element ko dusre elements se dur rakhne ke liye use hota hai.

CSS Box Model ek diagram se represent kiya jata hai:

```
+-------------------------+
|       Margin            |
|                         |
|  +-------------------+  |
|  |     Border        |  |
|  |                   |  |
|  |   +-----------+   |  |
|  |   |  Padding  |   |  |
|  |   |           |   |  |
|  |   |  Content  |   |  |
|  |   |           |   |  |
|  |   +-----------+   |  |
|  |                   |  |
|  +-------------------+  |
|                         |
+-------------------------+
```

Har HTML element ke liye Box Model ka arrangement hota hai. Aap **width**, **height**, **padding**, **border**, aur **margin** properties ka istemal karke Box Model ke components ko customize kar sakte hain.

Is prakar se, CSS Box Model HTML elements ke layout aur spacing ko define karne mein madad karta hai.