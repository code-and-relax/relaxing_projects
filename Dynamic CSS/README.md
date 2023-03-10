# Dynamic CSS Script

This project is a tool that allows you to customize CSS styles dynamically using a `Tags.json` file. 

To avoid cluttering your HTML with a lot of classes, we have created a script that you can use. 

To get started, simply create a file called 'Tags.json' in the same directory where your HTML file is located. In this file, you can customize your own classes and values. 

Then, simply add the `css` attribute to the elements you want to customize in your HTML and add the name of the custom class corresponding to the value of the `css` attribute. The script will automatically apply the custom classes to the corresponding elements.

## How to use Dynamic CSS

To apply the custom classes that we store inside our `Tags.json` file, we need to add the `css=['custom class name']` attribute. This way, all Tailwind CSS classes are applied without the need for our HTML to become garbled.

## Importing CDN link

To import the tool, just add the following script to your HTML:

````html
<script src='https://upcdn.io/W142hfw/raw/tailwind_optimized.js'></script>
````
## How to apply custom styles

To apply custom styles, you must first create a file called `Tags.json` in the same directory as your HTML file. In this file, you can customize your own classes and values.

Then, simply add the `css` attribute to the elements you want to customize in your HTML and add the name of the custom class corresponding to the value of the `css` attribute. The script will automatically apply the custom classes to the corresponding elements - it's that easy!



