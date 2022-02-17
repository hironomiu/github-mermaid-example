# github-mermaid-example

GitHubでMarkdownを記述する際にmermaidの利用例

[公式ブログ](https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/)

```mermaid
graph TD
    A[Christmas] -->|Get money| B(Go shopping)
    B --> C{Let me think}
    C -->|One| D[Laptop]
    C -->|Two| E[iPhone]
    C -->|Three| F[fa:fa-car Car]
```

## VSCode

VSCode上では[Markdown Preview Mermaid Support](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)の拡張機能でPreview可能