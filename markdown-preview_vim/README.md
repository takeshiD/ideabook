# markdown-preview vim plugin

## Architecture

![](/markdown-preview_vim/markdown-preview_vim.drawio.svg)

# Framework

![](/markdown-preview_vim/markdown-preview_framework.drawio.svg)

## Todo
- CLI
    - [ ] コマンドラインパーサーの実装
- Parser
    - [] AST Interfaceの設計
    - [] AST Interfaceのmarkdown-rsの実装
    - [] 拡張用APIの設計
    - [] 拡張用APIの実装
- Renderer
    - Other Node
        - [] ASCII Rendererの実装
        - [] HTML Rendererの実装
    - Mermaid
        - [] MermaidParser
        - MermaidRenderer
            - [] ASCII
            - [] Image
    - KaTeX
        - [] KaTeX Parser
        - KaTeXRenderer
            - [] ASCII
            - [] Image
- Drawer
    - TerminalDrawer
        - ImageDrawer
            - ueberzugpp
    - BrowserDrawer
    - File
        - PDF
        - HTML
        - ePUB
- Preview Function(for Terminal, Browser)
    - 
