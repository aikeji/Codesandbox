# xray for CodeSandbox

在 CodeSandbox 部署 xray 节点

## 项目特点

* 本项目用于在 CodeSandbox 上部署 xray ，采用的方案为 Node.js + WebSocket + VMess/Vless/Trojan/Shadowsocks + TLS
* vmess 和 vless 的 uuid 或 trojan 和 shadowsocks 的密码，路径既可以自定义，又或者使用默认值
* 部署完成如发现不能上网，请检查域名是否被墙，可使用 Cloudflare CDN 或者 worker 解决。

## 步骤

* 注册 [CodeSandbox](https://codesandbox.io/)
* 进入首页，找到“Start from a template”，选择下面Node.js
* 创建成功之后，左边栏，把所有文件全部删除，包含.codesandbox文件夹也删除
* 下载项目文件到本地，
* 网页中，在左边栏，右键，选择“Upload files”，然后上传项目文件到项目中（除了LICENSE和README.md）（除了LICENSE和README.md）
* 点击左上角的正方形图标，然后点击“Project settings”
* 转到“Env Variables”处，设置环境变量
* UUID，NEZHA_SERVER，NEZHA_PORT，NEZHA_KEY......
* 设置完成后，点击左上角的正方形图标，然后点击“Restart Sandbox”按钮

