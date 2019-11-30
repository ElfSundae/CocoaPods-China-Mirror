# CocoaPods CDN 中国镜像源

本站是 [CocoaPods Master Repo](https://github.com/CocoaPods/Specs) CDN 源的中国镜像，全量同步 pods 索引和 podspec 文件。

在 `Podfile` 中添加本镜像源：

```ruby
source 'https://cocoapods.0x123.com'
```

如有 Master Repo 的 Git 源、官方 CDN 源或其他镜像源，请删除之：

```diff
  source 'https://github.com/my/private/specs.git'
+ source 'https://cocoapods.0x123.com'

- source 'https://cdn.cocoapods.org/'
- source 'https://github.com/CocoaPods/Specs.git'
- source 'https://mirrors.tuna.tsinghua.edu.cn/git/CocoaPods/Specs.git'
```

- 环境要求：`pod --version` >= 1.8.0
- 镜像特色：全量托管 podspec 文件，如 [AFNetworking.podspec.json](https://cocoapods.0x123.com/Specs/a/7/5/AFNetworking/3.2.1/AFNetworking.podspec.json) 。官方 CDN 源 cdn.cocoapods.org 目前只包含索引，podspec 文件被重定向到 GitHub 链接。
- 更新周期：~~10 分钟~~ **本镜像目前仅供测试，寻求 CDN 合作商中...**
- 问题反馈：[CocoaPods-China-Mirror/issues](https://github.com/ElfSundae/CocoaPods-China-Mirror/issues)
- 了解 CDN Repo 请参考官方博客：[CocoaPods 1.7.2 — Master Repo CDN is Finalized!](http://blog.cocoapods.org/CocoaPods-1.7.2/)

By [Elf Sundae](https://github.com/ElfSundae)
