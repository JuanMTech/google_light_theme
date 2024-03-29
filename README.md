# NEW VERSION OF THIS THEME IS AVAILABLE. IT SUPPORTS BOTH LIGHT AND DARK MODE. YOU CAN CHECK THE THEME [HERE](https://github.com/JuanMTech/google-theme).
<br />
<br />

# Google Light Theme

A Home Assistant theme inspired on Google app Light mode.
<br />
<br />

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

[![Subscribe to YouTube channel][youtube-sub-shield]][youtubesubscribe]

[![Become a Patron][become-a-patron-shield]][becomeapatron]

[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee]
<br />
<br />

### Screenshots

![Google Light Modem 1](https://raw.githubusercontent.com/JuanMTech/google_light_theme/master/images/Google%20Light%20Mode%201.jpg)<br />
<br />
![Google Light Modem 2](https://raw.githubusercontent.com/JuanMTech/google_light_theme/master/images/Google%20Light%20Mode%202.jpg)<br />
<br />
![Google Light Modem 3](https://raw.githubusercontent.com/JuanMTech/google_light_theme/master/images/Google%20Light%20Mode%203.jpg)<br />
<br />

### Preparation
1. Make sure that under the **configuration.yaml** file you have the following:

```
frontend:
  themes: !include_dir_merge_named themes
```

2. Under the Home Assistant **Config** folder, create a new folder named **themes**
3. **Restart** Home assistant to apply the changes. 

### HACS installation
1. Go into the Community Store (HACS)
2. Search for Google Light Theme
3. Open the theme
4. Press Install
5. Restart Home Assistant

### Manual installation
1. In the Home assistant **themes** folder, create a file named `google_light_theme.yaml`
2. In this GitHub repo, go into the **themes** folder, open the `google_light_theme.yaml` file and copy the content
3. Paste the content in the `google_light_theme.yaml` file created under your Home Assistant themes folder

### Enable theme
1. Open your Home Assistant **Profile**
2. Under, **Themes**, select the new Google Light Theme

<br />
<br />
<br />

# Other available themes
- [**iOS Theme**](https://github.com/JuanMTech/ios-theme) - Based on the system-wide light and dark mode UI
- [**Google Theme**](https://github.com/JuanMTech/google-theme) - Based on the Android light and dark interface
- [**AMOLED Blue**](https://github.com/JuanMTech/amoled_blue) - A true black Home Assistant theme for devices with AMOLED displays


[buymeacoffee-shield]: https://i.imgur.com/Hzn2rM8.png
[buymeacoffee]: https://www.buymeacoffee.com/JuanMTech
[become-a-patron-shield]: https://i.imgur.com/U9BjCfc.png
[becomeapatron]: https://www.patreon.com/JuanMTech
[youtube-sub-shield]: https://i.imgur.com/6TAqHgi.png
[youtubesubscribe]: https://www.youtube.com/c/JuanMTech?sub_confirmation=1
