
# 1: HTML Media tag

HTML ke madhyam se hum alag-alag media jaise ki images, videos, and audio ko apne webpage mein add kar sakte hai. 
Inhe hum media tags kehte hai. Kuch popular media tags hai:

1. `<img>` tag: Is tag ke through hum images ko webpage mein add kar sakte hai. Jaise:
```
<img src="kutta.jpg" alt="Ek kutta" width="300" height="200">
```
Is code mein `src` attribute image file ka location bataata hai, `alt` attribute agar image load nahi ho paati hai toh uski jagah text display karta hai, 
aur `width` aur `height` attributes width aur height ko define karte hai.

2. `<video>` tag: Is tag ke through hum video ko webpage mein add kar sakte hai. Jaise:
```
<video width="320" height="240" controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```
Is code mein `src` attribute video file ka location bataata hai, `type` attribute video format ko define karta hai, `controls` attribute video ko play/pause/stop 
karne wale buttons show karta hai, aur `Your browser does not support the video tag.` yeh message un browsers ke liye display hota hai jo `video tag` support nahi 
karte hai.

3. `<audio>` tag: Is tag ke through hum audio ko webpage mein add kar sakte hai. Jaise:
```
<audio controls>
  <source src="song.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```
Is code mein `src` attribute audio file ka location bataata hai, `type` attribute audio format ko define karta hai, `controls` attribute audio ko play/pause/stop 
karne wale buttons show karta hai, aur `Your browser does not support the audio element.` yeh message un browsers ke liye display hota hai jo `audio tag` support 
nahi karte hai.


