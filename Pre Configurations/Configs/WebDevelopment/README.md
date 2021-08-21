
# `  Web Developers Pre-Configuration forVS Code 💯`

## `Here I'll be  providing `Pre-configuration`  file  for  `Web Developers` puroposes. 🤤`

---

```
       For a different languages VS Code will supports with different plugins.

       We can use best plugins for all in one work support, But, Files will use performance of VS Code.
```

```
 I'll be attaching all the configuration files, And I'll be attaching my system best configurations.
```

## <a href="../../../Configs/extensions-web.list" download="extensions.list">Download File</a> - `it consists all required list of packages`

```diff
- Important is file should be renamed to extensions and extension will be .list (if it is not with same name)

! finally file should be extensions.list
```

---
 ## `Installation Steps:` 
***
``` For Windows(PowerShell): ```
 ```code
    foreach($line in get-content extensions.list){code --install-extension $($line)}
 ```
***
```For MAC :```
```code
   cat extensions.list | % { code --install-extenstions $_}
````
***
```For Linux :```

``` code
   cat extensions.list | xargs -L 1 code --install-extenstions 
```
***

# `Detailed Description for Web developement plugin configuration`

| Package                | Description             | Where it Required | How it Works               |
| ---------------------- | ----------------------- | ----------------- | -------------------------- |
| abusaidm.html-snippets | It's for HTML shortcuts | HTML creation     | h1*6 will create 6 h1 tags |
|ecmel.vscode-html-css| It's for CSS selectors | while using Loops | when you type class, it shows used location |
|zignd.html-css-class-completion | It's for CSS classes | Class Redirection | You can get suggesstion of used classes |
|lonefy.vscode-js-css-html-formatter| To indent the HTML file | HTML files | It indenets the HTML code in clean way to make the code more understandable |
|tht13.html-preview-vscode| To preview the HTML code output | While coding HTML | It will show you the real time in HTML output |
|hdg.live-html-previewer| To preview the HTML code output | While coding HTML | It will show you the real time in HTML output |
|sibiraj-s.vscode-scss-formatter| It's a advanced version of CSS file formatter | It's for advanced CSS developer | It format the advanceed CSS files to make it clean |
|mrmlnc.vscode-scss| It's a advanced version of CSS file formatter | It's for advanced CSS developer | It format the advanceed CSS files to make it clean |
|ritwickdey.live-sass| SCSS file compiler | for SCSS file writer | It automatically compile SCSS files code to CSS |