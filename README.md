# A-My-Island

把个人计划、节点关系、表格、场景、角色与常用工具集中到一座可互动的小岛中。

## 主要功能

- 使用 Cytoscape.js 构建可分层浏览、连线和聚焦的可视化节点画布。
- 支持分组、文本、图片、表格及经营、计划、目标、委托等多种节点。
- 提供角色移动、跳跃、待机、工作、手机与剧情互动。
- 内置日记、备忘录、相册、视频、番茄钟、邮箱等手机 App。
- 支持场景、角色、节点插画及可选静态资源包管理。
- 业务数据保存在当前 Vault，便于随知识库备份与多设备同步。

## 付费与激活

A-My-Island 是需要购买许可证并激活后使用完整功能的付费插件。

激活码请通过作者的正式销售或联系渠道获取：

- [购买 A-My-Island 激活码](https://wzyp.cn/shop/NIAR958A)
- QQ 群：603045364
- 微信：VinVinVin444
- [Bilibili](https://space.bilibili.com/3493128231193555)
- [小红书](https://xhslink.cn/m/8ZWjZpJc6sK)
- [抖音](https://v.douyin.com/bqTGipbnW_8/)

## 平台支持

本插件当前仅支持桌面端。部分可选功能需要桌面环境提供本地文件选择、媒体处理和邮箱连接能力。

## 网络访问

A-My-Island 只在下列场景访问网络：

1. 激活许可证，以及在许可续签、过期恢复、可信时间异常或用户主动验证时连接授权服务器。
2. 从官方 A-My-Island-Releases 仓库下载用户主动选择的非可执行静态资源。
3. 用户自行配置天气服务后，天气模块访问其指定的接口。
4. 用户添加邮箱账户后，连接相应邮箱服务；仅在用户允许时加载邮件中的远程图片。
5. 用户主动打开作者链接、邮件链接或手机内的网页与视频内容。

插件不会通过远程 JavaScript 更新或执行代码。静态资源包会校验来源、包标识、允许路径、文件大小和 SHA-256。

## 隐私

- 无客户端遥测。
- 无使用行为分析。
- 无广告跟踪。
- 不出售用户数据。
- 邮箱密码、授权码及令牌不明文写入普通插件设置。

许可证服务只接收激活和验证所必需的数据。完整说明见 [PRIVACY.md](PRIVACY.md)。

## 数据与备份

主要业务数据保存在当前 Vault 的 `A_My_Island_Data` 与 `A_Shared_Data` 目录。插件设置及离线许可证保存在当前 Vault 的插件配置目录中。

备份整个 Vault 时，上述数据会一并备份。插件不会扫描与用户操作无关的外部目录；只有在用户主动选择、导入或导出文件时，才访问 Vault 外部路径。

## 安装与更新

正式上架后，请通过 Obsidian Community Plugin Directory 安装和更新。不要从非官方来源下载修改过的构建文件。

可选插画、动画、对话和场景资源由 [A-My-Island-Releases](https://github.com/VinVinVin444/A-My-Island-Releases) 提供。无法访问 GitHub 时，可通过支持渠道获取资源压缩包并按插件教程手动安装。

## Source and review

A-My-Island is paid proprietary software. Its TypeScript source code is maintained permanently in a private repository and is not distributed through the public release repository.

The public release repository contains only approved release files, public documentation, and non-executable static resources.

## Third-party software

This plugin uses Cytoscape.js, licensed under the MIT License. See [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md) for details.

## Support

作者：全平台：岛民Vin。问题反馈与购买咨询可通过上述作者渠道联系。

## License

A-My-Island is proprietary commercial software distributed under the terms in [LICENSE](LICENSE). Third-party components remain governed by their respective licenses.
