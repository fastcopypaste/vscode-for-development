# VScode for development

### For Javascript
## Search in all node_modules

Press `Ctrl + Shift + P` then type: `Open settings (JSON)`, then append this code:

```
"search.exclude": {
  "**/node_modules": false
},
"search.useIgnoreFiles": false
```
