## intro
the popular color theme from **VIM** to VsCode.


## preview
![js](https://raw.githubusercontent.com/Rozbo/papercolor-vscode/master/doc/js.png)

----
![python](https://raw.githubusercontent.com/Rozbo/papercolor-vscode/master/doc/python.png)

----
![php](https://raw.githubusercontent.com/Rozbo/papercolor-vscode/master/doc/php.png)

----
![c](https://raw.githubusercontent.com/Rozbo/papercolor-vscode/master/doc/c.png)

----
![markdown](https://raw.githubusercontent.com/Rozbo/papercolor-vscode/master/doc/markdown.png)
## About LeftBar
By default,the LeftBar will be dark or ligth.  because that the `VsCode` dont have api to control it now.  
So if u want have the bule LeftBar like the screenshot, u can do this:  

put this css into `<Microsoft VS Code>\resources\app\out\vs\workbench\electron-browser\workbench.main.css`  
Then may be u will see VsCode's notice: 
> Your Visual Studio Code installation appears to be corrupt. Please reinstall.

This tip is _expected_,because we have modified it,just choose `Don't show again`。

```css
.rozbo-papercolor-vscode-themes-papercolor-vscode-light-tmTheme .monaco-workbench>.activitybar>.content {
    background-color: #007acc !important;
}
.rozbo-papercolor-vscode-themes-papercolor-vscode-light-tmTheme .monaco-workbench > .part.statusbar {
  border-top: 1px solid #008aff !important;
}
```


## More Information
* [Visual Studio Marketplace](https://marketplace.visualstudio.com/items/rozbo.papercolor-vscode).
* [GitHub repository](https://github.com/rozbo/papercolor-vscode).
