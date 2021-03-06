[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

# GitHub Light Theme

A Home Assistant theme inspired on GitHub.

### Screenshots
![GitHub Light](https://github.com/einschmidt/github_light_theme/blob/main/images/theme_light.png)

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
2. Search for GitHub Light Theme
3. Open the theme
4. Press Install
5. Restart Home Assistant

### Manual installation
1. In the Home assistant **themes** folder, create a file named `github_light_theme.yaml`
2. In this GitHub repo, go into the **themes** folder, open the `github_light_theme.yaml` file and copy the content
3. Paste the content in the `github_light_theme.yaml` file created under your Home Assistant themes folder

### Enable theme
1. Open your Home Assistant **Profile**
2. Under, **Themes**, select the new GitHub Light Theme
