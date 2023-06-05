# GDevelopSplashPatcher
Add your custom logo to your game without having a subscription.

# Info
This can only be done on the browser version of the exported game.

# Tutorial

## 1: Set info

Open your project, go to Game settings and then Properties. Then, click on "Branding and Loading screen". Then click on the "GDevelop logo style" dropdown and select "Dark (colored)"

## 2: Export your game

After coding it, export your game to HTML. 

## 3: Patch your logo JS

A logo JS is the file that GDevelop uses to get its logo. The online tool patches the logo JS to display your logo. Now go to [this website](https://errivi.github.io/GDevelopSplashPatcher/tool.html) and import your PNG.

### Important info!

Your photo must be 755 per 132 (exact same width and height)!

## 4: Download your gd-logo-dark-colored.js

Press download to export and then download the ```gd-logo-dark-colored.js``` (the file needed for loading the logo)

## 5: Patch your game

Go to your export folder, navigate into "splash" and then replace the current ```gd-logo-dark-colored.js``` with your file!

