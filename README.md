# Texas Woman's University HTML

Maybe simple changes to a text file don't cause conflicts because they're easy to resolve. What about adding an image?

![a picture of a Ph.D. student](https://twu.edu/media/images/news/abreu_thumb.jpg)

So, did adding a photo to the file on GitHub cause a conflict that can't easily be resolved?

![17-twu-0027_brand-launch_app-icons_152x152](https://user-images.githubusercontent.com/3957145/31792948-59c20c88-b4e3-11e7-9474-92ecc4fc094f.png)

I'm trying to create a conflict between my local repository and the GitHub repository — a change for change's sake. 

Here is a brief step by step process of setting up the project for compiling.

1. Install [NPM](https://www.npmjs.com/)

2. After installing NPM make sure that it is in your path so you can use it in the command line. It usually works out of the bag in MAC/Linux, but sometimes the path needs to be added [manually in Windows](http://stackoverflow.com/questions/27864040/fixing-npm-path-in-windows-8/32159233).

3. Extract the project files and cd to the directory in your command line.

4. Run `npm install` to install all the dependencies for the project. This can take several minutes.

5. Once you have the dependencies installed, to build the project and "watch" any changes in sass, js, or html partials you will run `gulp` in the command line.

A browser window will open of the project and you will be able to see it edited live. Whenever you make a change to the html, sass, or js, the browser automatically refreshes.

With the project running, the command line will chirp at you if there are any issues with how your code is compiled. It's very helpful!

If you want to add new svg icons you just drop them into src/svgstore. They will be automatically compiled and turned into a spritesheet. You can see how icons are used in some of the html partials. They can also be used directly in the sass.

//

You will need to register for a Google Developer account and get an API key for Google Maps Embed API and Google Maps Static API
