# 1. img tag

The `<img>` tag is an HTML element used to embed images into a web page. It stands for "image" and is a self-closing element, meaning it does not have a closing tag. The `<img>` tag requires the src attribute, which specifies the URL of the image file to be displayed.

Here's how the `<img>` tag is used:

```
<img src="path/to/image.jpg" alt="Description of the image">
```


# 2. video tag

The `<video>` tag is an HTML element used to embed video content in a web page. It allows you to include video files and display them directly in the browser, providing a way to present multimedia content to your website visitors.

Here's how the `<video>` tag is used:

```
<video controls>
<source src="example.mp4" type="video/mp4">
<source src="example.webm" type="video/webm">
</video>
```


# 3. audio tag

In HTML, the `<audio>` tag is used to embed audio content, such as sound or music, directly into a web page. It allows you to play audio files on the web page without requiring any external media players. The `<audio>` tag supports various audio formats like MP3, WAV, OGG, and others, depending on the web browser's capabilities.

Here's the basic syntax of the `<audio>` tag:

```
<audio controls>
<source src="audio_file.mp3" type="audio/mpeg">
</audio>
```


# 4. source tag
The `<source>` tag is an HTML element used within the `<video>` and `<audio>` elements to specify different media sources for multimedia content. It allows you to provide multiple versions of the same video or audio file in different formats or resolutions. The browser will then select and use the first supported format it can play, based on the codecs and formats it supports.

Here's how the `<source>` tag is used within a `<video>` element:

```
<video controls>
<source src="video.mp4" type="video/mp4">
<source src="video.webm" type="video/webm">
<!-- Additional source tags for other formats -->
</video>
```

