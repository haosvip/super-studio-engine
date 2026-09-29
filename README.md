# Super Studio 智能引擎扩展

此仓库仅用于发布 Super Studio「图转PPT」所需的 Windows 智能引擎扩展包。

## 用户下载方式

桌面软件在首次使用图转功能时，会自动获取当前稳定版本、校验完整性并安装到软件私有目录。用户不需要手动处理运行环境或模型文件。

## 发布约定

每个稳定版本的 Release 必须包含：

- `SuperStudio-Intelligence-Engine-win-x64.zip`
- `engine-manifest.json`
- `SHA256SUMS.txt`
- `THIRD_PARTY_NOTICES.txt`

客户端只接受 HTTPS 地址、匹配的 SHA-256 和通过 `engine.json` 校验的包。
