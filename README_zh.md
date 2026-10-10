# JSON 在线解析 — 意见反馈

[English](README.md) | [中文](README_zh.md)

这个仓库用来收集 [JSON 在线解析](https://json.site/cn) 的意见反馈和功能建议。

感谢你使用 JSON 在线解析！

使用过程中遇到问题，或者有功能建议，欢迎随时提交反馈。

## 如何提交

- 前往 [GitHub Issues](https://github.com/bygo/json.site/issues) 创建一个[新的 Issue](https://github.com/bygo/json.site/issues/new)
- 简要描述你的问题或建议
- 如有必要，附上截图或示例 JSON

我会尽快查看并回复，感谢支持！

## 更新日志

### 2026-09-16

- **JSONC** —— 设置中可开启「允许 JSON 注释」，支持注释与尾随逗号，格式化时保留注释

### 2026-09-15

- **JSON 分享** —— 工具栏一键生成压缩分享链接（写入 URL hash），打开即可还原数据

### 2026-08-12

- **链接跳转修复** —— 编辑器内点击带查询参数的 http(s) 链接时，不再错误编码 `=`、`&`

### 2026-08-09

- **图视图全部展开/折叠** —— 工具栏一键展开或收起所有结构节点
- **连线可点击** —— 加宽命中区域，点击连线可选中子节点并高亮链路
- **折叠更聪明** —— 折叠某节点时保留子节点展开状态，再次展开可恢复先前布局
- **双指/滚轮缩放更快** —— 触控板与滚轮缩放灵敏度翻倍，浏览更跟手

### 2026-08-08

- **本地隐私提示** —— 历史记录面板顶部增加可关闭提示
- **图视图文字更清晰（Windows）** —— 修复缩放时卡片文字发虚

### 2026-08-05

- **图视图** —— 以交互式图浏览 JSON（平移、缩放、全屏、适应视图）
- **标量数组与高亮** —— 图节点按类型着色标量；标量数组内联展示并按元素着色

### 2026-08-01

- **树字体大小** —— 树视图取值跟随全局字号设置
- **工具栏布局** —— 窄屏下操作栏换行更合理

### 2026-07-30

- **树双击编辑** —— 修复树视图双击编辑键名/值
- **导出修复** —— 无效 JSON 提示更清晰，多格式导出更可靠

### 2026-07-29

- **编辑器滚动 CLS** —— 减少编辑器滚动时的布局偏移
- **单元格编辑** —— 修复进入单元格编辑时重复触发

### 2026-07-27

- **多格式导入导出** —— 支持 CSV / Excel / YAML / XML / JSONL / Markdown / SQL 等上传与导出

### 2026-07-24

- **树虚拟滚动** —— 大 JSON 树形视图更流畅
- **表头拖拽** —— 拖动表头可调整列顺序
- **树形编辑** —— 双击树节点即可编辑

### 2026-07-21

- **列隐藏** —— 隐藏表头列，通过左上角角格的按钮编辑
- **框选删除** —— 拖拽框选单元格后删除

### 2026-07-08

- **JSON Path语法更新** —— 更新为标准的JSON path语法
- **大幅重构表格** —— 支持虚拟滚动、笛卡尔积选择复制、重做UX

### 2026-06-28

- **一键截图** —— 一键将格式化后的 JSON 导出为图片
- **多语言** —— 支持切换界面语言

### 2026-06-07

- **JSON Path** —— 将光标定位到节点即可提取其路径（如 `[2].article.name`）并填入筛选框
- **快捷键面板** —— 查看并自定义快捷键，浏览器默认按键已妥善处理
- 修复展开时滚动位置异常的问题

<!-- changelog-synced: da898e67b902f9f89705771be284d4f7c8050ef5 -->

## Star History

<a href="https://www.star-history.com/?repos=bygo%2Fjson.site&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=bygo/json.site&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=bygo/json.site&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=bygo/json.site&type=date&legend=top-left" />
 </picture>
</a>
