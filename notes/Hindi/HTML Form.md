

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

HTML mein "input type color" ek aisa form element hai jiski madad se humein color ka chunav karne ki suvidha milti hai. 
Ismein ek color picker hota hai jismein aap apni pasandeeda color ko chun sakte hain.

Iska upyog jaise ki website design, logo design ya phir kisi bhi prakar ke graphics banane ke liye kiya ja sakta hai. 
Iske liye aapko bas input tag mein type="color" attribute ka upyog karna hoga.

Neeche diye gaye HTML code  mein, ek input field dikhaya gaya hai jismein color picker available hai:

```
<form>
	<label for="color-picker">Choose your favorite color:</label>
	<input type="color" id="color-picker" name="color-picker">
</form>
```

Iss code  mein, label tag ke dwara ek text message aur input tag ke dwara ek color picker dikhaya gaya hai. 
Aap isse copy karke apne project mein istemaal kar sakte hain.



#### 6 input date:

HTML mein "input type date" ek aisa attribute hai jo hum form elements ke liye use karte hai jahan user ko date select karna hota hai. Is attribute se, 
users ki input format ko standardize karne mein help milta hai.

Example ke liye, agar aap ek form create karna chahte hai jismein birthday field ho toh, aap is tarah ka code use kar sakte hai:

```
<label for="birthday">Janam Din:</label>
<input type="date" id="birthday" name="birthday">
```

Iss code se ek label aur date input field banega jismein user janam din select kar sakta hai. Input field ki value format yyyy-mm-dd mein hogi aur ye browser ke default 
calendar widget se select ki ja sakti hai.

#### 7 input datetime-local:
HTML mein "input type datetime-local" ek aisa attribute hai jisko form elements ke liye use kiya ja sakta hai. Is attribute ke through user ko ek date aur time picker 
diya jata hai, jisse wo apne preferred date aur time ko select kar sakte hain.
Is attribute se related example neeche diya gaya hai:

```
<label for="myDateTime">Select Date and Time: </label>
<input type="datetime-local" id="myDateTime" name="date_time">
```

Is prakar se, hum "input type datetime-local" attribute ke through date aur time pick karne ke liye form element create kar sakte hain.
#### 8 input file:
Input type file ek HTML element hai jo humein file upload karne ki anumati deta hai. Isse hum apne web page mein file browse aur select kar sakte hain.

Iska use karna bahut hi aasan hai. Input tag mein type="file" set karein aur phir name attribute mein koi naam de dein, 
jisse server ke dwara file ko identify kiya ja sake.

Yahan ek udaharan diya gaya hai:
```
<form action="/upload" method="post" enctype="multipart/form-data">
  <label for="file-upload">Choose a file:</label>
  <input type="file" id="file-upload" name="myFile">
  <input type="submit" value="Upload">
</form>
```
Is HTML code mein, form tag ka action attribute server ke URL ko point karta hai jahaan file upload kiya jayega. 
Method attribute "POST" hai kyunki humein file ko server par POST request bhejna hai. enctype attribute multipart/form-data hai kyunki hum file upload kar rahe hain.

Input tag mein type attribute "file" hai, jo file ko choose karne ki anumati deta hai. Id attribute "file-upload" input field ko label ke saath connect karta hai.
Name attribute "myFile" server ke liye file ko identify karne ke liye istemaal kiya jata hai.

Ek baar jab hum submit button par click karte hain, selected file ko server par upload kiya jata hai.
#### 9 input hidden:

"input type hidden" ek HTML tag hai jo web developers ki madad se user se chhupi hui jaankari ko server ke saath bhejne mein upyog kiya jaata hai. 
Is tag ka upyog user dwara na dekhi jaane waale input fields jaise session ID, CSRF tokens ya kisi bhi data ko form mein chhupane ke liye kiya jaata hai.

Is tag ka upyog karne ke liye, "input" tag ka upyog kiya jaata hai aur usmein "type=hidden" attribute ko set kiya jaata hai. 
Ye tag HTML code mein dikhai nahi deta hai, lekin browser ke view source option se iska pata lagaaya ja sakta hai. 

Yahaan ek udaharan diya gaya hai:
```
<form action="submit.php" method="post">
  <input type="text" name="username" placeholder="Enter username" required>
  <input type="password" name="password" placeholder="Enter password" required>
  <input type="hidden" name="csrf_token" value="random_string_of_characters">
  <button type="submit">Submit</button>
</form>
```

