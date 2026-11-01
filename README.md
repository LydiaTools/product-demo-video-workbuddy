# Product Demo Video Skill for WorkBuddy and Codex

WorkBuddy 和 Codex 的产品视频制作 Skill：从产品功能核验、口播分镜到可编辑 Remotion 成片。

[简体中文说明](README.zh-CN.md) · **English**

Turn a verified product workflow into a clear, editable short video. This Skill plans the product story, maps each line to an on-screen action, and builds an editable Remotion project with motion, captions, music, and export checks.

## What it does

- Checks the product category and supported features against current sources.
- Plans the hook, evidence, product result, and call to action before coding.
- Uses real product screenshots or recordings and keeps invented UI clearly illustrative.
- Builds an editable Remotion project with controlled movement, captions, music, and sound effects.
- Renders a sample before the full video and preserves approved outputs.
- Records asset sources, render settings, and verification notes.

## Install

Download the [complete Skill package](product-demo-video-workbuddy-公开候选.zip), extract it, then copy the `product-demo-video-workbuddy` folder into your WorkBuddy or Codex skills directory. Keep `SKILL.md`, `references/`, `scripts/`, and `assets/` together.

## Requirements

- WorkBuddy or Codex with local file and shell access
- Node.js 18+, Python 3, FFmpeg and FFprobe
- A Remotion-compatible project; Remotion has separate licensing terms
- Rights to use each product image, logo, font, soundtrack, and sound effect

## BFTiles example

The Skill was run in WorkBuddy for a Windows desktop window-layout product. The resulting 15-second landscape sample and editable project are kept in the production workspace; this repository contains the reusable Skill, not that production workspace.

## Source and licensing

Adapted from [noamdorr/saas-product-demo-video](https://github.com/noamdorr/saas-product-demo-video), an MIT-licensed Remotion Skill. The upstream license is retained in `LICENSE.upstream`; this adaptation is MIT licensed. Review Remotion and third-party asset terms separately before commercial use.
