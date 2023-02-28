# hugo-shortcode-mmt-netease

![preview](https://user-images.githubusercontent.com/33419593/221810055-bf78de27-8f5d-4ffa-bf02-f60c0939f169.png)

一个含有网易云随机评论 shortcode 的 Hugo 主题组件。

## Installation

将此 git 存储库克隆到您的主题文件夹中并添加为您的网站目录的子模块。

```bash
git submodule add https://github.com/Lruihao/hugo-shortcode-mmt-netease.git themes/shortcode-mmt-netease
```

接下来编辑您的项目 `config.toml` 并将此主题组件添加到您的主题中：

```bash
theme = ["your-main-theme", "shortcode-mmt-netease"]
```

要了解 hugo 的主题组件以及如何使用它们，请查看 <https://gohugo.io/hugo-modules/theme-components/>。

## Usage Example

> **Warning** 同一页面只支持使用一次！

这是一个用法示例：

```
{{< mmt-netease "2280569152" >}}
```

它只有一个匿名参数，代表获取随机评论及歌曲的**网易云歌单 ID**，例如：[2280569152](https://music.163.com/#/playlist?id=2280569152)。

## Dependencies

- [APlayer](https://github.com/MoePlayer/APlayer)
- [MetingJS](https://github.com/metowolf/MetingJS)
- [UomgAPI](https://api.uomg.com/doc-comments.163.html)
- [MMT](https://github.com/Lruihao/MMT)
