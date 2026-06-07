# Inkwell — Typora Theme

A clean, reading-focused Typora theme pair with soft gray tones and refined typography. Available in light (**Inkwell**) and dark (**Inkwell Dark**) variants.

## Design Philosophy

Inkwell is built around one idea: the theme should disappear so your content can take center stage. Instead of heavy contrast and saturated colors, it uses layered gray tones to create visual hierarchy — headings lean blue-gray, body text sits in a warm dark gray, and code blocks use a subtle off-background that separates without shouting.

## Preview

### Inkwell (Light)

![image-20260607下午21516486](https://gitee.com/zhizhu_wlz/picgo/raw/master/setup/image-20260607下午21516486.png)

### Inkwell Dark

![image-20260607下午21421511](https://gitee.com/zhizhu_wlz/picgo/raw/master/setup/image-20260607下午21421511.png)

## Features

- **Two variants**: light mode with white background, dark mode with deep blue-gray (`#1a2030`)
- **Syntax highlighting**: full CodeMirror token coverage with 15+ color-mapped token types (keywords, strings, comments, numbers, functions, operators, types, decorators, tags, etc.)
- **Code blocks**: light gray background with language label header, line number support, and copy button styling
- **Tables**: rounded corners, zebra striping, hover highlight, and soft shadow
- **Blockquotes**: left border accent with tinted background card
- **Keyboard tags** (`<kbd>`): skeuomorphic key-cap styling
- **YAML front matter**: card layout with syntax-colored keys and values
- **Search highlights**: amber/yellow for matches, deep orange for current selection
- **Focus & Typewriter mode**: non-active blocks fade to 35% opacity for distraction-free writing
- **Sidebar / file manager**: full dark mode styling for Typora's file tree (Inkwell Dark)
- **Print optimized**: clean print stylesheet with URL annotations on links
- **Responsive**: adapts padding and font sizes for smaller screens

## Color Palette

### Inkwell (Light)

| Element | Color | Usage |
|---------|-------|-------|
| Background | `#ffffff` | Page background |
| Body text | `#3d4852` | Paragraphs, lists |
| Heading (H1) | `#1a2332` | Deep blue-gray |
| Heading (H2-H4) | `#2c3e50` | Medium blue-gray |
| Links | `#3b82c4` | Muted blue |
| Code background | `#f6f8fb` | Inline and block code |
| Inline code | `#c7254e` | Soft rose |
| Borders | `#e2e8f0` | Tables, rules, code blocks |

### Inkwell Dark

| Element | Color | Usage |
|---------|-------|-------|
| Background | `#1a2030` | Deep blue-gray |
| Body text | `#c4cdd8` | Soft light gray |
| Heading (H1) | `#edf1f7` | Near white |
| Heading (H2-H4) | `#a8b8cc` | Light blue-gray |
| Links | `#6ba8e0` | Sky blue |
| Code background | `#242e42` | Elevated dark panel |
| Inline code | `#f0a0b8` | Soft pink |
| Borders | `#2d3848` | Subtle dark borders |

### Syntax Highlighting (Dark mode)

| Token | Color | Name |
|-------|-------|------|
| Keywords | `#a78bfa` | Violet-400 |
| Strings | `#6ee7b7` | Emerald-300 |
| Comments | `#64748b` | Slate-500, italic |
| Numbers | `#fb923c` | Orange-400 |
| Functions | `#60a5fa` | Blue-400 |
| Operators | `#2dd4bf` | Teal-400 |
| Types / Built-ins | `#22d3ee` | Cyan-400 |
| Decorators | `#fbbf24` | Amber-400 |
| HTML Tags | `#f472b6` | Pink-400 |
| Punctuation | `#94a3b8` | Slate-400 |

## Installation

### macOS

1. Open Typora → **Preferences** (`Cmd + ,`)
2. Go to **Appearance** → click **Open Theme Folder**
3. Copy `inkwell.css` and/or `inkwell-dark.css` into the folder
4. Restart Typora
5. Select **Inkwell** or **Inkwell Dark** from the **Theme** menu

### Windows

1. Open Typora → **Preferences** (`Ctrl + ,`)
2. Go to **Appearance** → click **Open Theme Folder**
3. Copy `inkwell.css` and/or `inkwell-dark.css` into the folder (path: `%APPDATA%\Typora\themes`)
4. Restart Typora
5. Select **Inkwell** or **Inkwell Dark** from the **Theme** menu

### Linux

1. Copy the CSS files to `~/.config/Typora/themes/`
2. Restart Typora and select the theme

## Typography

- **Sans-serif** (body & headings): System font stack — SF Pro (macOS), Segoe UI (Windows), Noto Sans SC / PingFang SC / Microsoft YaHei (CJK)
- **Monospace** (code): JetBrains Mono → Fira Code → SF Mono → Menlo → Consolas
- **Base size**: 15px
- **Line height**: 1.75 (body), 1.65 (code blocks)

## Compatibility

Tested with Typora 1.x on macOS. The theme uses standard Typora CSS selectors and CodeMirror token classes, so it should work across platforms. Syntax highlighting covers CodeMirror tokens (`.cm-*`), Prism.js (`.token.*`), highlight.js (`.hljs-*`), and Pygments (`.highlight .*`).

## License

MIT
