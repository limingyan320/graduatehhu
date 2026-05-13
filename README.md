# ronnbunn

给导师汇报用的 reveal.js 幻灯片，重点介绍两个项目的批处理：

- **receipt-judge** — 标注队列 / rerun batch（后端自治生命周期）
- **tts-bertvits2** — TTSBag 袋装批处理 / TTSBus 公交发车模型

## 本地预览

reveal.js / mermaid 都走 CDN，所以不需要 `npm install`，
随便起一个静态服务器就行：

```bash
# 任选其一
python3 -m http.server 8000
# 或
npx serve .
```

然后浏览器打开 `http://localhost:8000/`。

## 操作

- 方向键 / Space 翻页
- `f` 全屏，`s` 演讲者视图，`o` 概览
- `?` 看完整快捷键

## 文件

```
ronnbunn/
├── index.html   # 幻灯片主体
├── styles.css   # 自定义样式
└── README.md
```

幻灯片里的所有流程图 / 时序图 / mindmap / gantt 均由
[mermaid](https://mermaid.js.org/) 在浏览器里实时渲染。
