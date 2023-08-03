# 1: HTML Table

HTML table ek tarah ka content hai jo ki rows aur columns ke form mein arrange hote hain. HTML table har tarah ki information ko organized tarike 
se display karne ke liye istemal hota hai jaise ki data, images, aur links.

Ek HTML table banane ke liye, `<table>` tag ka upyog hota hai. Har row ke liye `<tr>` tag aur har column ke liye `<td>` ya <th> tag ka upyog kiya jata hai. 
  `<td>` tag data cell ke liye aur `<th>` tag header cell ke liye istemal hota hai.

Neeche diya gaya hai ek simple example HTML table ka jismein 3 rows aur 2 columns hain:

```
<table>
  <tr>
    <th>Product</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>Mobile Phone</td>
    <td>10,000</td>
  </tr>
  <tr>
    <td>Laptop</td>
    <td>50,000</td>
  </tr>
</table>
    
```

Is table mein pehli row header cells (Product aur Price) ke liye reserve ki gayi hai aur baaki do rows mein data cells (Mobile Phone, Laptop aur unke prices) hain. 
Is table ko dekhne par apko ye samajh mein ayega ki kis product ke corresponding kya price hai.

Yeh tha HTML table ka ek basic example. Aap ismein background color, border, font size, aur other styling options bhi add kar sakte hain.


# 2: Rowspan and Colspan in Table

Rowspan aur Colspan, HTML ke table mei use kiye jaane wale attributes hai. Ye attributes table ke cells ko merge karne ke liye use kiye jaate hain.


Hum isi ko ek example ke through samajhte hain. Maan lo hume ek table banani hai jismein 4 cells hote hain. Hum 2nd row ke 2nd cell ko span karna chahte hain, 
taki ye cell 1st aur 2nd column dono ko cover kar sake. Iske liye hum rowspan aur colspan attribute ka use karenge.

```
<table>
  <tr>
    <td>Cell 1</td>
    <td>Cell 2</td>
  </tr>
  <tr>
    <td>Cell 3</td>
    <td rowspan="2" colspan="2">Cell 4</td>
  </tr>
  <tr>
    <td>Cell 5</td>
  </tr>
</table>
```

Is table mei, humne 2nd row ke 2nd cell ko rowspan="2" aur colspan="2" se define kiya hai. Aise karke, ye cell 1st aur 2nd column me dono ko merge karne laga hai.
Is tarah se hum rowspan aur colspan ka use karke tables ko customize kar sakte hain.


