# vscodeTokenColorCustomized

## I've had terrible experiences with the token color of every free VScode extension
## So i have decided to alter the token colors myself with the help of my graphic designer 

### You can copy and paste this format to your vscode > settings.json file
### Hoping you guys enjoy the colors 

  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "GitHub Dark Default",

  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": ["string.quoted.double", "string.quoted.single"],
        "settings": { "foreground": "#7FFFA2" } //done #63C67D
      },
      {
        "scope": ["support.type.property-name.json"],
        "settings": { "foreground": "#a0f7ed" } //done
      },
      {
        "scope": [
          "variable.other.declaration.go",
          "source.go",
          "variable.other.assignment.go",
          "variable.other.arg.go",
          "variable.other.php",
          "source.python",
          "variable.other.property"
        ],
        "settings": {
          "foreground": "#0094cf"
        }
      },
      {
        "scope": [
          "entity.name.variable.local.go",
          "variable.parameter.function.python",
          "variable.language.python",
          "variable.other.local.java",
          "entity.name.variable.local.java",
          "variable.other.readwrite.js",
          "variable.other.readwrite.ts"
        ],
        "settings": { "foreground": "#ffffff" }
      },
      {
        "scope": ["variable", "meta.variable", "variable.other.readwrite"],
        "settings": { "foreground": "#95fff4" } 
      },
      {
        "scope": ["entity.name.function", "support.function"],
        "settings": { "foreground": "#fdff87" } 
      },
      {
        "scope": ["entity.name.type", "support.class"],
        "settings": { "foreground": "#6ad5ff" } 
      },
      {
        "scope": ["keyword"],
        "settings": {
          "foreground": "#e7e59e",
          "fontStyle": "bold"
        }
      },
      {
        "scope": ["keyword.control", "storage.type"],
        "settings": { "foreground": "#00C5C9" } 
      },
      {
        "scope": ["comment.line.double-slash", "comment.block"],
        "settings": { "foreground": "#6d6d6d", "fontStyle": "italic" } 
      },
      {
        "scope": ["constant.numeric"],
        "settings": { "foreground": "#98C568" } 
      },
      {
        "scope": ["constant.language.boolean"],
        "settings": { "foreground": "#ff0000" } //i couldn't find this relative value
      },
      {
        "scope": ["keyword.operator", "keyword.operator.assignment"],
        "settings": { "foreground": "#c8c8c8" } 
      },
      {
        "scope": ["punctuation.separator", "punctuation.terminator"],
        "settings": { "foreground": "#d6d6d6" } 
      },
      {
        "scope": ["keyword.control.flow"],
        "settings": { "foreground": "#62d0d2" } 
      },
      {
        "scope": ["support.type", "support.constant"], 
        "settings": { "foreground": "#99FF87" }
        // 9bdcff
      },
      {
        "scope": [
          "variable.parameter",
          "meta.function.parameters",
          "variable.parameter.function.language.python",
          "meta.function.parameters.python",
          "meta.function.python",
          "meta.function-call.arguments.python"
        ],
        "settings": { "foreground": "#319f9f" } 
      },
      {
        "scope": ["support.module", "entity.name.namespace"],
        "settings": { "foreground": "#94C4D5" } 
      },
      {
        "scope": [
          "meta.annotation",
          "storage.type.annotation",
          "meta.decorator"
        ],
        "settings": { "foreground": "#6d6d6d" } 
      },
      {
        "scope": ["meta.generic", "entity.name.type.parameters"],
        "settings": { "foreground": "#ff6464" } 
      },
      {
        "scope": [
          "keyword.control.import",
          "meta.import",
          "keyword.other.package"
        ],
        "settings": { "foreground": "#00fff2" } 
      },
      {
        "scope": ["variable.language.this", "variable.language.self"],
        "settings": { "foreground": "#ff5c5c" } 
      },
      {
        "scope": ["keyword.control.flow.await", "keyword.control.yield"],
        "settings": { "foreground": "#000000" } //couldn't find this
      },
      {
        "scope": ["invalid.illegal", "invalid.deprecated"],
        "settings": { "foreground": "#fffefe" } 
      },
      {
        "scope": "meta.object-literal.key.js",
        "settings": {
          "foreground": "#FFD700" 
        }
      }
    ]
  },

