# Image optimization

This code allows to reduce quality, resize images and/or change format (for gifs at the moment) in order to reduce file size. Also, it generates automatically a file (exportImages) where we import and export all newly created files. This allows to avoid the use of width and height when using Nextjs Image component (something that is required otherwise).

In order to run this code, please see the script in the package.json file

Also, you can specify the desired size of each image by adding that information in the object 'dimensionsMapping' located in the file 'optimizeImages'.

All images need to be saved in one directory. If you need to change the current directory, please do so in the file 'optimizeImages', variable `dirPath`. The same goes for where to save the excluded images json file, change this variable if needed: `excludedImagesPath`
