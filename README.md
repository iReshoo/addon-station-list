# Addon Station List

English | [中文](./README_zh.md)

### How to upload my resouces?

How to upload an ItemsAdder addon, a plugin that uses ItemsAdder API, ItemsAdder configurations, etc.

* Click on the `ia` (ItemsAdder) or `cc` (CosmeticsCore) folder
* Click on `Add file` -> `Create new file`

![image](https://github.com/Cha-Shao/addon-station-list/assets/27242001/d50dc5a9-792b-45e5-92c9-a903bb2193fc)

* Set the file name to something meaningful for your project, for example project name and author name. 
  * Do not add special characters or spaces in the file name.
  * Do not replace other files.

![image](https://github.com/Cha-Shao/addon-station-list/assets/27242001/31ac64eb-83e5-4109-a444-9dda432ae4b5)


* Copy and paste the content of the example file from the bottom of this page. Edit every property to your preference.

![image](https://github.com/Cha-Shao/addon-station-list/assets/27242001/7daecea9-ca4a-4cf9-b802-b6ad3de4cd09)

* Use [this website](https://www.unixtimestamp.com/) to create an unix date and set it in the file.

![image](https://github.com/Cha-Shao/addon-station-list/assets/27242001/948bd310-fb13-490a-a3ca-e50f1438613e)

* Upload the resource logo or screenshot using a service like https://smms.app/ . Use globally accessible image hosting websites, or even your private object storage! (Chinese users cannot access github raw and imgur)

* Now press on `Commit changes...` and create a pull request. 

### Rules to publish the resources are:

* every resource you publish MUST NOT contain any of the default itemsadder resources (textures, models, .jar file).
* you must satisfy the rules of the marketplace where you published the resource.

## Example Config

IA
```yaml
author: LoneDev
content: Currency indicator, GPS, quiver and more HUDs for ItemsAdder
image: https://s2.loli.net/2022/10/27/5gB1SRheKNUmyIp.png
link: https://www.spigotmc.org/resources/addon-rpghuds-for-itemsadder.97486
premium: false
tags:
  - hud
  - plugin
title: AdvancedCrates
time: 114514
```

CC
```yaml
author: Cha_Shao
image: /assets/item/cc/Amogus/image.png
link: '#'
premium: false
tag: ballon
title: Amogus
time: 114514
```

## Tips

1. Text that begins with a special symbol needs to be enclosed in quotation marks

    Example:

    ```yaml
    # available
    title: '[Itemsadder] Example'
    # unavailable
    title: [Itemsadder] Example
    ```

    Special symbols known to require quotation marks: `!` `@` `#` `%` `&` `*` `[` `]` `{` `}` `|` `,`
