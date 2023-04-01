# 1: HTML Lists
HTML mein, hum apne webpage par list ko show karne ke liye "List" ka use karte hai. List mein hum kisi bhi topic ke points ya items ko organize kar sakte hai.

HTML mein 3 types ki list hoti hai: 
1. Ordered List (numbering se dikhaye jate hai)
2. Unordered List (bullets se dikhaye jate hai)
3. description List

Example ke taur par agar mujhe fruits ke naam display karne hai toh mein unordered list ka use karoonga. Yeh code dekhiye:

```
<ul>
   <li>Aam</li>
   <li>Kela</li>
   <li>Kele</li>
   <li>Litchi</li>
</ul>
```

Is code mein `<ul>` tag unordered list ko define karta hai aur `<li>` tag list item ko define karta hai. Ismein har ek list item ke pehle bullet point 
automatically aa jata hai.

Agar main yeh numbers ke saath dikhana chahata hoon toh mein ordered list ka use karoongo. Yeh code dekhiye:

```
<ol>
   <li>Ek</li>
   <li>Do</li>
   <li>Tin</li>
   <li>Char</li>
</ol>
```

Iss code mein `<ol>` tag ordered list ko define karta hai aur `<li>` tag list item ko define karta hai. Har ek list item ke pehle number automatically aa jata hai.


## 3 description list

HTML में एक Description List होती है जिसमें हम किसी चीज़ का Definition बता सकते हैं। इसमें 2 tags होते हैं - `<dl>` और `<dt>/<dd>`।

`<dl>` टैग डिस्क्रिप्शन लिस्ट को शुरू करता है, उदाहरण के तौर पर, अगर हम फलों का Description List बनाना चाहते हैं 
तो हम इस तरह से लिख सकते हैं:

```
<dl>
  <dt>आम</dt>
  <dd>एक फल जो गर्मियों में पाया जाता है।</dd>
  
  <dt>सेब</dt>
  <dd>एक फल जो सर्दियों में पाया जाता है।</dd>
  
  <dt>केला</dt>
  <dd>एक फल जो सबसे ज्यादा खाया जाता है।</dd>
</dl>
```

यहाँ, `<dt>` टैग में फल के नाम हैं - आम, सेब और केला, जबकि `<dd>` टैग में उनका Definition है। इस तरह की डिस्क्रिप्शन लिस्ट बनाने से वेब पेज को अधिक एक्सेसिबल, समझदार और सुविधाजनक 
बनाया जा सकता है।
