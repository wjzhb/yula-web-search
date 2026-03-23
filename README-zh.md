# 🔍 yula-web-search

<img src="./img/logo.png" width="100" alt="yula-web-search logo">

===========

无需 API Key 的 OpenClaw 网页搜索技能。直接走本地网络/代理，自动搜索提取内容并总结，专为中文搜索优化。

## 功能特点

- ❌ **不需要 API Key** — 开箱即用，无需配置
- 🔍 **Bing 搜索为主，Google 搜索为备用**
- 📝 **自动提取内容** — 从最相关的结果提取正文
- 🧠 **自动汇总回答** — 不需要用户点击链接，直接得到整合后的答案
- 🇨🇳 **专为中文搜索优化** — 对中文结果排序提取更精准
- 📦 支持本地网络/代理 — 不需要外部 API 服务

## 工作流程

```
1. Bing 搜索 → 得到 (标题 + URL)
    ↓
2. 根据相关性筛选 → 选出 top 2-3
    ↓
 3. 逐个提取网页正文内容
    ↓
 4. 合并所有内容
    ↓
 5. 总结汇总得到最终回答
    ↓
 6. 带上来源链接呈现给用户
```

## 作者

创建者 **Yula**  
GitHub: https://github.com/wjzhb/yula-web-search

如果你觉得这个技能有用，**欢迎去 GitHub 点个 ⭐ Star！**

## ☕ 打赏支持

如果你喜欢这个项目，想要支持开发，可以通过以下方式打赏：

<div align="center">
  <table>
    <tr>
      <td align="center">
        <b>微信</b><br>
        <img src="./img/wechat-qrcode.jpg" width="200" alt="微信收款二维码">
      </td>
      <td align="center">
        <b>支付宝</b><br>
        <img src="./img/alipay-qrcode.jpg" width="200" alt="支付宝收款二维码">
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        <b>BNB (BSC)</b><br>
        <code>0x5bcc2Cec253a7d625b7A98049C8775c61750f812</code>
      </td>
    </tr>
  </table>
</div>

## 版权

Copyright (c) 2026 [Yula](https://github.com/wjzhb)

使用 MIT 许可证开源 - 详见 [LICENSE](LICENSE)

---

**English version**: [README.md](./README.md)
