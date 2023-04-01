# 1. What is HTML?
HTML ek markup language hai jo web pages banane ke liye istemal ki jati hai. HTML ka full form "HyperText Markup Language" hai. Iski madad se, hum text, images, videos, links aur baqi sabhi tarah ke content ko web page par dikhate hain.

HTML me tags ka istemal hota hai jinhe angle brackets (<>) ke bich likha jata hai. Har tag kuch na kuch kaam karta hai, jaise ki text ko bold ya italic karne ke liye <b> aur <i> tag ka istemal hota hai.

For example, agar hum chahte hain ki kuch text bold ho to hum <b> tag ka istemal karenge. Jaise ki: 
```
<p>Mera naam ChatGPT hai aur main ek AI model hun.</p>
<p><b>Main bahut intelligent hun!</b></p>
```
Is code me, <p> tag ka istemal para likhne ke liye kiya gaya hai. Dusre <p> tag ke andar <b> tag ka istemal kiya gaya hai jisse ki "Main bahut intelligent hun!" wale text ko bold kar diya gaya hai.

Aise hi alag-alag tags ka istemal karke, hum apne web pages ko aur bhi sundar aur useful bana sakte hain.
# 2. What is XHTML?
XHTML ek markup language hai jise HTML ki tarah hi use kiya jaata hai. Iska poora naam "Extensible Hypertext Markup Language" hai, aur isme HTML ke saare rules aur tags ko follow kiya jaata hai. Yah language XML syntax ka upyog karti hai, isliye ise "X" se shuru kiya jaata hai.

Jaise ki HTML me, XHTML bhi web pages ko design karne ke liye use kiya jaata hai. Isme hum text, images, links, tables, forms aur videos ko create kar sakte hain. Yeh browser-friendly hai aur cross-platform compatibility provide karta hai.

Example:
```
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>Hello World</title>
</head>
<body>
    <h1>Mera Pehla Web Page</h1>
    <p>Is page ke liye maine XHTML ka upyog kiya hai.</p>
</body>
</html>
```
Is example me, DOCTYPE XHTML ka version define karta hai jo ki Transitional version hai. Head section me title tag hai jisme page ka title diya gaya hai. Body section me h1 aur p tag hai jisme content dikhaya ja raha hai.

# 3. What is an HTML Element?

HTML ek markup language hai jo web pages ke structure ko define karta hai. HTML element ek tag hota hai jo web page ka particular section ko represent karta hai.
Har HTML element ka apna tag hota hai jismein "open tag" aur "close tag" hote hain. open tag mein angle brackets ke beech mein element ka naam hota hai aur 
close tag mein bhi wohi naam hota hai lekin usse pehle slash (/) ka use kiya jaata hai.

For example, agar aapko ek paragraph likhna hai toh aap ```<p> </p>``` tags ka use kar sakte hain. Jaise ki:
```
<p>Yeh ek example hai.</p>
```
Ismein ```<p>``` opening tag hai aur ```</p>``` closing tag hai. Text jo bhi paragraph mein aayega woh dono tags ke beech mein hi hoga. 
Isi tarah se HTML ke bahut saare elements hote hain jaise headings, images, links, tables, lists, etc.


# 4. What are Tags?

HTML tags hote hai jo humare web page ko structure, format aur style dene me madad karta hai.

Har HTML tag ke do parts hote hai- opening tag aur closing tag. Opening tag angle brackets ke andar hota hai jisme tag ka naam hota hai, jaise 
```<p>``` paragraph tag ke liye. Closing tag bhi angle brackets ke andar hota hai, lekin usme / ka use hota hai, jaise ```</p>``` paragraph tag ka closing tag.

For example, agar hum ek paragraph create karna chahte hai toh hum ```<p>``` tag ka use kar sakte hai, jaise:

```<p>Yeh ek example paragraph hai.</p>```

Is example me ```<p>``` opening tag hai jo paragraph start karne ke liye istemal kiya gaya hai, aur ```</p>``` closing tag hai jo paragraph ko khatam karne ke 
liye use kiya gaya hai.

Is tarah se, HTML tags ka istemal karke hum apne web pages ko structure diya ja sakta hai, 
jaise headings ke liye ```<h1> - <h6>``` tags, links ke liye ```<a>``` tag, images ke liye ```<img>``` tag, aur bahut sare aur bhi tags hai jo humare
web pages ko design karne me help karte hai.
# 5. What are Attributes?

HTML mein “attributes” wo hote hai jo tags ko aur bhi mukammal karte hai. Ye tags ke andar likhe jate hai, aur inka use kisi 
specific information ko tag ke sath link karne ke liye hota hai.

Sabse aam attribute hai "class" attribute, jo elements ko CSS ke sath style karne ke liye use kiya jata hai. Iske alawa, 
"id" attribute ka use bhi ek unique identifier ke taur par kiya jata hai. Aur iske alava bhi bahut saare attributes hote hai, 
jaise "href" (links ke liye), "src" (images aur other media ke liye), "alt" (image ka alternate text), "title" (tooltip ke liye), etc.

Yaha ek example hai: 

Suppose aapko ek paragraph ko bold karne ki zarurat hai, toh aap <strong> tag ka use kar sakte hai. Lekin agar aap chahte hai ki 
  sirf particular paragraph hi bold ho to aap class attribute ka use kar sakte hai. Jaise:

```<p class="important">Ye paragraph bold hoga</p>```
  
```<p>Ye paragraph normal rahega</p>```

CSS mein, aap "important" class ko select karke usko bold style de sakte hai:

```
  <style>
  .important {
    font-weight: bold;
}
 </style>
```

Is tarah se, aap HTML attributes ka use karke apne web pages ko aur bhi zyada detailed aur appealing bana sakte hai.