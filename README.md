### GitHub Page link:

To see the GitHub page live [Click Here!](https://rayhanalkavey.github.io/Nature-Journey-Advance-css-project/ "Click Here!")

### This is a SASS practice project using npm-node-sass package(SCSS)

##### Implementing the 7-1 CSS architecture with sass: scss/base/7-folders

1. Abstract folder:
   a) This folder is only going to put code that's not going to output any css. For example, \_function.scss, \_variables.scss , \_mixins.scss etc
2. Base folder:
   a) File for real low level basics, such as resets and styles for the HTML and body element selectors.
   b)This file should be a partial so that we can later import it into the main sass file.
   c) Partial files will always start with \_(Underscore). For example, \_animation.scss, \_base.scss, \_typography.scss, \_utilities.scss etc.
   d) Heading primary codes are considered as typography
3. Component folder:
   a) We are going to create one file for each of our components.
   b) Components are reusable building blocks that makeup our websites or apps, and they should be usable anywhere on the page so they are completely independent and held together with the layout of the page.
   c) Examples: button,
4. Layout folder:
   a) We need a layout folder for each piece of the entire project
   b) We include global footer, header etc here.
5. Pages
   a) This architecture is designed for multi page projects.
   b) If we have a very specific style for a specific page for example a homepage we create a specific file for a specific page. For example, \_home.scss
6. Themes
   a) Like web apps with different themes.
7. Venders
   a) For third party css like files of bootstrap, icon systems or animation framework.

##### Hole precess of installing SASS and live-server at a glance:

1. Precess of installing SASS:

- Install node and check the version
- Init npm to create a package.json file
- Write a script in the package.json file. Which includes file name input file location(scss file) and the output file location (css file)
- Then compile the scss file to css file in the terminal by calling npm run (file-name). We should keep this terminal open. Otherwise the process will be stopped . If we need to use the terminal we should open a new one.
- Install live server globally. Npm install live-server -g. If any problem with the installation type (sudo npm install live-server-g) and then provide password.

2. To install live server globally ;

- Npm install live-server -g
- If have security concern on mac write sudo in command line
- Then (Npm install live-server -g) again and provide the password.
