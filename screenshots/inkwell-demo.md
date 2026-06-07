# Inkwell 主题预览

这是一份用于展示 **Inkwell** 主题排版效果的示例文档。主题采用柔和灰调配色，专注于阅读体验。

## 基本排版

正文使用系统字体栈，支持中英文混排。行高设定为 `1.75`，确保长时间阅读不疲劳。**加粗文本** 使用更深的色调突出，*斜体文本* 保持自然倾斜。这里有一个 [行内链接示例](#)，以及 `inline code` 标记。

> "好的排版不是让人注意到设计，而是让人专注于内容。"
> — 某位设计师

### 列表

1. 有序列表第一项 — 步骤清晰明了
2. 有序列表第二项 — 编号使用加粗样式
3. 有序列表第三项 — 适合教程和指南

- 无序列表支持嵌套
  - 子项 A
  - 子项 B

### 快捷键

按 `Cmd` + `S` 保存，`Cmd` + `Shift` + `P` 打开命令面板。

## 代码块

```python
# Theme Installer
import os
import shutil

def install_theme(name: str):
    """Install a Typora theme."""
    themes_dir = os.path.expanduser(
        "~/Library/Application Support/abnerworks/Typora/themes"
    )
    source = f"./{name}.css"
    dest = os.path.join(themes_dir, f"{name}.css")
    
    if os.path.exists(themes_dir):
        shutil.copy2(source, dest)
        print(f"Theme '{name}' installed!")
    else:
        print("Themes directory not found.")

if __name__ == "__main__":
    install_theme("inkwell")
```

## 表格

| 元素 | 亮色模式 | 暗色模式 | 用途 |
|------|---------|---------|------|
| 正文 | `#3d4852` | `#c4cdd8` | 主要文字 |
| 标题 | `#1a2332` | `#edf1f7` | 一级标题 |
| 链接 | `#3b82c4` | `#6ba8e0` | 超链接 |
| 代码 | `#f6f8fb` | `#242e42` | 代码块背景 |
