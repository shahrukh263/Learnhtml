

### 01 form Tag: 

HTML mein 'form' tag ka upyog ek form ya anumati prapt karne ke liye hone wale dastavej ko web page par shamil karne ke liye kiya jata hai. 
Form tag ke andar input fields, buttons aur dusre elements shamil hote hain jinhe user bharega ya chune ga.

Mukhya form attributes hain 'action' aur 'method'. 'Action' attribute mein aap form data ko bhejne ke liye server-side script ka URL specify kar sakte hain 
aur 'method' attribute mein aap ye tay kar sakte hain ki form data ko GET ya POST method se bheja jaye.

Yahan ek udaharan diya gaya hai:

```
<form action="/submit-form.php" method="POST">
  <label for="name">Naam:</label>
  <input type="text" id="name" name="user_name"><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="user_email"><br><br>
  <label for="message">Sandesh:</label>
  <textarea id="message" name="user_message"></textarea><br><br>
  <input type="submit" value="Submit">
</form>
```

Is example mein humne form tag se ek contact form banaya hai. Jab user submit button par click karta hai toh form data /submit-form.php page par POST method ke 
zariye bheja jata hai. Is form mein naam, email aur sandesh ke liye input fields, aur submit button shamil hain.

### 02 input Tag: 
#### 1 input text:

Input type text ka upyog form me text input lene ke liye kiya jaata hai. Jab bhi hum kisi HTML form me text field add karte hai 
toh input type text ka use kiya jaata hai. Isme user ko ek box diya jaata hai, jisme wo apna naam, ya kuchh bhi text enter kar sakta hai.

Iska syntax is tarah hota hai: 
```
<input type="text" name="fieldname" id="fieldid">
```
Yahaan "fieldname" aur "fieldid" aapke text field ke naam aur ID hote hain. Aapko inhe khud hi customize karna padega.

Iske alawa, aap is element ke andar placeholder attribute ka upyog bhi kar sakte hai. Ye attribute user ko ye bataane ke liye hota hai ki wo isi field me 
kya enter karega. Jaise ki:
```
<input type="text" name="FirstName" placeholder="Enter your First Name" >
```
#### 2 input email:

"input type=email" ek aisa attribute hai jo email address ke liye input field ko define karta hai. Jab bhi koi user email address enter karta hai, 
toh is attribute ka use karke validate karna bahut easier ho jata hai.

Jaise ki:

```
<form>
  <label for="email">Email address:</label>
  <input type="email" id="email" name="email">
</form>
```

Is HTML code mein humne "input type email" ka use kiya hai. Yahan par "label" tag se email address ke label ko define kiya gaya hai aur "input type email" 
tag mein email address ko enter karne ke liye field create kiya gaya hai.

Jab user form submit karega, toh browser automatically email address format check karega aur agar email address invalid hoga toh error message show karega.

Is tarah se "input type email" attribute ka use karke email address validation bahut easily handle kiya ja sakta hai.

#### 3 input button:

"input type=button" ek tarika hai jisse hum ek button ko create kar sakte hai. Ye button HTML form mein use kiya jaata hai, jaise ki submit button ya 
phir kisi action ko trigger karne ke liye.

Iske liye, HTML mein input tag ka use kiya jaata hai, aur type attribute ko "button" value se set kiya jaata hai. Iske baad, button par dikhega jo bhi text aap 
input tag ke andar daalte hai.

Yahaan ek example diya gaya hai:

```
<input type="button" value="Click Here">
```

Is code mein, humne input tag ka use kiya hai, type attribute ko button se set kiya hai aur value attribute mein "Click Here" text diya hai.
Jab aap is code ko browser mein run karenge, toh aapko "Click Here" wala button dikhega.

Iske alawa, aap input tag ke andar onclick attribute ka use karke bhi button click karne ke baad koi action trigger kar sakte hai. Jaise ki,

```
<input type="button" value="Submit" onclick="alert('Form Submitted!')">
```

Is code mein, humne onclick attribute ke andar JavaScript ka use kiya hai, aur jab bhi user Submit button par click karega, 
toh ek alert box dikhayi dega jisme "Form Submitted!" message likha hoga.

#### 4 input checkbox:

Input type checkbox HTML me ek tarah ka form element hota hai jo user ko multiple options me se ek ya ek se jyada options select karne ki anumati deta hai. 
Iska use generally forms me kiya jata hai jaha user ko apni preference choose karne ki jarurat hoti hai.

Iske liye hume input tag ka use karna hota hai, jisme type attribute ko "checkbox" set karna hota hai. Ye attribute ye bhi decide karta hai ki ye element checkbox hoga. 

Mudda samajhne ke liye, ek example ke through samjhte hain:

```
<form>
  <label for="sabzi">Kounsi sabziyan pasand hain?</label><br>
  <input type="checkbox" id="sabzi1" name="sabzi[]" value="palak">
  <label for="sabzi1">Palak</label><br>
  <input type="checkbox" id="sabzi2" name="sabzi[]" value="matar">
  <label for="sabzi2">Matar</label><br>
  <input type="checkbox" id="sabzi3" name="sabzi[]" value="bhindi">
  <label for="sabzi3">Bhindi</label><br>
</form>
```

Iss example me humne ek form banaya hai jisme user ko choose karne ke liye kuch sabziyon ka option diya gaya hai. Sabse pehle `<label>` tag se uss option ka label 
banate hain jisse ki user ko ye pata chal sake ki ye element kis cheez ka hai. Fir input tag me type attribute ko checkbox set kiya hai. 
Ye attribute ye bhi decide karta hai ki ye element checkbox hoga. Iss example me humne id, name aur value attribute ko set kiya hai jisse ki form ke backend me 
inke naam se access kiya ja sake.

#### 5 input color:
Example: 
```
<input type="color">
```
#### 6 input date:
Example: 
```
<input type="date">
```
#### 7 input datetime-local:
Example: 
```
<input type="datetime-local">
```
#### 8 input file:
Example: 
```
<input type="file">
```
#### 9 input hidden:
Example: 
```
<input type="hidden">
```
#### 10 input image:
Example: 
```
<input type="image">
```
#### 11 input month:
Example: 
```
<input type="month">
```
#### 12 input number:
Example: 
```
<input type="number">
```
#### 13 input password:
Example: 
```
<input type="password">
```
#### 14 input radio:
Example: 
```
<input type="radio">
```
#### 15 input range:
Example: 
```
<input type="range">
```
#### 16 input reset:
Example: 
```
<input type="reset">
```
#### 17 input search:
Example: 
```
<input type="search">
```
#### 18 input submit:
Example: 
```
<input type="submit">
```
#### 19 input tel:
Example: 
```
<input type="tel">
```
#### 20 input time:
Example: 
```
<input type="time">
```
#### 21 input url:
Example: 
```
<input type="url">
```
#### 22 input week:
Example: 
```
<input type="week">
```

### 03 label Tag:
### 04 select Tag:
### 05 option Tag:
### 06 optgroup Tag:
### 07 output Tag:
### 08 datalist Tag:
### 09 legend Tag:
### 10 fieldset Tag:
### 11 button Tag:
### 12 textarea Tag: