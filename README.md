# CatWeb JSON Generator

This is a simple, browser-based JSON generator for creating **CatWeb UI layouts** in Roblox.

> 🔧 Built by [YourLocal-Dude](https://github.com/YourLocal-Dude)

---

## 🌐 Live Version

Once deployed to GitHub Pages, your live generator will be accessible at:

https://yourlocal-dude.github.io/Catweb-Json-Generator/

---

## 💡 Features

- ✅ Generate CatWeb-compatible UI JSON
- 🧱 Supports all standard elements:
  - `TextLabel`, `TextButton`, `TextBox`, `ImageLabel`, `Frame`
- 🧠 Supports the special `script` element with actions like `Redirect`, `SetProp`, `Wait`, etc.
- 🎨 Fully customizable:
  - `position`, `size`, `font`, `colors`, `anchor`, `alignment`, `text`, `href`, and more
- 📋 One-click JSON copy
- 🌈 Live preview of structured JSON

---

## 🚀 How to Use

1. Open the site in your browser (`index.html`) or visit the live GitHub Pages link.
2. Use the form to add and configure CatWeb UI elements.
3. Click "➕ Add Element" to include them in your layout.
4. Copy the generated JSON using "📋 Copy JSON".
5. Paste the result into **CatWeb's Import JSON** system in Roblox.

---

## 📦 Example Output

```json
{
  "background": "#ffffff",
  "title": "My CatWeb Site",
  "webcontent": [
    {
      "globalid": "A1",
      "class": "TextLabel",
      "text": "Welcome!",
      "position": "{0.1,0},{0.1,0}",
      "size": "{0.8,0},{0.1,0}",
      "font": "BuilderSansMedium",
      "font_size": "medium",
      "font_color": "#000000"
    },
    {
      "class": "script",
      "content": [
        {
          "text": ["When website loaded..."],
          "actions": [
            {
              "text": ["Redirect to(domain)", { "value": "home.rbx", "t": "string", "href": "true" }]
            }
          ]
        }
      ]
    }
  ]
}
```