Is example mein, "csrf_token" naam ka hidden input field hai jis mein ek random string value ko store kiya gaya hai. 
Ye token server ke dwara form submit karne ke samay verify kiya jaata hai taaki kisi bhi unauthorized access se bacha ja sake.
#### 10 input image:

HTML mein, "input type = image" ka upyog ek button ya submit ke roop mein, ek chitr ke saath karna hai. Jab is button par click kiya jata hai, 
tab wo "form" ko submit karega. 

Yahaan ek udaharan diya gaya hai:

```
<form action="process.php" method="post">
   <label for="username">Username:</label>
   <input type="text" name="username"><br><br>
   <label for="password">Password:</label>
   <input type="password" name="password"><br><br>
   <input type="image" src="submit.png" alt="Submit">
</form>
```

Is udaharan mein, humne ek form banaya hai jismein do input fields hain (username and password) aur ek submit button hai.
Submit button ke liye, humne "input type=image" ka upyog kiya hai, jo ek chitr ke saath sanchalit hota hai ("submit.png"). 

Jab is button par click kiya jata hai, tab wo form ko submit kar dega aur process.php page ko call karega.  Yadi koi validation errors honge toh, phir use wapis form pe bulaya ja sakta hai.
#### 11 input month:

HTML mein input type month ka upyog karke hum ek maah (month) ka chayan (selection) karte hain. Iske liye HTML ke andar input tag ka upyog kiya jata hai. 

Isko istemal karne ke liye, aapko input tag ke type attribute ko "month" me set karna hai:

`<input type="month">`

Jab yeh code browser mein render hota hai toh, ek calendar widget display hota hai jismein saal aur maah select karne ki suvidha hoti hai. 
Yadi user ismein se koi bhi maah chunta hai, toh uss value ko yyyy-mm format mein submit kiya jata hai.

For example, agar user May 2023 select karta hai, toh submit hone waali value "2023-05" hogi.
#### 12 input number:

Input type number HTML mein ek form element hai jo numeric input accept karta hai. Ye input field user dwara numeric values ke liye use kiya jata hai jaise ki age, 
quantity, price, etc. Ismein user only numerical characters hi enter kar sakta hai aur iske saath saath ismein arrow buttons bhi hote hain, 
jisse user value ko ek digit ki increment ya decrement kar sakta hai.

Example ke liye, agar hume ek form banana hai jisme user apni umar daale toh uss form ke HTML code mein hum input tag ka use karenge aur type attribute mein 'number' 
likhenge. Jaise niche diya gaya hai:

```
<form>
  <label for="age">Aapki Umar:</label>
  <input type="number" id="age" name="age" min="18" required>
</form>
```

Is example mein humne input type number ka use kiya hai. Humne input ka id 'age' and name 'age' set kiya hai taki ye form submit hone par server ke dwara access kiya
ja sake. Humein minimum age '18' deni hai, isliye humne min attribute ka use kiya hai. Aur last me required attribute ka use kiya hai jisse ye form submit nahi hoga 
jab tak ki user age field ko fill na kare.

#### 13 input password:

HTML mein 'input type password' ka upyog ek form field banane ke liye kiya jata hai jismein user ko apna password enter karna hota hai. 
Ye field user ke dwara diye gaye characters ko masked (chhupaya) kar dikhate hain, taaki koi anya vyakti un characters ko padh na sake.

Is field ka upyog ek simple HTML tag ke madhyam se kiya ja sakta hai -

```
<input type="password" name="password">
```

Yahan par `type` attribute mein "password" value diya jata hai, jo is field ko password field bana deta hai. Saath hi, `name` attribute ke madhyam se yeh field 
form submit hone par server tak pahunchega.

Example ke tor par, agar hum ek login form banana chahte hain jismein username aur password ki input fields ho, to uska HTML code kuch is tarah se dikhega -

```
<form action="/login" method="post">
  <label for="username">Username:</label>
  <input type="text" name="username" id="username"><br>

  <label for="password">Password:</label>
  <input type="password" name="password" id="password"><br>

  <input type="submit" value="Log in">
</form>
```

