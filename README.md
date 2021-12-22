```json
{
    "editor.fontSize": 16,
    "editor.fontLigatures": true,
    "files.associations": {
        "*.js": "javascriptreact",
        "*.cjson": "jsonc",
        "*.wxss": "css",
        "*.wxs": "javascript",
        "*.html": "html"
    },
    "emmet.includeLanguages": {
        "wxml": "html"
    },
    "minapp-vscode.disableAutoConfig": true,
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    },
    "javascript.updateImportsOnFileMove.enabled": "always",
    "git.ignoreWindowsGit27Warning": true,
    "cssrem.rootFontSize": 80,
    "openFormGenerator.src": "https://mrhj.gitee.io/form-generator/#/",
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
    "workbench.iconTheme": "vscode-icons",
    "eslint.enable": true,
    "eslint.run": "onType",
    "eslint.options": {
        "extensions": [
            ".js",
            ".vue",
            ".jsx",
            ".tsx"
        ]
    },
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
    "vetur.format.defaultFormatterOptions": {
        "js-beautify-html": {
            "wrap_line_length": 120,
            "wrap_attributes": "auto",
            "end_with_newline": false
        },
        "prettyhtml": {
            "printWidth": 100,
            "singleQuote": true,
            "wrapAttributes": false,
            "sortAttributes": false
        }
    },
    "[css]": {
        "editor.defaultFormatter": "aeschli.vscode-css-formatter"
    },
    "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "[jsonc]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "vsicons.dontShowNewVersionMessage": true,
    "[vue]": {
        "editor.defaultFormatter": "octref.vetur"
    },
    "volar.codeLens.pugTools": false,
    "workbench.sideBar.location": "left",
    "workbench.colorTheme": "Monokai",
    "window.zoomLevel": -1
}
```


html5--用户代码片段
```json
{
    "vh": {
        "prefix": "html5", // 触发的关键字 输入html5按下tab键
        "body": [
            "<!DOCTYPE html>",
            "<html lang=\"zh-CN\">",
            "",
            "<head>",
            "    <meta charset=\"UTF-8\">",
            "    <meta name=\"viewport\" content=\"width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0\">",
            "    <meta http-equiv=\"X-UA-Compatible\" content=\"ie=edge\">",
            "    <title>Document</title>",
            "</head>",
            "",
            "<body>",
            "",
            "</body>",
            "",
            "</html>",
        ],
        "description": "vh components"
    }
}
```
