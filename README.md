<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://tools.suckless.org/sent/">sent</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/xzi/sent/stargazers"><img src="https://img.shields.io/github/stars/xzi/sent?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/xzi/sent/issues"><img src="https://img.shields.io/github/issues/xzi/sent?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/xzi/sent/contributors"><img src="https://img.shields.io/github/contributors/xzi/sent?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="assets/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="assets/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="assets/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="assets/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="assets/mocha.webp"/>
</details>

## Usage

1. Download the patch file for the colorscheme you want from the patches folder
2. Copy the patch to your sent source folder
3. Run `git apply colorscheme.patch` (replace colorscheme with the colorscheme's name)
4. Delete config.h
5. Rebuild

<!-- this section is optional -->
## 🙋 FAQ

-	Q: **_"I'm getting an error about the patch failing."_**\
	A: Open `config.def.h` and make sure the following is set.
	```
	static const char *colors[] = {
          "#4c4f69", /* foreground color */
          "#eff1f5", /* background color */
 	};
 	```

## 💝 Thanks to

- [xzi](https://github.com/xzi)

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
