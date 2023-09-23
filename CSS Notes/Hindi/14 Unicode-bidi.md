# 1. unicode-bidi

**unicode-bidi** CSS property text content ke Unicode bidirectional algorithm ko control karne ke liye hoti hai. Unicode bidirectional algorithm text mei likhne aur presentation ki direction ko manage karta hai jab ek sentence ya paragraph mei alag-alag script languages, jaise LTR (left-to-right) aur RTL (right-to-left), ka istemal hota hai.

Yadi aap ek webpage mei alag-alag languages ka istemal karte hain jaise English (LTR) aur Arabic (RTL), toh **unicode-bidi** property ki madad se text content ka order manage kiya ja sakta hai taki sahi tarah se display ho sake.

Niche kuch examples diye gaye hain:

1. **Override Default Direction:**

```
p {
  unicode-bidi: bidi-override;
  direction: rtl;
}
```

2. **Embed Text Direction:**

```
p {
  unicode-bidi: embed;
}
```

Is property ka istemal languages ke text content ko sahi tarah se display karne ke liye hota hai, jahan alag-alag scripts ka istemal hota hai aur text ka order sahi tarike se maintain karna important hota hai.