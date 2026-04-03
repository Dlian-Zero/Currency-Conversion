# 💱 外汇汇率小组件 (ExchangeRate Widget)

[![API](https://img.shields.io/badge/API-聚合数据-1E90FF)](https://www.juhe.cn/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

基于 Scripting 运行的外汇汇率查看工具，通过**聚合数据 API** 实时获取多种货币的**现汇卖出价 (fsellpri)**。支持多币种选择、AppKey 配置、原始响应调试及自动更新日志提示。

<div align="center">
  <img src="https://github.com/user-attachments/assets/4873d189-e275-4fdc-a1e2-2149ed10a0be" alt="预览图1" />
  <img src="https://github.com/user-attachments/assets/bcedb3db-27f7-45ed-879d-de0a96b8d155" alt="预览图2" />
</div>


## ✨ 功能特性

- 🏦 **实时汇率**：展示四种货币兑人民币 (CNY) 的现汇卖出价
- 🔐 **API 密钥管理**：可视化设置聚合数据 AppKey，状态实时显示
- ⚙️ **自定义币种**：通过设置页面自由选择想显示的 4 种货币
- 📜 **更新日志**：自动检测新版本更新内容，支持手动查看
- 🛠️ **调试工具**：展示 API 原始返回 JSON，方便字段适配与问题排查
- 📱 **模态页面**：以 `pageSheet` 风格呈现，符合 iOS 交互习惯

## 📦 前置要求

- 设备：iPhone / iPad（iOS 14+）
- 应用：[Scripting](https://apps.apple.com/us/app/scripting/id6479691128)（需提前安装）
- 网络：需要互联网连接以调用聚合数据 API
- 账号：[聚合数据](https://www.juhe.cn/) 免费/付费 API 密钥

<div align="center">
  <div style="margin-top: 8px;">
    <a 
      href="https://scripting.fun/import_scripts?urls=%5B%22https%3A%2F%2Fscripting.fun%2Fimport_scripts%3Furls%3D%255B%2522https%253A%252F%252Fgithub.com%252FDlian-Zero%252FCurrency-Conversion%252Fraw%252Frefs%252Fheads%252Fmain%252F%2525E5%2525A4%252596%2525E5%2525B8%252581%2525E6%2525B1%252587%2525E7%25258E%252587.scripting%2522%255D%22%5D" 
      style="display: inline-block; background: linear-gradient(135deg, #2c7a4d, #1e5a3a); color: white; font-size: 1rem; font-weight: 600; padding: 10px 28px; border-radius: 40px; text-decoration: none; box-shadow: 0 4px 12px rgba(0,0,0,0.15);">
      🚀 一键导入
    </a>
  </div>
</div>
