# Vintage Theme
Vintage theme original made by Anup Surendran (https://github.com/surendrananup/home-assistant/tree/master/themes) updated and HACS adapted.

[![hacs_badge](https://shields.io)](https://github.com) 
[![GitHub release (latest by date)](https://shields.io)](https://github.com) 
[![GitHub All Releases](https://shields.io)](https://github.com)


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