Iss example mein humne `input` tags ka upyog karke do form fields create kiye hain - ek text field "username" aur dusra password field "password". 
Saath hi, humne ek submit button bhi add kiya hai, jise click karne par form submit ho jayega.
#### 14 input radio:

HTML mein "input type radio" ek form element hai, jo user ko kuch options mein se ek option ko chunne ki suvidha deta hai. Iska upyog generally multiple choice 
questions aur surveys mein kiya jaata hai. Ismein ek group mein multiple radio buttons hote hain, jahan har button ke liye ek unique value hota hai. 
Jab user kisi ek button par click karta hai toh us button ki value server ke saath bheji jaati hai.

Neeche diye gaye example mein, 3 radio buttons ka group banaya gaya hai jismein user apna favourite colour chun sakta hai:

```
<form>
  <input type="radio" id="red" name="color" value="red">
  <label for="red">Laal</label><br>
  <input type="radio" id="blue" name="color" value="blue">
  <label for="blue">Neela</label><br>
  <input type="radio" id="green" name="color" value="green">
  <label for="green">Hara</label><br>
</form>
```

Iss example mein, "name" attribute same radio buttons ke group ko identify karne mein help karta hai aur "value" attribute each radio button ko uniquely identify 
karta hai. "label" tag radio button ke saath associate label ko darshata hai.
#### 15 input range:

Input type range HTML mein ek tarah ka input control hai jo ek slider jaisa dikhta hai. Aap isse use karke user se numerical values ko select karne ki anumati 
de sakte hain. Iska syntax kuch is tarah hota hai:

```
<input type="range" min="0" max="100" step="1">
```

Yahan `type` attribute mein "range" value diya gaya hai, jo batata hai ki ye ek range input type hai. `min` attribute mein minimum value di gayi hai,
`max` attribute mein maximum value di gayi hai, aur `step` attribute mein ek step size di gayi hai, jiske anusaar slider ko chalaya ja sakta hai.

Is input control ke through aap user se kisi bhi numeric value ko select karne ki anumati de sakte hain, jaise ki volume level, brightness level, ya phir koi 
rating scale. Ye control bahut hi flexible hai aur iske style ko CSS ke dwara customize kiya ja sakta hai.
#### 16 input reset:

Input type reset HTML mein ek form element hai jo ek button ki tarah behave karta hai aur ek form ke sabhi fields ko apni default value par reset kar deta hai.

Iski syntax is tarah se hoti hai:
```
<input type="reset" value="Reset">
```

Ismein "type" attribute mein "reset" value set kiya jata hai aur "value" attribute mein button par show hone wale text ko set kiya jata hai.

Example: Agar aap ek contact form bana rahe hain jismein naam, email aur message ka input fields hote hain, toh aap "reset" button use karke saare fields ko 
reset kar sakte hain. Jaise:

```
<form>
  <label for="name">Naam:</label>
  <input type="text" id="name" name="name"><br><br>
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>
  
  <label for="message">Message:</label>
  <textarea id="message" name="message"></textarea><br><br>
  
  <input type="submit" value="Submit">
  <input type="reset" value="Reset">
</form>
```

Is example mein, jab user "Reset" button par click karega toh saare fields blank ho jayenge aur default value par reset ho jayenge.
#### 17 input search:

"input type search" ek HTML attribute hai jo ki text box ko search input ke taur par define karta hai. Jab aap input element me "type=search" attribute use karte hain,
toh usmein ek search icon bhi automatically generate ho jaata hai jisse user easily search kar sakta hai.

Yeh attribute mostly search engines ya fir website mein search box ke liye use hota hai. Isko istemal karne se user ko apni zaroorat ke mutabik results mil jaate hain. 

Example:
```
<form>
  <label for="search">Search:</label>
  <input type="search" id="search" name="search" placeholder="Search for...">
</form>
```

Is HTML code mein "input type=search" attribute ka upyog kiya gaya hai. Yahan "id" aur "name" attributes search box ke liye unique identifier ke roop mein use kiye gaye
hain. "placeholder" attribute ke dwara hum search box mein pre-filled text show kar sakte hain.
#### 18 input submit:

"input type submit" HTML tag ka upyog kisi bhi form ko submit karne ke liye karte hai. Jab user form ko fill karke submit button par click karta hai, 
toh form ke data server ya phir client-side scripting ki madad se submit ho jaate hai.

