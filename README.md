Monokai Pro for Sublime Text
============================

Beautiful functionality for professional developers
---------------------------------------------------

**Monokai Pro** is a color scheme, user interface theme and icon pack for code editors. It has been designed with **beautiful functionality** in mind. Carefully selected shades of color are the foundation of an uncompromising, non-distractive user interface.

Monokai Pro comes in a **dark theme** and a **light theme**. Regardless of your coding environment, the single goal of Monokai Pro is to let you focus on your code.

### ☞ How to install free evaluation for Sublime Text:

```
1. Package Control ‣ Install Package ‣ Theme - Monokai Pro
2. Command Palette ‣ Monokai Pro: select theme
```

Find out more here: [monokai.pro](https://monokai.pro)

![Monokai Pro](https://raw.githubusercontent.com/monokai-pro/sublime-text/master/img/monokai-pro.png)

Pixel-perfect file icons
------------------------

The icons of Monokai Pro have all been created from scratch to ensure they are easily recognizable on small sizes in the side bar. They are designed to help you quickly find the right files in your project.

![Monokai Pro Icons](https://raw.githubusercontent.com/monokai-pro/sublime-text/master/img/monokai-pro-icons.png)

Color filters
-------------

Monokai Pro offers a set of color filters for the dark and light theme. Whatever your mood, there's a color setting that's right for you.

History of Monokai
------------------

Monokai Pro was created by the same author of the iconic Monokai color palette, first introduced back in 2006. While the classic Monokai remains popular and has inspired many variations over the years, Monokai Pro is its official modern successor, offering a more refined and balanced color scheme. Today, it's the go-to choice for professional developers around the world.

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