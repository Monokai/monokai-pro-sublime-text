Monokai Pro for Sublime Text
============================

Beautiful functionality for professional developers
---------------------------------------------------

Monokai Pro is a color scheme, customized user interface theme and complete icon set for Sublime Text. It has been designed by the author of the original Monokai colors. Carefully selected shades of colors are the foundation of an uncompromising, non-distractive user interface. The single goal of Monokai Pro is to let you focus on your code.

### ☞ How to install free evaluation for Sublime Text:

```
1. Package Control ‣ Install Package ‣ Theme - Monokai Pro
2. Command Palette ‣ Monokai Pro: select theme
```

Find out more here: [monokai.pro](https://monokai.pro)

![Monokai Pro](https://raw.githubusercontent.com/Monokai/monokai-pro-sublime-text/master/img/monokai-pro.png)

Pixel-perfect file icons
------------------------

The icons of Monokai Pro have all been created from scratch to ensure they are easily recognizable on small sizes in the side bar. They are designed to help you quickly find the right files in your project.

![Monokai Pro Icons](https://raw.githubusercontent.com/Monokai/monokai-pro-sublime-text/master/img/monokai-pro-icons.png)

## Supported plugins

### Sublime Linter

Place this in your Sublime Linter User preferences:

```
{
	"gutter_theme": "Packages/Theme - Monokai Pro/Monokai Pro.gutter-theme",
	"styles": [
		{
			"mark_style": "none",
			"priority": 1,
			"scope": "region.orangish",
			"icon": "warning",
			"types": [
				"warning"
			]
		},
		{
			"mark_style": "none",
			"priority": 1,
			"scope": "region.redish",
			"icon": "error",
			"types": [
				"error"
			]
		}
	]
}
```

It will automatically match the gutter icon colors to the selected color filter of Monokai Pro.