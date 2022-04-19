# Botify segments
VS code extension for semantic highlighting language for Botify segments.

## Installation
1. Download this repo
2. Place it in your `~/.vscode/extensions` folder. Bash script: `cp -R botify-lang ~/.vscode/extensions/botify-lang`
3. Copy the code snippet of the next section into your `settings.json` vscode file
4. Restart VS Code
5. You can now use the `botify` language in VS Code

### Semantic highlighting (Code snippet)
Important: Modify this value `[Default Dark+]` by the name of the theme you're using.

```json
"editor.tokenColorCustomizations": {
        "[Default Dark+]": {
            "textMateRules": [
                {
                    "scope": "keyword.route.botify",
                    "settings": {
                        "foreground": "#66D9EF"
                    }
                },
                {
                    "scope": "keyword.route.values.botify",
                    "settings": {
                        "foreground": "#A6E22E"
                    }
                },
                {
                    "scope": "keyword.host.botify",
                    "settings": {
                        "foreground": "#F92672"
                    }
                },
                {
                    "scope": "keyword.path.botify",
                    "settings": {
                        "foreground": "#F92672"
                    }
                },
                {
                    "scope": "keyword.path.values.botify",
                    "settings": {
                        "foreground": "#E6DB74"
                    }
                },
                {
                    "scope": "keyword.host.values.botify",
                    "settings": {
                        "foreground": "#E6DB74"
                    }
                },
                {
                    "scope": "source.botify",
                    "settings": {
                        "foreground": "#E6DB74"
                    }
                },
                {
                    "scope": "keyword.comment.botify",
                    "settings": {
                        "foreground": "#75715E"
                    }
                }
            ]
        },
    }
```