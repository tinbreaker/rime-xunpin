# 勳拼输入方案 / Xunpin Input Method

西夏文拼音输入方案，基于龔勳擬音系统。
A Tangut phonetic input method based on Gong Xun's reconstruction system.

## 简介 / Introduction

勳拼是一个为输入西夏文设计的拼音方案。它采用龔勳的西夏语拟音系统，使用拉丁字母表示。
Xunpin is a phonetic input method designed for typing Tangut characters. It uses Gong Xun's reconstruction system represented in Latin alphabet.

## 特点 / Features

- 采用拉丁字母转写 / Uses Latin alphabet transcription
- 声调标记系统 / Tone marking system:
  - 无标记 = 平声 / No mark = level tone
  - x后缀 = 上声 / Suffix x = rising tone
- 支持全角/半角切换 / Supports full/half-width character switching
- 支持中英文标点切换 / Supports Chinese/English punctuation switching

## 使用方法 / Usage

1. 基本输入 / Basic Input:
   - 直接输入拼音 / Type pinyin directly
   - 例如 / Example: `tjiw` → 𗉔

2. 声调输入 / Tone Input:
   - 平声：无需额外标记 / Level tone: No additional mark needed
   - 上声：加x后缀 / Rising tone: Add suffix x
   - 例如 / Example: `sjihx` → 𗉝

3. 笔画输入 / Stroke Input:
    - 输入 `f` 开启 / Input `f` to enable
    - 例如 / Example: `focaaabcccq` → 𘓐
    - 支持输入部件 / Supports inputting components

4. 四角号码输入
    - 输入 `v` 开启 / Input `v` to enable
    - 例如 / Example: `v134420` → 𗉔

## 安装 / Installation

1. 安装Rime输入法 / Install Rime
2. 将方案文件放入Rime用户文件夹 / Put schema files into Rime user directory
3. 重新部署 / Redeploy

## 配置文件说明 / Configuration Files

- `xunpin.schema.yaml`: 主方案文件 / Main schema file
- `xunpin.dict.yaml`: 码表文件 / Dictionary file

## 字体要求 / Font Requirements

需要安装支持西夏文的字体（如 Tangut N4694）
Requires installation of fonts supporting Tangut script (e.g., Tangut N4694)

## 致谢 / Acknowledgments

- 龔勳的西夏语拟音研究 / Gong Xun's research on Tangut phonetic reconstruction
- RIME输入法框架 / RIME Input Method Framework
- 新萱拼 / xinxuanping