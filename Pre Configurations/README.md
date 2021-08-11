
# ` Pre-Configuration for VS Code 💯`

## `Here I'll be  providing `Pre-configuration` files  for different language puroposes. 🤤`

---

```diff
       For a different languages VS Code will supports with different plugins.

       We can use best plugins for all in one work support. But, more plugins may raise performance issue of VS Code.

       That's the reason I'm giving individual plugin sheet for ** Web developemnt **
```

```
    I'll be attaching the configuration file, and I'll be giving the details description of each and single line execution of multiple plugins in simple easy way.
```

***
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