Yeh tag simple text ya images ke saath submit button create karne ke liye istemal kiya jaata hai. Iske attributes mein value attribute hota hain jismein 
submit button ke naam ya text define kiya jaata hai. 

Example:
```
<form action="submit.php">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name"><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>
  <input type="submit" value="Submit">
</form>
```

Is example mein, "input type submit" tag ko submit button ke roop mein istemal kiya gaya hai form ko submit karne ke liye. "value" attribute mein "Submit" 
text set kiya gaya hai, jo button ke text ke roop mein dikhai dega.
#### 19 input tel:
HTML mein "input type tel" ek input form field hai jo sirf mobile number ki entry ke liye use hota hai. 
Iski madad se user apna mobile number enter kar sakta hai aur ye number browser mein display hota hai.

Iski syntax ya code kuch is tarah hai: 

```
<input type="tel" name="mobile_number" placeholder="Mobile Number">
```

Yahan, `type` attribute mein "tel" value diya gaya hai jo batata hai ki ye field mobile number ke liye hai. 
`name` attribute mein "mobile_number" likha gaya hai jo server ko bheja jayega jab form submit hoga. `placeholder` attribute mein "Mobile Number" 
likha hai jo field ke andar blank text box ke jagah dikhayi dega.

#### 20 input time:

HTML mein "input type time" ek form element hota hai jiski madad se hum user ko sahi samay ka input lene mein madad kar sakte hain. 
Ismein user samay ko hour, minute aur second ke roop mein select kar sakta hai.

Iska basic syntax yeh hai:

```
<input type="time" name="samay">
```

Yahaan "type" attribute mein "time" value diya jaata hai aur "name" attribute mein uska naam "samay" rakha gaya hai.

Jab user is form element mein click karega toh ek pop-up calendar open hoga jismein user samay ko select kar sakega. 
Jaise ki neeche diye gaye example mein dikhaya gaya hai:

```
<form>
  <label for="samay">Samay:</label>
  <input type="time" id="samay" name="samay">
</form>
```

Iss example mein "for" attribute ka upyog label element se input element ko link karne ke liye kiya gaya hai.

Jab user form submit karega toh input element ke selected value ko form data ke roop mein submit kiya jayega.
#### 21 input url:

Input type "url" HTML mein ek attribute hai jo use hota hai URL ko input field ke through user se collect karne ke liye. 
Jab hum URL ke liye input field create karte hain, toh isse user-friendly experience provide hota hai kyunki aise user ko apna URL manually type karne ki jarurat 
nahi padti hai.

Is attribute ka use generally form submit karne ke liye kiya jata hai. Input type "url" ka syntax niche diya gaya hai:

```
<input type="url" name="url_field_name">
```

Yahan "name" attribute, URL ko identify karne ke liye use hota hai jab data server ke taraf send kiya jata hai.

Example ke roop mein, agar aapko apne website mein user se unke website ka URL collect karna hai, toh aap input type "url" ka use kar sakte hain. 
Niche diye gaye code  mein aap dekh sakte hain ki kaise aap input type "url" ka use kar sakte hain:

```
<form action="submit.php" method="post">
  <label for="website_url">Apni website ka URL add karein:</label>
  <input type="url" id="website_url" name="website_url" required>
  <button type="submit">Submit</button>
</form>
```

Is example mein, "id" attribute "for" attribute ke saath use kiya gaya hai taaki label or input field ko associate kiya ja sake. 
"required" attribute, yeh validate karta hai ki user ne URL enter kiya hai ya nahi.

#### 22 input week:

"input type week" ek HTML form element hai jiski madad se user se hafto ke naam ya dates ko input karne ki suvidha pradaan ki jaati hai. 
Iska upyog hum kisi bhi form mei kar sakte hai, jis mein weekly data ka input liya jata hai.

Ismein "week" attribute hota hai jo date format ko define karta hai. Ye attribute "yyyy-Www" format mei hota hai jismein "yyyy" saal aur "Www" week number hota hai.

Yahan ek udaharan diya gaya hai:

```
<label for="weekly-data">Hafta chune:</label>
<input type="week" id="weekly-data" name="weekly-data" min="2023-W01" max="2023-W52">
```

