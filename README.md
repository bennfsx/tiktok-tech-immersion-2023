# Tiktok Tech Immersion 2023 Assignment

Link: ![Tests](https://github.com/TikTokTechImmersion/assignment_demo_2023/actions/workflows/test.yml/badge.svg)

This is a demo and template for backend assignment of 2023 TikTok Tech Immersion.

## Requirements
https://bytedance.sg.feishu.cn/docx/P9kQdDkh5oqG37xVm5slN1Mrgle
1. Architecture
2. Data storage
3. Message delivery
4. Performance and scalability


![image](https://github.com/bennfsx/tiktok-tech-immersion-2023/assets/44813216/7a6a3e40-f0f5-462e-8910-978d0c2b02ea)

## Installation

Requirement:

- golang 1.18+
- docker

To install dependency tools:

```bash
make pre
```

## Run

```bash
docker-compose up -d
```

Check if it's running:

```bash
curl localhost:8080/ping
```
