# NapCat 安装指南
适合新手的零基础安装教程，5分钟搞定！

## 一、准备工作
- 电脑系统：Windows 10/11 或 Mac OS 12+
- 必备工具：Node.js（版本 ≥18，下载地址：https://nodejs.org/）
- 安装包：NapCat 最新版（官网：https://napneko.github.io/）

## 二、具体安装步骤
1. 打开 Node.js 安装包，一路点「下一步」，最后勾选「Add to PATH」再完成。
2. 下载 NapCat 压缩包，右键解压到桌面（比如解压到「NapCat-v1.0」文件夹）。
3. 打开文件夹，按住 Shift 键+右键，选「在此处打开终端」（Windows）或「新建终端窗口」（Mac）。
4. 输命令 `npm install`，等待30秒（出现 `added xxx packages` 就是成功）。
5. 输命令 `npm run start`，看到「Server running at http://localhost:3000」就启动成功了！

## 三、常见问题
- Q：命令报错「npm不是内部命令」？
  A：重新装 Node.js，记得勾选「Add to PATH」，装完重启终端再试。
- Q：启动后打不开网页？
  A：检查端口3000有没有被占用，换换命令 `npm run start -- --port 3001` 用3001端口。
