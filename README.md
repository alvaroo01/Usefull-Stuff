# How to use this cursor

## How to Use

### HTML

Add a series of `<div>` elements with the class name `.circle` to your HTML file. You can customize the number of circles as needed.

 ```
<div class="circle"></div>
<div class="circle"></div>
<div class="circle"></div>
<div class="circle"></div>
<div class="circle"></div>
<div class="circle"></div>
<div class="circle"></div>
<div class="circle"></div>
<div class="circle"></div>
 ```

 ##$ CSS 
 
 Define the styles for the `.circle` class in your CSS file. Adjust the properties as desired, such as size, border radius, and initial background color.

 ```
.circle {
    height: 24px;
    width: 24px;
    border-radius: 24px;
    background-color: black;
    position: absolute;
    top: 0;
    left: 0;
    pointer-events: none;
}
 ``` 

 ### JavaScript

Import the provided JavaScript file into your project. You can customize the appearance and behavior of the cursor animation by adjusting the variables in the script.

- `factor`: Controls the size of the trail left by the cursor.
- `gradientColors`: Define an array of colors to create a gradient effect for the cursor trail.

### Credits

This custom cursor animation was created based on a tutorial by **CodeMorphism**. You can find the tutorial on [YouTube](https://www.youtube.com/@codemorphism).
