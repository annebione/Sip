# Sip
## Gulp builds the easier way. Because gulp is just too much.

Sip is a gulpfile template engine destined to ease the pain of developing front-end builds and boost developer's productivity by making developers focus on what matters: their code. Pass the plugins you need and source/destination folders for your files as simple strings and you're done. No configuration at all. Sip does all the heavy lifting and tosses a gulpfile with all your plugins set and ready to go for both - production and development code.

### Documentation

##### Sipsource.js
That's where all your configurations should go. After installing Sip, open it with your preferred text editor.

##### 1. Edit your source variables.
In Sipsource.js the first block of variables you will see looks like the following:

```
const htmlSource = 'path/to/html'
,	cssSource = 'path/to/css'
,	jsSource = 'path/to/js'
,	imgSource = 'path/to/img'
,	assetsSource = 'path/to/assets';

```
Which corresponds to:

1. Source for your HTML files
2. Source folder for your CSS files
3. Source folder for your JS files
4. Source folder for your images
5. Source folder for your assets (fonts etc)

Edit those values according to your needs.

##### 2. Coming soon
Sip is in development right now. More information and a testable alpha version coming soon.
