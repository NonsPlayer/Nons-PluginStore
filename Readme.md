<div align="center">
<img src="https://github.com/Miaoyww/NonsPlayer/blob/master/NonsPlayer-Icon.png" alt="图标" Height="128" Width="128">

<h1 align="center">NonsPlayer Plugin Store</h1>

<p align="center"> 
  A repository for listing <a href="https://github.com/Miaoyww/NonsPlayer">NonsPlayer</a> plugins.
</p>
</div>

# 临时目录

- [Ncm](https://github.com/Miaoyww/NonsAdapter-Ncmp): NonsPlayer的网易云适配器

## 插件提交及更新

1. Fork 本仓库
2. 在 `plugins` 目录下创建一个 JSON 文件，内容如下

```js
{
    "name": "ExamplePlugin", // 插件名
    "repo": "Miaoyww/example-plugin", // 插件的 Repo
    "branch": "main", // 分支名
    "subpath": "/", // 插件在 repo 中的子目录 （可选）
    "author": "Author" // 作者
}
```

## Manifest.json 格式
Special thanks to [BetterNCM](https://github.com/BetterNCM/BetterNCM-Plugins)

```js
{
    "name": "ExamplePlugin", // 插件名
    "slug": "example-plugin", // 插件唯一识别名（英文、数字、横杠与下划线） (留空则根据插件名自动生成)（如果插件名有中文请填写该字段）
    "version": "0.1.0", // 插件版本，推荐使用语义化版本（https://semver.org/）
    "author": "Author", // 插件作者
    "author_link": "https://example.com", // 作者链接（可选）
    "description": "Description of the plugin", // 插件描述
    "preview": "preview.png", // 插件预览图
    "type": "plugin", // 插件类型（可选）：adapter  | plugin (默认)
    "requirements": ["example-dependency"], // 依赖的插件 Slug（可选）
}
```
