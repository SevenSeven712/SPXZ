<div align="center">
  
  <!-- 你的头像（如果是圆角，使用了简单的内联样式） -->
  <img src="https://github.com/SevenSeven712.png" width="120" style="border-radius: 50%; box-shadow: 0 4px 8px rgba(0,0,0,0.2);" alt="SevenSeven712 Avatar" />
  
  <h1>🎬 SPXZ - 国内短视频下载插件</h1>

  <!-- 动态打字机效果 -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=0055FF&center=true&vCenter=true&width=500&lines=%E8%BD%BB%E9%87%8F%E3%80%81%E7%BA%AF%E5%87%80%E3%80%81%E6%97%A0%E5%B9%BF%E5%91%8A;%E4%B8%80%E9%94%AE%E8%A7%A3%E6%9E%90%E5%9B%BD%E5%86%85%E4%B8%BB%E6%B5%81%E7%9F%AD%E8%A7%86%E9%A2%91;%E8%AE%A9%E6%94%B6%E8%97%8F%E5%8F%98%E5%BE%97%E6%9B%B4%E7%AE%80%E5%8D%95" alt="Typing SVG" />
  </a>

  <!-- 徽章区 -->
  <p>
    <a href="https://github.com/SevenSeven712/SPXZ/stargazers"><img src="https://img.shields.io/github/stars/SevenSeven712/SPXZ?style=for-the-badge&color=yellow" alt="Stars"></a>
    <a href="https://github.com/SevenSeven712/SPXZ/releases"><img src="https://img.shields.io/github/v/release/SevenSeven712/SPXZ?style=for-the-badge&color=blue" alt="Release"></a>
    <a href="https://github.com/SevenSeven712/SPXZ/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey?style=for-the-badge" alt="License"></a>
  </p>

  <p>一个专为国内用户打造的浏览器扩展，让视频下载回归纯粹。</p>
</div>

<br/>

## 🌟 关于 SPXZ

**SPXZ** 是一款极简的浏览器短视频下载扩展。无需繁琐的复制粘贴，告别烦人的水印和广告。打开页面，点击解析，一键保存，给你最丝滑的离线收藏体验。

## ✨ 核心亮点

<table>
  <tr>
    <td align="center" width="33%">
      <h3>🚀 极速解析</h3>
      <p>智能嗅探页面视频流<br>点击瞬间完成解析</p>
    </td>
    <td align="center" width="33%">
      <h3>💧 无水印原画</h3>
      <p>绕过平台压制<br>直取最高清无水印源</p>
    </td>
    <td align="center" width="33%">
      <h3>🍃 纯净无广</h3>
      <p>无弹窗、不追踪<br>开源透明，安全放心</p>
    </td>
  </tr>
</table>

> 💡 **多平台支持**：目前兼容抖音、快手、B站、小红书等主流自媒体平台。*(具体支持情况视各大平台前端更新而定)*

## 🛠️ 极速安装指南

由于扩展尚未上架应用商店，请通过“开发者模式”进行本地安装：

1. 前往本仓库的 [Releases](https://github.com/SevenSeven712/SPXZ/releases) 页面，下载最新版的 `.zip` 压缩包。
2. 将压缩包**解压**到一个你熟知的文件夹中。
3. 打开浏览器（Chrome / Edge / 360 等 Chromium 内核浏览器），在地址栏输入：
   - Chrome：`chrome://extensions/`
   - Edge：`edge://extensions/`
4. 在扩展页面右上角，开启 **“开发者模式”** 开关。
5. 点击左上角的 **“加载已解压的扩展程序”**。
6. 选中你刚才解压出来的那个文件夹（确保里面包含 `manifest.json` 文件），完成安装！

## 🚀 怎么使用？

```mermaid
graph LR
A[打开短视频网页] --> B(点击浏览器右上角 SPXZ 图标)
B --> C{等待解析完成}
C --> D[点击下载保存至本地]