Is example mein humne ek text label banaya hai jismein user ko prompt kiya hai ki wo "Hafta chune" (Select Week) aur uske baad "input type week" ka element hai 
jiske id "weekly-data" hai. Humne ismein "min" aur "max" attributes bhi diye hai jo user ko saal ki shuruaat aur ant tak ki range batate hai
jismein wo weekly data select kar sakta hai.

### 03 label Tag:
HTML mein "label" ek tag hai jo form field ke saath joda jaata hai, jisme uss field ke liye text label hota hai. 
Yeh user ko batata hai ki woh kis field ko fill kar raha hai.

Iska ek simple example hai:

```
<label for="username">Username:</label>
<input type="text" id="username" name="username">
```

Yahan par "label" tag ka upyog username field ke saath kiya gaya hai. Label tag ke "for" attribute mein username field ka id diya gaya hai jisse label aur 
field connect ho jayein aur user ko pata chale ki yeh field ke liye hai.

Iss code mein "Username:" label text hai jo user ko batata hai ki yeh field username ke liye hai.

### 04 select Tag:

Select tag HTML mein ek bahut hi jaruri tag hai, jo dropdown menu banane ke liye use kiya jata hai. Is tag ke help se user kisi bhi ek option ko select kar sakta hai.

Yah tag 2 parts me divide hota hai - select tag and option tag. Select tag dropdown menu ko define karta hai aur option tag menu ke options ko define karte hain.

Example ke roop mein, agar aap ek HTML form bana rahe hain aur usmein ek dropdown menu add karna chahte hain jismein 'Fruit' aur 'Vegetable' options hon, 
to iske liye aap is tarah ka code use kar sakte hain:

```
<form>
<label for="food">Choose your food:</label>
<select id="food" name="food">
<option value="fruit">Fruit</option>
<option value="vegetable">Vegetable</option>
</select>
</form>
```

Is code mein, `label` tag dropdown menu ke name ko describe karta hai, `select` tag menu ko define karta hai, `option` tags dropdown menu ke options ko 
define karte hain, `value` attribute selected option ki value ko store karti hai aur `name` attribute selected option ko server ke saath send karta hai.

### 05 output Tag:
Output tag HTML me ek semantic tag hai jo web developers ko kisi bhi dynamic content ko display karne ke liye use kiya jata hai. 
Is tag ka upyog primarily JavaScript se associated data ko display karne ke liye hota hai.

Is tag ka syntax bahut hi simple hai, is tarah se likha jata hai:
```
<output for="input_id"></output>
```

Yahan `for` attribute input element ke id ke sath match karana chahiye jiske ap output ko display karana chahte hain. Jab input value change ho toh output 
value automatic update ho jayega. Jaise ki agar hume do numbers add karne ka program banana hai, toh uske liye hum input field se dono numbers ko input karenge 
aur output tag ka use karke result display karenge. Code is tarah se dikhega:

```
<label for="num1">Enter first number:</label>
<input type="number" id="num1"><br><br>

<label for="num2">Enter second number:</label>
<input type="number" id="num2"><br><br>

<output for="num1 num2"></output>

<script>
  var num1 = document.getElementById("num1");
  var num2 = document.getElementById("num2");
  var output = document.querySelector("output");

  function sum() {
    var result = +num1.value + +num2.value; //+ sign is used to convert string to number
    output.value = result;
  }

  num1.addEventListener("input", sum);
  num2.addEventListener("input", sum);
</script>
```

Is code mein humne `num1` aur `num2` input fields define kiye hain jis se hum input lege. Fir humne `output` tag define kiya hai jis se hum result display karenge.
`sum()` function input values ko add karke result calculate karta hai aur usko output field mein display karta hai.
Overall, output tag developers ko dynamic content display karne ke liye bahut flexible ek option provide karta hai.

### 06 datalist Tag:
Datalist tag ek HTML element hai jo input field ke liye options ko define karne ke liye use kiya jata hai. Ye ek dropdown list ki tarah kaam karta hai, 
jisme user ko select karne ke liye options diye jaate hai. Is tag ka upyog karna bahut hi saral hai. Sabse pehle, hum input field ko define karte hain jisme hume 
datalist ka upyog karna hai. Iske baad, hum datalist element ko define karte hain jisme hum apne options ko rakhte hain.
Mera ek example hai jisme hum ek form bana rahe hain jisme user ko apna favourite fruit select karna hai. 
Iske liye, hum input field ko define karenge jiske type "text" hoga aur isme datalist ka upyog karenge.

