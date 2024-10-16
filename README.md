<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/KDE/labplot">LabPlot</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/Sebagabones/labplot/stargazers"><img src="https://img.shields.io/github/stars/Sebagabones/labplot?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/Sebagabones/labplot/issues"><img src="https://img.shields.io/github/issues/Sebagabones/labplot?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/Sebagabones/labplot/contributors"><img src="https://img.shields.io/github/contributors/Sebagabones/labplot?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/mocha.webp"/>
</details>

## Usage

### Colormap Theme
1. Download the `Catppuccin (Categorical).json` file from `\themes\colormaps`
2. Add this file to `/usr/share/labplot2/colormaps/` 
3. Update the end of `ColormapCollections.json` with: 
``` json
,{
	"name" : "Catppuccin (Categorical)",
	"description": "These color maps are not scientific in any way and are only meant for categorical highlighting to match the Catppuccin worksheet and application themes.",
	"url" : "https://github.com/catppuccin/labplot"
}
```
4. To use this theme, select your data from a spreadsheet, and right-click, and then select the theme from the "Conditional Formatting>Heatmap" option.

Note: Currently, these changes may be overwritten when LabPlot updates, however we are hoping to be able to merge these changes into LabPlot so that Catppuccin is installed by default!
### Worksheet Theme
1. Download the flavor of your choice from `\themes\worksheet_themes`.
2. Add this file to `/usr/share/labplot2/themes`
3. Download the screenshot preview from `\assets\screenshots_for_preview` 
3. Add this file to `/usr/share/labplot2/themes/screenshots`
4. Once you have created a graph in LabPlot, right-click outside of the preview, and apply the theme through the theme option.
Note: Currently, these changes may be overwritten when LabPlot updates, however we are hoping to be able to merge these changes into LabPlot so that Catppuccin is installed by default!

## 💝 Thanks to

- [Sebagabones](https://github.com/Sebagabones)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
