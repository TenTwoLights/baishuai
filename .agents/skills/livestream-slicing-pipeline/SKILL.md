---
name: livestream-slicing-pipeline
description: Plan and verify Douyin fashion livestream clipping from transcript, denoising, style segmentation, and video cuts through final rendering or Studio delivery.
---

# 女装直播切片流程

1. 确认当前环节及交付，当用户只要求清洗时使用 livestream-transcript-cleaner。整链按消音、转录、款式切分、组合渲染。先查输入路径、目标款、转录对应视频和依赖，原素材只读。
2. 提交方案列备选角度、行号范围、选取理由和风险。等确认后再执行未经选定的钩子、CTA、改写和成批出片。每片集中一个卖点，分镜原话照录，同批切片避免重复使用原行。口播改写仅在该模式获准时重组，保留事实依据。
3. 视频切点优先使用句级 ASR 时间码。只能按段估算时标明精度并抽听，不承诺句级精度。独立导出时保持原片段顺序，原技能建议段首尾各留 1.5 秒，相邻间隔不足 3 秒则按中点分配，防止剪入邻段说话。复查余量是否带入禁词。
4. 渲染前确认实际可用的程序与 A1 运镜花字、B1 字幕规格版本。花字只取允许的痛点原话。缺规格时说明缺项。检查字幕对齐、音轨、静止尾巴、段落及成品可播放。工作台交付用真实界面跑一遍输入到导出，检查失败提示。消音独立任务只交 MP4，放任务目录的去除杂音子目录。
5. 版本另存，列改动、交付文件、核验结果和未验证项。

