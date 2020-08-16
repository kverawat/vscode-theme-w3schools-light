# How to Create a new Color Theme?

Credit: https://css-tricks.com/creating-a-vs-code-theme/
Credit: https://code.visualstudio.com/api/extension-guides/color-theme

## Install
First, you need to run:

`npm install -g yo generator-code`

This makes the generator globally available on your machine (meaning you can now create a theme in any directory). 

## Kick off

`yo code`

You can then execute this command to kick off your theme:
You will be prompted by a screen that looks like this: 

used the arrows here to navigate to the **"New Color Theme"** option. 

![](https://raw.githubusercontent.com/kverawat/vscode-theme-w3schools-light/master/asset/images/yocode.png)

When selecting this, it asks if this import from an existing one or it is a new theme. If we want to create a new one used the arrows here to navigate to the  **"Start fresh"**.

If you customized a theme as described above, select 'Start fresh'. because if this is a new theme

![](https://raw.githubusercontent.com/kverawat/vscode-theme-w3schools-light/master/asset/images/yocode-colortheme.png)

Next, you’ll have to answer a few other questions, including:

```
# ? What’s the extension’s name?
# ? What is the the identifier? (I just went with the name, that’s probably typical.)
# ? What is the the description? (I just put something silly in initially. Don’t worry, you can update this in your package.json in the future.)
# ? What’s the publisher’s name? (See earlier instructions.)
# ? What name should be shown to the user? (I used the same as the extension name.)
# ? Is this theme dark, light, or high contrast?
```

![](https://raw.githubusercontent.com/kverawat/vscode-theme-w3schools-light/master/asset/images/yocode-colortheme-question.png)


```
# ? What type of extension do you want to create? New Color Theme
# ? Do you want to import or convert an existing TextMate color theme? No, start fresh
# ? What's the name of your extension? w3schools Light Theme
# ? What's the identifier of your extension? w3schools-light-theme
# ? What's the description of your extension? VSCode Theme based on Quite light theme. Integrates with a coding color3shools.com
# ? What's the name of your theme shown to the user? w3schools Light Theme
# ? Select a base theme: Light
```

```
   create w3schools-light-theme\themes\w3schools Light Theme-color-theme.json
   create w3schools-light-theme\.vscode\launch.json
   create w3schools-light-theme\package.json
   create w3schools-light-theme\vsc-extension-quickstart.md
   create w3schools-light-theme\README.md
   create w3schools-light-theme\CHANGELOG.md
   create w3schools-light-theme\.vscodeignore
```

### Your extension w3schools-light-theme has been created!

![](https://raw.githubusercontent.com/kverawat/vscode-theme-w3schools-light/master/asset/images/yocode-colortheme-question-answer.png)

It will set you up with a base theme to start skinning your color preferences.

- [VSCode Reference : The full scoop and all the details are here.](https://code.visualstudio.com/api/get-started/your-first-extension)
- [VSCode Reference : More details about themes in general are here](https://code.visualstudio.com/docs/getstarted/themes?WT.mc_id=csstricks-themearticle-sdras)

___

## Result

### Welcome to your VS Code Extension

You got new folder `w3school-light-theme`

About `vsc-extension-quickstart.md` inside the new extension for further instructions
on how to modify, test and publish your extension.

So, We alredy open `vsc-extension-quickstart.md` to learning it and then we import all important content as below.

### What's in the folder

* This folder contains all of the files necessary for your color theme extension.
* `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
* `themes/w3schools Light Theme-color-theme.json` - the color theme definition file.

### What is base theme and where is it?

You can see `w3schools Light Theme-color-theme.json` file on the folder `themes` of your color theme extension is a start skinning your color preferences that auto generate for you but it is very basic theme.

But now you can customize it if you want.

We recommend some content that need you understand it befor modify if you alredy know please skip link we recommend below.

- [VSCode Reference : The full scoop and all the details are here.](https://code.visualstudio.com/api/get-started/your-first-extension)
- [VSCode Reference : More details about themes in general are here](https://code.visualstudio.com/docs/getstarted/themes?WT.mc_id=csstricks-themearticle-sdras)

I assume we understand it..

### Start Editing Theme

To start editing with Visual Studio Code, use the following commands:

```code
cd w3schools-light-theme
code .
```

After that you will have new visual studio code on new popup windows of VSCode.


### Get up and running straight away

on new popup windows of VSCode

* Some time new popup windows of VSCode may be open New it not open new popup on folder that you want.

* Make sure you VSCode must be open folder of your create theme `w3schools-light-theme` May be locate at `C:\vscode-theme-w3schools-light\w3schools-light-theme`
  
   At the top left corner on the Title Bar on new popup windows of VSCode, click 
   
   ```
   File > Open Folder > C:\vscode-theme-w3schools-light\w3schools-light-theme
   ```

   ![](https://raw.githubusercontent.com/kverawat/vscode-theme-w3schools-light/master/asset/images/vscode-open-folder-your-extension-theme.png)

* Open file `launch.json` inside the folder `.vscode`
  
    ![](https://raw.githubusercontent.com/kverawat/vscode-theme-w3schools-light/master/asset/images/launch-F5-ExtDevHost.png)

* Press `F5` to open a new window again with your extension loaded.
  
  Now you will found the new popup windows of VSCode

  ![](https://raw.githubusercontent.com/kverawat/vscode-theme-w3schools-light/master/asset/images/vscode-open-folder-your-extension-theme-F5.png)

* Open `File > Preferences > Color Themes` and pick your color theme and you can see your theme in the drop-down list. Arrow up and down to see a live preview of your theme.
  
  Now you can see new your color theme as **w3schools Light Theme** on the list of color theme.

  ![](https://raw.githubusercontent.com/kverawat/vscode-theme-w3schools-light/master/asset/images/launch-F5-ExtDevHost-NewTheme.png)

* Open a file that has a language associated. such as
   - sample.html, 
   - sample.js, 
   - sample.css, 
   - sample.php, 
   - sample.md, 
   - sample.ts, 
   - sample.json, 
   - sample.scss
  
  The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. 
  
  To examine these scopes, invoke the `Inspect TM Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac) .

### Make changes

* Changes to the theme file are automatically applied to the `Extension Development` Host window.

### Adopt your theme to Visual Studio Code

* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

___

## Install your extension

* **Private (Personal Used Only)** 
  
  To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
  
  Example for my laptop, I copy it into:

  `C:\Users\Rungnapa-WIN10\.vscode\extensions`

* **Public (Market Place)**
  
  To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.

  It is very easy ! don't worry that.

___

## How to Publishing a Theme to the Extension Marketplace

If you'd like to share your new theme with the community, you can publish it to the Extension Marketplace. Use the vsce publishing tool to package your theme and publish it to the VS Code Marketplace.

https://code.visualstudio.com/api/working-with-extensions/publishing-extension

**Tip:** To make it easy for users to find your theme, include the word "theme" in the extension description and set the Category to Themes in your package.json.

We also have recommendations on how to make your extension look great on the VS Code Marketplace, see Marketplace Presentation Tips.

https://code.visualstudio.com/api/references/extension-manifest#marketplace-presentation-tips
