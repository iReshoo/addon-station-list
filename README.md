# Addon Station List

English | [中文](./README_zh.md)

### How to upload my resouces?

* To upload an ItemsAdder addon, plugin that uses IA API, configurations, resource packs, namespaces.. you have to create a `Pull Request` or `Issue` here

* We recommend that you use https://smms.app/ Place images or other globally accessible image hosting websites, or even your private object storage! (Chinese users cannot access github raw)

### Rules to publish the resources are:

* every resource you publish MUST NOT contain any of the default itemsadder resources (textures, models, .jar file)

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

1. The `time` field is filled in with the timestamp when submitting the resource, accurate to seconds (`1683130262` will be `2023 05 04 00:11:02`)

2. Text that begins with a special symbol needs to be enclosed in quotation marks

    Example:

    ```yaml
    # available
    title: '[Itemsadder] Example'
    # unavailable
    title: [Itemsadder] Example
    ```

    Special symbols known to require quotation marks: `!` `@` `#` `%` `&` `*` `[` `]` `{` `}` `|` `,`