# Vintage Theme

Vintage theme original made by Anup Surendran ( https://github.com) updated and HACS adapted.

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

[![GH-release](https://img.shields.io/github/v/release/Banditen01/vintage_theme.svg?style=flat-square)](https://github.com/Banditen01/vintage_theme/releases)
[![GH-downloads](https://img.shields.io/github/downloads/Banditen01/vintage_theme/total?style=flat-square)](https://github.com/Banditen01/vintage_theme/releases)
[![GH-last-commit](https://img.shields.io/github/last-commit/Banditen01/vintage_theme.svg?style=flat-square)](https://github.com/Banditen01/vintage_theme/commits/master)
[![GH-code-size](https://img.shields.io/github/languages/code-size/Banditen01/vintage_theme.svg?color=red&style=flat-square)](https://github.com/Banditen01/vintage_theme)

### Screenshots


**1. Desktop**
<p align="center">
  <img src="https://github.com/Banditen01/vintage_theme/blob/master/images/vintage_1.png">
</p>
<p align="center">
  <img src="https://github.com/Banditen01/vintage_theme/blob/master/images/vintage_2.png">
</p>
</p>
<p align="center">
  <img src="https://github.com/Banditen01/vintage_theme/blob/master/images/vintage_3.png">
</p>

### Preparation
1. Make sure that under the **configuration.yaml** file you have the following:

<pre>
frontend:
  themes: !include_dir_merge_named themes
</pre>

2. Under the Home Assistant **Config** folder, create a new folder named **themes**
3. **Restart** Home assistant to apply the changes.

### HACS installation
1. Go into the **Community Store** (HACS)
2. Search for **Vintage** under themes
3. Open the theme
4. Press Install
5. Restart Home Assistant

### Manual installation
1. In the Home assistant **themes** folder, create a two files named `vintage.yaml` and `vintage_classic_modern.css`
2. In this GitHub repo, go into the **themes** folder, open the `vintage.yaml` and `vintage_classic_modern.css` and copy the content
3. Paste the content in the `vintage.yaml` file and `vintage_classic_modern.css` file created under your Home Assistant themes folder

### Enable theme
1. Open your Home Assistant **Profile**
2. Under, **Themes**, select the new Vintage Theme
