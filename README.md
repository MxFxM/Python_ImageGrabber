# Image grabber for Python

Grabs an image from a url and saves it in a folder.

Can also be used to save multiple images at once.

Example is for weather icons from openweathermap.

## Usage

    downloadImage(url, name, folder)

- url is the url of the image
- If no name is give, name will be temp
- .jpg will be appended to name
- If no folder is given, folder is current working directory
- A given folder will be cwd/folder/name.jpg


    downloadImages(url, names, folder)


- folder is same as above
- names is an array of names
- url is an array of up to two elements
- the names will be put in the middle of the two url parts
- a part of the url can also be empty
