# dwsal

dwsal 是钉钉假勤管理 CLI / MCP Server 工具，用于查询和操作考勤组、班次、排班、排班规则、用户、部门、假期规则、假期余额等业务能力。

本仓库仅用于发布 dwsal 的二进制发布包，不包含源码。

## 安装

推荐通过 npm 安装：

```bash
npm install -g dwsal
```

npm 安装包会根据当前系统自动下载对应平台的二进制发布包。

## MCP Server

安装后可以作为 MCP STDIO Server 使用：

```bash
dwsal --mcp-server
```

在支持 MCP 的客户端中配置命令：

```json
{
  "command": "dwsal",
  "args": ["--mcp-server"]
}
```

## 手动下载

如需手动下载，请到 Releases 页面选择对应平台：

- `dwsal-win-x64.zip`
- `dwsal-linux-x64.zip`
- `dwsal-osx-arm64.zip`
- `dwsal-osx-x64.zip`

Release 地址：

```text
https://github.com/QiChangWei/dwsal/releases
```

## 说明

- Windows 发布包内文件名为 `dwsal.exe`。
- Linux / macOS 发布包内文件名为 `dwsal`。
- Gitee 备用发布地址：`https://gitee.com/qichangwei520/dwsal/releases`。
