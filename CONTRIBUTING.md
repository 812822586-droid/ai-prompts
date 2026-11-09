# 贡献指南 · Contributing

感谢你愿意补充提示词！本项目欢迎任何人提交实用的中文 Prompt。

## 怎么贡献一条提示词

1. Fork 本仓库
2. 编辑 `prompts-data.js`（或同步编辑 `prompts.json`），在数组末尾追加一条：

```js
{
  "id": "x99",          // 唯一编号，不要和已有重复
  "title": "简短标题",
  "category": "写作与文案", // 使用已有分类名，或提 Issue 申请新分类
  "tags": ["标签1", "标签2"],
  "prompt": "完整提示词正文，需要用户填写的地方用【占位符】标出",
  "tip": "一行使用小贴士"
}
```

3. 本地用浏览器打开 `index.html`，确认能搜到、能复制
4. 提交 Pull Request，简要说明适用场景

## 质量要求

- **原创**：请写你自己的提示词，不要整段粘贴受版权保护的合集
- **实用**：针对真实场景，占位符要清楚
- **中文优先**：面向中文用户；角色扮演类可中英混排
- **安全合规**：不要诱导违法、欺诈、医疗夸大承诺等内容

## English

Add a prompt object to `prompts-data.js` / `prompts.json`, open `index.html` locally to verify, then open a PR. Keep prompts original, practical, and China-scenario friendly.
