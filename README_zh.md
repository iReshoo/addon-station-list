# 创意工坊

[English](./README.md) | 中文

### 如何上传我的资源？

* 想要上传资源到创意工坊，你需要在 **此仓库** 创建一条 `Pull Request` 或者 `Issue`

* 建议使用 https://smms.app/ 或其他全球可访问的图床，或者是你自己的对象存储（中国用户无法访问github raw）

### 发布资源需要遵守的规则：

* 您发布的资源内不得包含Itemsadder的默认资源（包括但不限于材质、模型、.jar文件）

## 示例配置

IA

```yaml
author: LoneDev
content: Currency indicator, GPS, quiver and more HUDs for ItemsAdder
image: https://s2.loli.net/2022/10/27/5gB1SRheKNUmyIp.png
icon: https://www.spigotmc.org/data/resource_icons/97/97486.jpg?1636395812
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

## 提醒

1. `time` 字段填写的是提交资源时的时间戳，精确到秒( `1683130262` 将是 `2023-05-04 00:11:02` )

2. 需要用引号封闭特殊符号开头的文字

    如：

    ```yaml
    # 可以使用的
    title: '[Itemsadder] Example'
    # 不可使用的
    title: [Itemsadder] Example
    ```

    已知需要引号的特殊符号：`!` `@` `#` `%` `&` `*` `[` `]` `{` `}` `|` `,`
