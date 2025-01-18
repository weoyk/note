---
title: 发布工具平台配置指南
date: '2024-12-02 10:53:55'
updated: '2025-01-18 13:35:49'
permalink: /post/publishing-tool-platform-configuration-guide-z28nyqd.html
comments: true
toc: true
---

UiPath 平台配置工具是一个PowerShell脚本，用于帮助您成功安装/升级Orchestrator。它可以帮助您在升级之前检查环境的完整性和就绪性，并帮助您在安装后执行一些操作。

该工具可从下方下载，而且还与 `UiPathOrchestrator.msi`​ 安装程序捆绑。捆绑的脚本可以在 Orchestrator 安装目录的 `Tools`​ 文件夹中找到，默认位置为 `C:\Program Files (x86)\UiPath\Orchestrator\`​。该脚本会检查 Orchestrator 计算机。多节点安装时，在一个节点上运行该工具便已足够。

平台配置工具不遵循与 `UiPathOrchestrator.msi`​ 安装程序相同的版本控制模式，而且可以在产品发布周期外进行更新。我们建议您始终下载并使用以下工具的最新版本。

‍

‍
