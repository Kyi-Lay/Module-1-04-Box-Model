# HTML Box Model Example

This project demonstrates the use of the HTML box model. It includes an HTML file and a CSS file to showcase how different properties like `margin`,padding`,and `border`affect the layout of elements.

## Project Structure
   assets
│ ├── css
│ │ └── style.css
│ └── images
│ ├── image-1.png
│ ├── image-2.png
│ ├── image-3.png
│ └── image-4.png
│
└── index.html

  
## Files

### index.html

   This is the main HTML file that includes a section with four images.
  html
<!DOCTYPE html>
<html lang="en-US">
<head>
    <meta charset="UTF-8">
    <title>HTML Box Model</title>
    <link rel="stylesheet" type="text/css" href="./assets/css/style.css">
</head>
<body>
    <section>
        <img src="./assets/images/image-1.png" alt="box with number 1"/>
        <img src="./assets/images/image-2.png" alt="box with number 2"/>
        <img src="./assets/images/image-3.png" alt="box with number 3"/>
        <img src="./assets/images/image-4.png" alt="box with number 4"/>
    </section>
</body>
</html>

# 📖  style.css
This CSS file contains the styling rules for the HTML file. It demonstrates the use of width, height, text-align, border, margin, padding, and background-color properties.

# Description
## HTML File:

* The HTML file defines a simple webpage with a section element containing four img elements.
* Each image has an alt attribute describing the content of the image.
  CSS File:

    The section element is styled to have a width and height of 600px, centered text, and a 
  black border.
  Each img element is styled to have a width and height of 200px, a light blue background 
  color, a margin of 20px, padding of 20px, and a dark blue border.
# Usage
  To view the project, simply open the index.html file in a web browser. You will see four 
  images styled according to the CSS rules specified in the style.css file.

## 📝 Notes
    Ensure that the paths to the CSS and image files are correct.
 The alt attributes in the img tags provide alternative text for the images, which is useful 
 for accessibility and when the images cannot be displayed.

# License
 This project is licensed under the MIT License - see the LICENSE file.

 Feel free to customize the `README.md` file further based on your project's specific details 
 and requirements.




