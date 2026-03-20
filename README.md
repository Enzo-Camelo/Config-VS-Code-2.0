# ⚙️ VS Code — Configurações Pessoais
Configuração minimalista e produtiva para o **Visual Studio Code**, focada em legibilidade, performance e DX (Developer Experience).

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/500px-Visual_Studio_Code_1.35_icon.svg.png" width="50" />

---

## 🛠️ Como aplicar
1. Abra o VS Code  
2. Pressione **`Ctrl + Shift + P`**  
3. Selecione **Preferences: Open User Settings (JSON)**  
4. Cole o conteúdo abaixo

---

## 📄 `settings.json`
> 💡 Dica: passe o mouse sobre o bloco e clique no ícone 📋 para copiar tudo.

```json
{
  "workbench.startupEditor": "none",
  "github.copilot.chat.localeOverride": "pt-br",
  "files.autoSave": "afterDelay",

  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 14,
  "editor.lineHeight": 1.8,
  "editor.fontLigatures": true,

  "editor.rulers": [80, 120],
  "editor.renderLineHighlight": "gutter",
  "editor.semanticHighlighting.enabled": true,
  "editor.minimap.enabled": false,

  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "editor.formatOnType": true,

  "workbench.editor.labelFormat": "short",
  "workbench.tree.indent": 12,
  "explorer.compactFolders": false,

  "terminal.integrated.fontLigatures.enabled": true,

  "github.copilot.enable": {
    "*": true,
    "plaintext": false,
    "markdown": true,
    "scminput": false,
    "python": true,
    "html": true
  },
  "github.copilot.nextEditSuggestions.enabled": true,

  "explorer.fileNesting.patterns": {
    "*.ts": "${capture}.js",
    "*.js": "${capture}.js.map, ${capture}.min.js, ${capture}.d.ts",
    "*.jsx": "${capture}.js",
    "*.tsx": "${capture}.ts",
    "tsconfig.json": "tsconfig.*.json",
    "package.json": "package-lock.json, yarn.lock, pnpm-lock.yaml, bun.lockb, bun.lock",
    "*.sqlite": "${capture}.${extname}-*",
    "*.db": "${capture}.${extname}-*",
    "*.sqlite3": "${capture}.${extname}-*",
    "*.db3": "${capture}.${extname}-*",
    "*.sdb": "${capture}.${extname}-*",
    "*.s3db": "${capture}.${extname}-*",
  },
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "Dracula Theme",
  "geminicodeassist.inlineSuggestions.enableAuto": false,
  "code-runner.runInTerminal": true,
  "geminicodeassist.project": "fourth-invention-h92sd",
  "python.terminal.activateEnvironment": true,
}
```

## 🎨 Tema & Aparência

**Tema:** Dracula Theme

**Ícones:** Material Icon Theme

**Fonte:** [JetBrains Mono ↗](https://www.jetbrains.com/lp/mono/)

## 🧩 Extensões Utilizadas

- Dracula Official Theme
- GitHub Copilot Chat
- Gemini Code Assist
- Live Server
- Material Icon Theme
- Prettier
- Python
- Color Highlight
- Tailwind CSS
- Auto Rename Tag
- Auto Import