```
<label for="fruit">Apna pasandida phal chune:</label>
<input type="text" id="fruit" name="fruit" list="fruits">
<datalist id="fruits">
  <option value="Kela">Kela</option>
  <option value="Seb">Seb</option>
  <option value="Angoor">Angoor</option>
  <option value="Santra">Santra</option>
  <option value="Aam">Aam</option>
</datalist>
```

Is code  mei humne pehle label define ki hai jisse user ko pata chalega ki wo kya select karne ke liye hai. Fir humne input field define kiya hai jisme user ko apna 
favourite fruit select karna hai. Is input field ka name "fruit" hai aur iska datalist ka ID "fruits" hai. Humne datalist element mei kuch options bhi define kiye
hai jisme user se poocha jayega ki wo konsa phal select karna chahte hai.

### 07 legend Tag:
HTML mein "legend" tag ka upyog form ke saath ek heading ke roop mein kiya jata hai. Is tag ka upyog fieldset tag ke saath hota hai, 
jo ek group of related form elements ko define karta hai.

Iska syntax yeh hai:
```
<fieldset>
  <legend>Heading Text Here</legend>
  <!-- Form elements go here -->
</fieldset>
```

Isme "Heading Text Here" ki jagah aap apne form ke liye koi bhi heading text daal sakte hain. 
Jaise ki, agar aap ek registration form bana rahe hain toh aap is prakar ka code likh sakte hain:
```
<fieldset>
  <legend>User Registration Details</legend>
  <label for="username">Username:</label>
  <input type="text" id="username" name="username"><br><br>
  <label for="password">Password:</label>
  <input type="password" id="password" name="password"><br><br>
  <input type="submit" value="Submit">
</fieldset>
```

Iss code mein "User Registration Details" legend tag ke andar hai aur uske baad username, password fields hain. 
Iss tarah se, legend tag ek form ko organize karne mein madad karta hai aur usse visually appealing banata hai.
### 08 button Tag:
Button tag HTML mein ek markup tag hai jo button ke form mein ek button create karta hai. 
Is tag ka use karke hum apne web page mein button add kar sakte hai jaise submit, reset ya phir custom buttons.

Is tag ke andar hum text ya phir image bhi add kar sakte hai jo button ke upar show hoga. 
Ye buttons clickable hote hai aur user inhe click karke apne desired action ko perform kar sakta hai.

Yahan ek example diya gaya hai jismein hum ek submit button create kar rahe hai:

```
<button type="submit">Submit</button>
```

Is example mein `type` attribute `submit` value ke saath use kiya gaya hai jisse ye button submit button ki tarah behave karega. 
Hum is tag mein koi bhi text ya phir image add kar sakte hai jo button ke upar show hoga.

Aur agar aap chahte hai ki button ko click karne se koi action na ho toh aap usko disabled bhi kar sakte hai:

```
<button type="button" disabled>Disabled Button</button>
```

Is example mein `type` attribute mein `button` value use kiya gaya hai aur `disabled` attribute use karke disabled button create kiya gaya hai.
### 09 textarea Tag:
Textarea tag HTML mein ek aisa tag hai jo humein text input field provide karta hai jahan humein multiple lines of text enter karne ki suvidha hoti hai. 
Iska syntax bahut hi simple hai, ise hum `<textarea></textarea>` ke beech mein likhte hai.

Iske attributes mein se sabse important attribute 'name' hai, jo humare form submit hone ke baad server par send kiya jaata hai. 
Iske saath hi, hum ismein rows aur cols attributes ka upyog karke input field ka size bhi set kar sakte hai.

Ek chota sa example dekh lein: 
```
<form>
  <label for="msg">Message:</label><br>
  <textarea id="msg" name="user_message" rows="4" cols="50">
    Enter your message here...
  </textarea><br>
  <input type="submit" value="Submit">
</form>
```
Is example mein humne ek form banaya hai jismein ek textarea input field hai. Yahaan humne is field ko "msg" ID se identify kiya hai. 
Iske saath hi humne uska naam "user_message" set kiya hai aur uski height aur width ko bhi set kiya hai.
Jab user ismein kuchh likhega toh ye field uske dwara di gai value ko apne andar store karega aur jab form submit hoga toh ye value server par send ho jayegi.