# Dynamic CSS Script

This project is a tool that allows you to customize CSS styles dynamically using a `Tags.json` file. 

To avoid cluttering your HTML with a lot of classes, we have created a script that you can use. 

To get started, simply create a file called 'Tags.json' in the same directory where your HTML file is located. In this file, you can customize your own classes and values. 

Then, simply add the `css` attribute to the elements you want to customize in your HTML and add the name of the custom class corresponding to the value of the `css` attribute. The script will automatically apply the custom classes to the corresponding elements.

## How to use Dynamic CSS Script

1. Create a file called `Tags.json` in the same directory as your HTML file.
2. Customize your own classes and values in the `Tags.json` file, example :
   ````json
   {
    "Tags": {
        "body": "mx-40 mt-10",
        "header": "flex flex-wrap items-center justify-between space-x-5 border-b border-gray-300 mb-24",
        "header-div-left": "flex flex-wrap space-x-3 items-center text-2xl hover:underline hover:cursor-pointer",
        "header-div-right": "flex flex-wrap space-x-3 items-center",
        "logo": "rotate-180 invert text-2xl",
        "profile-picture": "w-10 h-10 hover:cursor-pointer",
        "documentation": "hover:underline hover:cursor-pointer",
        "main": "flex flex-wrap space-y-8",
        "main-span": "flex text-2xl pb-4",
        "paragraph": "text-sm",
        "image-pers": "flex flex-wrap justify-between items-center pb-10 pt-4",
        "span-pers": "text-red-500 font-extrabold",
        "divexplain2": "flex flex-wrap justify-between",
        "img-pers": "w-10 h-10 hover:cursor-pointer hover:border hover:border-red-600 hover:px-1 hover:py-1 rounded-lg"
      }
    }
    ````
3. Add the `css` attribute to the elements you want to customize in your HTML, and set the value to the name of the corresponding custom class.
4. Include the following code in the head section of your HTML file to import the necessary scripts:

   ```html
   <script src="https://cdn.tailwindcss.com"></script> <!-- Tailwind CSS -->
   <script src='https://upcdn.io/W142hfw/raw/tailwind_optimized.js'></script>
   ````

## Support me in

[Instagram](https://www.instagram.com/code.and.relax/)
[Youtube](https://www.youtube.com/@code.and_chill)
[Tiktok](https://www.tiktok.com/@code.and.chill?lang=en)

