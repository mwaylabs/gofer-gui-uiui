# Chrome Extension
```
git clone https://github.com/mwaylabs/gofer-gui-uiui.git
cd gofer-gui-uiui
```

- Open Chrome
- Menu -> Tools -> Extensions
- Activate `Developer mode`
- `Load unpacked extension...`
- Select `gofer-gui-uiui` directory

** Add a Domain **
- Open gofer-gui-uiui/manifest.json
- Add path to mcap into `content_scripts.matches`

```

"content_scripts": [
    {
      "matches": ["http://NEWDOMAIN.DE"]
    }
  ]

```