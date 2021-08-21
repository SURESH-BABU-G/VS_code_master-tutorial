
# `Vs code Customization for Quick Coding 💯`

## `Here I'll be explaining the Details of `Plugin` and usage. 🖥️ `

---

```
                        I'll be listing all the Plugins and usage, and Many more will be added constantly
```

<!--  The Result would be looking some thing like below -->

### `I'll be adding the pre-config files in `Content/Configs` folder.`


```diff
+ I'll be adding more files and even in the below I'll be adding new plugins with date of update
```

## <a href="../../../Configs/" download="extensions.list">Download Path</a> - `it consists all required list of pre-configured files.`

```diff
* Please, Feel free to raise a bug or note for required language plugins or configuration for a language ( I research and make a uniq look and comfort for your requirement )
```

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
