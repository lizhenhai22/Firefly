---
title: "IconGlass · 玻格桌面"
slug: iconglass
published: 2026-11-28
order: 1
description: "Windows 10 / 11 原生毛玻璃多桌面图标布局管理与切屏自动守护工具。基于 .NET 10 WPF 与原生 Win32 API（零第三方依赖），内置 6 套毛玻璃配色、实时透明度调节、多桌面方案库、实时微缩图 Diff 对比与一键智能整理，彻底终结 1080p 与 3K 切屏桌面图标乱飞。"
image: "images/iconglass-preview.png"
status: "published"
tags:
  - Windows 11
  - .NET 10
  - WPF
  - Acrylic
  - 开源工具
link:
  - label: "GitHub"
    icon: "fa7-brands:github"
    value: "https://github.com/lizhenhai22/IconGlass"
  - label: "下载"
    icon: "material-symbols:download"
    value: "https://github.com/lizhenhai22/IconGlass/releases/tag/v1.0.0"
  - label: "介绍文章"
    icon: "material-symbols:article"
    value: "/posts/iconglass-desktop-manager/"
---

## 项目简介

**IconGlass（玻格桌面）** 是一款专为 Windows 10 / 11 打造的原生毛玻璃多桌面图标布局管理与切屏自动守护工具（MIT 开源）。

它针对 **3K 高分屏笔记本（200% 缩放）与 1080p 外接显示器（100% 缩放）来回切换、休眠唤醒导致的桌面图标乱飞** 问题，提供不重启资源管理器的精准坐标还原与高颜值毛玻璃交互体验。

## 视频演示

<div style="margin: 1rem 0; border-radius: 14px; overflow: hidden; box-shadow: 0 10px 28px rgba(15, 23, 42, 0.14);">
  <video
    controls
    playsinline
    preload="metadata"
    poster="/assets/images/iconglass-poster.png"
    style="width: 100%; display: block; background: #0f172a;"
  >
    <source src="/assets/videos/iconglass-promo.mp4" type="video/mp4" />
  </video>
</div>

## 核心特性

- [x] **原生 Win11 毛玻璃工坊** — 亚克力（Acrylic）/ 云母（Mica）/ 纯净半透明切换，25%–96% 实时透明度滑块，6 套主题配色（晨雾白 / 晴空蓝 / 薄荷晴 / 樱霞粉 / 星夜紫 / 曜石黑）
- [x] **多桌面方案库** — 无限命名快照、Emoji 徽章、标签筛选、按图标名反查方案与 JSON 导入导出
- [x] **实时桌面微缩图 & Diff 对比** — 着色区分应用 / 文件夹 / 文件 / 系统图标，恢复前先看红线移动路径
- [x] **切屏 / DPI / 休眠自动恢复** — Per-Monitor DPI v2 感知，防碰撞网格还原，绝不重启 `explorer.exe`
- [x] **一键智能整理 & 一键撤销** — 内置 3 套整理预设（含底行留空与 1080p/3K 通用安全区）、自动撤销栈、演示模式隐显图标与开机静默自启

## 获取方式

- 直接前往 [GitHub Releases](https://github.com/lizhenhai22/IconGlass/releases) 下载单文件可执行版（提供 938 KB 轻量版与双击即用独立版）。
- 完整图文介绍与原理解密请参阅博客文章：[IconGlass · 玻格桌面详细介绍](/posts/iconglass-desktop-manager/)。
