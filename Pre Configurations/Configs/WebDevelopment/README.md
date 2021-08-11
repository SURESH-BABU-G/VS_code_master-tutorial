
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

# `Detailed Description for Minimal configuration`

| Package                | Description             | Where it Required | How it Works               |
| ---------------------- | ----------------------- | ----------------- | -------------------------- |
| abusaidm.html-snippets | It's for HTML shortcuts | HTML creation     | h1*6 will create 6 h1 tags |
