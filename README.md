# Path Handling

File paths are used to specify the location of resources such as HTML files, CSS style sheets, JS scripts, images and other assets within a website's directory structure. File paths can be either relative or absolute. Relative file paths specify the location of a file relative to the current location, typically the directory of the file referencing it. This approach is commonly used for referencing files within the same website or project. Absolute file paths, on the other hand, specify the complete path to a file starting from the root directory of the file system. Absolute paths are useful for referencing resources located outside the website's directory structure or when the exact file location needs to be explicitly defined. Understanding how to properly use file paths is essential for organizing and accessing resources efficiently in web development projects.


## Relative file path structure

Relative file path describes the location of a file in a web site's folder structure.


| Path                         | Description                                               |
| ---------------------------- | --------------------------------------------------------- |
| `<img src="img.jpg" >`         | file is located in the same folder as the current page.   |
| `<img src="images/img.jpg" >`  | file is located in the images folder in the current folder |
| `<img src="/images/img.jpg">`  | file is located in the images folder at the root of the current web |
| `<img src="../img.jpg">`	   | file is located in the folder one level up from the current folder |


## Absolute file path structure

Absolute file path specify the complete path to a file. It's useful for referencing resources located outside out the current project.

```
<img src="https://www.otherwebsite.com/your/img.jpg" alt="your image">
```
