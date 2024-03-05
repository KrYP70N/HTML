# HTML Introduction

## Note 

- stand for Hyper Text Markup Language for creating webpage
- "index.html" will serve as a default page of directory

## Sample Doc

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Simple Title</h1>
    <p>Simple paragraph Lorem ipsum, dolor sit amet consectetur adipisicing elit. Cupiditate, eveniet.</p>
</body>
</html>
```

## Explaination

| Element | Description |
|---------|-------------|
| `<!DOCTYPE html>` | Define HTML DOC |
| `<html> `         | Root element    |
| `<head>`          | Metadata info   |
| `<title>`         | Title of page   |
| `<body>`          | Doc body that contain visible contents |
| `<h1>`            | Heading         |
| `<p>`             | Paragraph       |


## Anatomy

Each **HTML** element consists of several parts : 

| Parts | Description |
| ----- | ----------- |
| Opening Tag | The opening tag is the first part of an HTML element, enclosed in angle brackets (`<` and `>`). It specifies the type of element being used and may contain attributes that provide additional information about the element. |
| Element Name | The element name is the name of the HTML tag, such as `<p>` for paragraphs, `<img>` for images, or `<a>` for links. |
| Attribute | Attributes provide additional information about an element and are included within the opening tag. They are written as name-value pairs, where the attribute name is followed by an equals sign (`=`) and the attribute value enclosed in quotation marks (`"` or `'`). |
| Content | The content of an HTML element is the information or markup contained within the opening and closing tags. It can include text, other HTML elements, or both, depending on the type of element. |
| Closing Tag | The closing tag is the final part of an HTML element, also enclosed in angle brackets (`<` and `>`), but with a forward slash (`/`) before the element name. It indicates the end of the element's content. |

![HTML Element Anatomy](/assets/html-element-anatomy.png)


## Element 

An element contain `start tag <p>` `content` and `end tag </p>`.
However some elements doesn't have end tag like `img` and `br`.

```
<p> content </p>
```

