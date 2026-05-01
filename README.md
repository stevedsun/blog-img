# blog-img

图片仓库，用于博客中引用的图片资源。

## 图片链接格式

当图片被推送到 GitHub 远程仓库后，可通过以下格式访问图片：

```
https://raw.githubusercontent.com/{owner}/{repo}/{branch}/{filepath}
```

### 示例

假设图片文件名为 `example.png`，仓库信息如下：

- 仓库地址：`git@github.com:stevedsun/blog-img.git`
- 默认分支：`main`

则图片链接为：

```
https://raw.githubusercontent.com/stevedsun/blog-img/main/example.png
```

### 常见场景

| 场景 | 链接格式 |
|------|----------|
| 直接查看 raw 文件 | `https://raw.githubusercontent.com/stevedsun/blog-img/main/图片文件名.png` |
| 在 Markdown 中引用 | `![](https://raw.githubusercontent.com/stevedsun/blog-img/main/图片文件名.png)` |

## 注意事项

1. **链接区分大小写**：文件名的大小写必须与仓库中实际文件名一致。
2. **路径编码**：如果文件名包含空格或特殊字符，需要进行 URL 编码（如空格变为 `%20`）。
3. **分支确认**：确认图片所在分支，默认情况下使用 `main` 分支。

## 当前仓库文件列表

| 文件名 | 大小 |
|--------|------|
| ai-agent-mcp-header-900x383.png | ~179 KB |
| device.png | ~949 KB |
| kernel-panic-screenshot.png | ~211 KB |
| memos-memory-management-header-900x383.png | ~9.6 KB |
| Pasted image (2).png | ~16 MB |
| Pasted image (3).png | ~5.3 MB |
| Pasted image (4).png | ~1.6 MB |
| typora-icon.png / typora-icon2.png | ~1.3 KB / ~567 B |
| 微信图片_20211001122730.jpg | ~14 KB |