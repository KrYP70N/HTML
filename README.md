# HTML Media Elements

We can share various type of multimedia such as image, music, video and other formats. 

| tag name     | attribute name                                   | use case                                       |
| ------------ | ------------------------------------------------ | ---------------------------------------------- |
| img          | alt="description"                                | represent for image content                    |
| picture      | -                                                | more flexibility in specifying image resources | 
| source       | media="(dimention)", srcset="path"               | defines when the image is the most suitable    |
| link         | rel="icon", type="image/x-icon", href="path"     | represent for adding favicon, stylesheet, etc. |
| audio        | controls, autoplays, muted                       | represent for audio content                    |
| video        | controls, autoplays, muted                       | represent for video content                    |
| source       | src="path", type="audio/ogg"                     | define supportable audio format for various types of browsers and version |


## Sample Code

### Image

```
<img src="./file/path.format" alt="alternative text for image">
```

### Picture

```
<picture alt="alternative text for image">
    <source media="(max-width: 700px)" srcset="./file/path.format" />
    <source media="(max-width: 700px)" srcset="./file/path.format" />
    <img src="./file/path.format">
</picture>
```

### Favicon

```
<link rel="icon" type="image/x-icon" href="./file/path.format" />
```

### Audio 

```
    <audio controls>
        <source src="./file/path.format" >
        <source src="./file/path.format" >
        Your browser does not support the audio element.
    </audio>
```

### Video 

```
    <video controls>
        <source src="./file/path.format" >
        <source src="./file/path.format" >
        Your browser does not support the audio element.
    </video>
```

