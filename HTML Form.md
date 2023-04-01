

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
Example: 
```
<input type="email">
```
#### 3 input button:
Example: 
```
<input type="button">
```
#### 4 input checkbox:
Example: 
```
<input type="checkbox">
```
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