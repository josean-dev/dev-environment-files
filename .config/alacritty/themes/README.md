# Alacritty Theme

Collection of colorschemes for easy configuration of the [Alacritty terminal
emulator].

[Alacritty terminal emulator]: https://github.com/alacritty/alacritty

## Installation

### Imports

Clone the repository, or download the theme of your choice:

```sh
# We use Alacritty's default Linux config directory as our storage location here.
mkdir -p ~/.config/alacritty/themes
git clone https://github.com/alacritty/alacritty-theme ~/.config/alacritty/themes
```

Add an import to your `alacritty.toml` (Replace `{theme}` with your desired
colorscheme):

```toml
import = [
    "~/.config/alacritty/themes/themes/{theme}.toml"
]
```

### Manual

To manually include a colorscheme in an existing `alacritty.toml`, you just need
to copy the entire content of the theme into the root level of your
configuration file.

## Color Schemes

|                                                                       NAME                                                                        |                           COLORS                           |
|:-------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------:|
|                                   **_afterglow_**<br>[source](https://github.com/YabataDesign/afterglow-theme)                                    |        ![base16_default_dark](images/afterglow.png)        |
|                                   **_alabaster_**<br>[source](https://github.com/tonsky/vscode-theme-alabaster)                                   |             ![alabaster](images/alabaster.png)             |
|                                   **_alabaster_dark_**<br>[source](https://github.com/gargakshit/vscode-theme-alabaster-dark)                     |        ![alabaster_dark](images/alabaster_dark.png)        |
|                **_alacritty_0_12_**<br>[source](https://github.com/alacritty/alacritty/blob/v0.12.3/alacritty/src/config/color.rs)                |        ![alacritty_0_12](images/alacritty_0_12.png)        |
|                                      **_argonaut_**<br>[source](https://github.com/pwaleczek/Argonaut-theme)                                      |        ![base16_default_dark](images/argonaut.png)         |
|             **_ashes_dark_**<br>[source](https://marketplace.visualstudio.com/items?itemName=AndrsDC.base16-themes)                               |        ![base16_ashes_dark](images/ashes_dark.png)         |
|             **_ashes_light_**<br>[source](https://marketplace.visualstudio.com/items?itemName=AndrsDC.base16-themes)                              |        ![base16_ashes_light](images/ashes_light.png)       |
|                  **_atom_one_light_**<br>[source](https://github.com/dexpota/kitty-themes/blob/master/themes/AtomOneLight.conf)                   |        ![atom_one_light](images/atom_one_light.png)        |
|                  **_aura_**<br>[source](https://github.com/daltonmenezes/aura-theme)                   |        ![aura](images/aura.png)        |
|                                        **_ayu_dark_**<br>[source](https://github.com/ayu-theme/ayu-colors)                                        |              ![ayu_dark](images/ayu_dark.png)              |
|                                       **_ayu_light_**<br>[source](https://github.com/ayu-theme/ayu-colors)                                        |             ![ayu_light](images/ayu_light.png)             |
|                                   **_baitong_**<br>[source](https://github.com/cypj/baitong-theme)                                                |         ![baitong](images/baitong.png)                     |
|                                   **_base16_default_dark_**<br>[source](https://github.com/chriskempson/base16)                                   |   ![base16_default_dark](images/base16_default_dark.png)   |
|                                         **_blood_moon_**<br>[source](https://github.com/dguo/blood-moon)                                          |            ![blood_moon](images/blood_moon.png)            |
|                                                                   **_bluish_**                                                                    |                ![bluish](images/bluish.png)                |
|                                              **_breeze_**<br>[source](https://github.com/KDE/breeze)                                              |                ![breeze](images/breeze.png)                |
|              **_campbell_**<br>[source](https://blogs.msdn.microsoft.com/commandline/2017/08/02/updating-the-windows-console-colors)              |              ![campbell](images/campbell.png)              |
|              **_carbonfox_**<br>[source](https://github.com/edeneast/nightfox.nvim/raw/main/extra/carbonfox/nightfox_alacritty.yml)               |             ![carbonfox](images/carbonfox.png)             |
|                                    **_catppuccin_frappe_**<br>[source](https://github.com/catppuccin/alacritty)                                   |     ![catppuccin_frappe](images/catppuccin_frappe.png)     |
|                                 **_catppuccin_latte_**<br>[source](https://github.com/catppuccin/alacritty)                                       |      ![catppuccin_latte](images/catppuccin_latte.png)      |
|                                  **_catppuccin_macchiato_**<br>[source](https://github.com/catppuccin/alacritty)                                  |  ![catppuccin_macchiato](images/catppuccin_macchiato.png)  |
|                                    **_catppuccin_mocha_**<br>[source](https://github.com/catppuccin/alacritty)                                    |      ![catppuccin_mocha](images/catppuccin_mocha.png)      |
|                               **_challenger_deep_**<br>[source](https://github.com/challenger-deep-theme/alacritty)                               |       ![challenger_deep](images/challenger_deep.png)       |
|                                                                  **_chicago95_**                                                                  |               ![chicago95](images/chicago95.png)           |
|                                              **_citylights_**<br>[source](https://citylights.xyz/)                                               |           ![citylights](images/citylights.png)            |
|                                 **_Cobalt2_**<br>[source](https://github.com/wesbos/cobalt2/tree/master/Cobalt2)                                  |               ![Cobalt2](images/Cobalt2.png)               |
|                                 **_cyber_punk_neon_**<br>[source](https://github.com/Roboron3042/Cyberpunk-Neon)                                  |       ![cyber_punk_neon](images/cyber_punk_neon.png)       |
|         **_dark_pastels_**<br>[source](https://invent.kde.org/utilities/konsole/-/blob/master/data/color-schemes/DarkPastels.colorscheme)         |          ![dark_pastels](images/dark_pastels.png)          |
|                                                                  **_deep_space_**                                                                 |             ![depp_space](images/deep_space.png)           |
|                                     **_doom_one_**<br>[source](https://github.com/hlissner/emacs-doom-themes)                                     |              ![doom_one](images/doom_one.png)              |
|                                                **_dracula_**<br>[source](https://draculatheme.com)                                                |               ![dracula](images/dracula.png)               |
|                                                **_dracula_plus_**<br>[source](https://draculatheme.com)                                           |               ![dracula_plus](images/dracula_plus.png)     |
|                                     **_everforest_dark_**<br>[source](https://github.com/sainnhe/everforest)                                      |       ![everforest_dark](images/everforest_dark.png)       |
|                                     **_everforest_light_**<br>[source](https://github.com/sainnhe/everforest)                                     |      ![everforest_light](images/everforest_light.png)      |
|                                           **_falcon_**<br>[source](https://github.com/fenetikm/falcon)                                            |                ![falcon](images/falcon.png)                |
|                          **_flat_remix_**<br>[source](https://github.com/Mayccoll/Gogh/blob/master/themes/flat-remix.sh)                          |            ![flat_remix](images/flat_remix.png)            |
| **_flexoki_**<br>[source](https://github.com/kepano/flexoki/tree/main/alacritty)                                                                  | ![flexoki](images/flexoki.png)                             |
| **_github_dark_**<br>[source](https://github.com/projekt0n/github-theme-contrib/blob/main/themes/alacritty/github_dark.yml)                          | ![github_dark](images/github_dark.png)                         |
| **_github_dark_colorblind_**<br>[source](https://github.com/projekt0n/github-theme-contrib/blob/main/themes/alacritty/github_dark_colorblind.yml)  | ![github_dark_colorblind](images/github_dark_colorblind.png)   |
| **_github_dark_dimmed_**<br>[source](https://github.com/projekt0n/github-theme-contrib/blob/main/themes/alacritty/github_dark_dimmed.yml)          | ![github_dark_dimmed](images/github_dark_dimmed.png)           |
| **_github_dark_high_contrast_**<br>[source](https://github.com/projekt0n/github-theme-contrib/blob/main/themes/alacritty/github_dark_high_contrast.yml)| ![github_dark_high_contrast](images/github_dark_high_contrast.png)|
| **_github_dark_tritanopia_**<br>[source](https://github.com/projekt0n/github-theme-contrib/blob/main/themes/alacritty/github_dark_tritanopia.yml)  | ![github_dark_tritanopia](images/github_dark_tritanopia.png)   |
| **_github_light_**<br>[source](https://github.com/projekt0n/github-theme-contrib/blob/main/themes/alacritty/github_light.yml)                      | ![github_light](images/github_light.png)                       |
| **_github_light_colorblind_**<br>[source](https://github.com/projekt0n/github-theme-contrib/blob/main/themes/alacritty/github_light_colorblind.yml)| ![github_light_colorblind](images/github_light_colorblind.png) |
| **_github_light_high_contrast_**<br>[source](https://github.com/projekt0n/github-theme-contrib/blob/main/themes/alacritty/github_light_high_contrast.yml)| ![github_light_high_contrast](images/github_light_high_contrast.png)|
| **_github_light_tritanopia_**<br>[source](https://github.com/projekt0n/github-theme-contrib/blob/main/themes/alacritty/github_light_tritanopia.yml)| ![github_light_tritanopia](images/github_light_tritanopia.png) |
|                                                                   **_google_**                                                                    |                ![falcon](images/google.png)                |
|                                                                   **_gotham_**                                                                    |                ![falcon](images/gotham.png)                |
|                                  **_gnome_terminal_**<br>[source](https://gitlab.gnome.org/GNOME/gnome-terminal)                                  |        ![gnome_terminal](images/gnome_terminal.png)        |
|                                        **_gruvbox_dark_**<br>[source](https://github.com/morhetz/gruvbox)                                         |          ![gruvbox_dark](images/gruvbox_dark.png)          |
|                                        **_gruvbox_light_**<br>[source](https://github.com/morhetz/gruvbox)                                        |         ![gruvbox_light](images/gruvbox_light.png)         |
|                                  **_gruvbox_material_hard_dark_**<br>[source](https://github.com/sainnhe/gruvbox-material)                        | ![gruvbox_material_hard_dark](images/gruvbox_material_hard_dark.png)   |
|                                  **_gruvbox_material_hard_light_**<br>[source](https://github.com/sainnhe/gruvbox-material)                       | ![gruvbox_material_hard_light](images/gruvbox_material_hard_light.png) |
|                                  **_gruvbox_material_medium_dark_**<br>[source](https://github.com/sainnhe/gruvbox-material)                      | ![gruvbox_material_medium_dark](images/gruvbox_material_medium_dark.png) |
|                                  **_gruvbox_material_medium_light_**<br>[source](https://github.com/sainnhe/gruvbox-material)                      | ![gruvbox_material_medium_light](images/gruvbox_material_medium_light.png) |
|                                  **_hardhacker_**<br>[source](https://github.com/hardhackerlabs/theme-alacritty)                                  |      ![hardhacker](images/hardhacker.png)                  |
|                                                                **_high_contrast_**                                                                |         ![gruvbox_light](images/high_contrast.png)         |
|                                 **_horizon-dark_**<br>[source](https://github.com/jolaleye/horizon-theme-vscode)                                  |          ![horizon-dark](images/horizon-dark.png)          |
|                                                     **_hyper_**<br>[source](https://hyper.is)                                                     |                 ![hyper](images/hyper.png)                 |
|                                 **_inferno_**<br>[source](https://github.com/hafiz-muhammad/inferno-alacritty-theme)                              |                 ![inferno](images/inferno.png)             |
|                                 **_iris_**<br>[source](https://github.com/DioptricDesign/Iris)                                                    |                 ![iris](images/iris.png)                   |
|                                                                    **_iterm_**                                                                    |                 ![iterm](images/iterm.png)                 |
|                                 **_kanagawa_dragon_**<br>[source](https://github.com/rebelot/kanagawa.nvim)                                       |          ![kanagawa_dragon](images/kanagawa_dragon.png)    |
|                                  **_kanagawa_wave_**<br>[source](https://github.com/rebelot/kanagawa.nvim)                                        |          ![kanagawa_wave](images/kanagawa_wave.png)        |
|                                                                **_konsole_linux_**                                                                |             ![iterm](images/konsole_linux.png)             |
|                                                                **_low_contrast_**                                                                 |             ![iterm](images/low_contrast.png)              |
|                  **_Mariana_**<br>[source](https://github.com/mbadolato/iTerm2-Color-Schemes/blob/master/alacritty/Mariana.yml)                   |                ![iterm](images/mariana.png)                |
|                  **_marine_dark_**<br>[source](https://github.com/ProDeSquare/alacritty-colorschemes/blob/master/themes/marine_dark.yaml)         |                ![marine_dark](images/marine_dark.png)         |
|                                  **_material_theme_**<br>[source](https://github.com/equinusocio/material-theme)                                  |        ![material_theme](images/material_theme.png)        |
|                                                             **_material_theme_mod_**                                                              |    ![material_theme_mod](images/material_theme_mod.png)    |
|                  **_meliora_**<br>[source](https://github.com/ramojus/mellifluous.nvim)                                                           |                ![meliora](images/meliora.png)              |
|                  **_midnight-haze_**<br>[source](https://github.com/hafiz-muhammad/midnight-haze-alacritty-theme)                                 |    ![midnight-haze](images/midnight-haze.png)              |
|    **_monokai_charcoal_**<br>[source](https://github.com/dodeca12/Monokai-Charcoal-Theme-for-Alacritty/blob/main/monokai_charcoal_white.yaml)     |      ![monokai_charcoal](images/monokai-charcoal.png)      |
|                      **_monokai_pro_**<br>[source](https://gist.github.com/AlphaTechnolog/d1d5f6557f77f71519cb5713268da7dd)                       |           ![monokai_pro](images/monokai_pro.png)           |
|                             **_moonlight_ii_vscode_**<br>[source](https://github.com/atomiks/moonlight-vscode-theme)                              |   ![moonlight_ii_vscode](images/moonlight_ii_vscode.png)   |
|                                            **_msx_**<br>[source](https://paulwratt.github.io/programmers-palettes/HW-MSX/HW-MSX-palettes.html)    |              ![msx](images/msx.png)              |
|                                       **_nightfly_**<br>[source](https://github.com/bluz71/vim-nightfly-colors)                                   |              ![nightfly](images/nightfly.png)              |
|                                       **_nightfox_**<br>[source](https://github.com/EdenEast/nightfox.nvim)                                       |              ![nightfox](images/nightfox.png)              |
|                                       **_night_owl_**<br>[source](https://vscodethemes.com/e/sdras.night-owl/night-owl)                           |             ![night_owl](images/night_owl.png)             |
|                                                             **_night_owlish_light_**                                                              |    ![night_owlish_light](images/night_owlish_light.png)    |
|                                       **_noctis-lux_**<br>[source](https://github.com/liviuschera/noctis)                                         |              ![noctis-lux](images/noctis-lux.png)              |
|                                          **_nord_**<br>[source](https://github.com/arcticicestudio/nord)                                          |                  ![nord](images/nord.png)                  |
|                                          **_nordic_**<br>[source](https://github.com/AlexvZyl/nordic.nvim)                                          |                  ![nordic](images/nordic.png)                  |
|                                          **_nord_light_**<br>[source](https://github.com/nordtheme/alacritty/issues/28#issuecomment-1422225211)                                          |                  ![nord](images/nord_light.png)                  |
|                             **_oceanic_next_**<br>[source](https://github.com/voronianski/oceanic-next-color-scheme)                              |          ![oceanic_next](images/oceanic_next.png)          |
|                                  **_omni_**<br>[source](https://github.com/getomni/alacritty/blob/main/omni.yml)                                  |                  ![omni](images/omni.png)                  |
|                                                                  **_one_dark_**                                                                   |              ![one_dark](images/one_dark.png)              |
|                                  **_palenight_**<br>[source](https://github.com/JonathanSpeek/palenight-iterm2)                                   |             ![palenight](images/palenight.png)             |
|              **_papercolor_dark_**<br>[source](https://github.com/NLKNguyen/papercolor-theme/blob/master/colors/PaperColor.vim#L126)              |       ![papercolor_dark](images/papercolor_dark.png)       |
|              **_papercolor_light_**<br>[source](https://github.com/NLKNguyen/papercolor-theme/blob/master/colors/PaperColor.vim#L36)              |      ![papercolor_light](images/papercolor_light.png)      |
|                  **_papertheme_**<br>[source](https://github.com/s6muel/paper-theme/blob/main/themes/alacritty/paper-theme.yml)                   |         ![papercolor_light](images/papertheme.png)         |
|**_pastel_dark_**<br>[source](https://github.com/gnachman/iTerm2/blob/01c280152acebfe123f56e0215a3c178297a0edc/plists/ColorPresets.plist#L3715-L3924)|          ![pastel_dark](images/pastel_dark.png)           |
|                                   **_pencil_dark_**<br>[source](https://github.com/mattly/iterm-colors-pencil)                                    |           ![pencil_dark](images/pencil_dark.png)           |
|                                   **_pencil_light_**<br>[source](https://github.com/mattly/iterm-colors-pencil)                                   |          ![pencil_light](images/pencil_light.png)          |
|                                                                   **_rainbow_**                                                                   |               ![rainbow](images/rainbow.png)               |
|                                  **_remedy_dark_**<br>[source](https://github.com/robertrossmann/vscode-remedy)                                   |           ![remedy_dark](images/remedy_dark.png)           |
|                                        **_rose-pine_**<br>[source](https://github.com/rose-pine/alacritty)                                        |             ![rose-pine](images/rose-pine.png)             |
|                                        **_rose-pine-dawn_**<br>[source](https://github.com/rose-pine/alacritty)                                        |             ![rose-pine-dawn](images/rose-pine-dawn.png)             |
|                                        **_rose-pine-moon_**<br>[source](https://github.com/rose-pine/alacritty)                                        |             ![rose-pine-moon](images/rose-pine-moon.png)             |
|                                      **_snazzy_**<br>[source](https://github.com/sindresorhus/hyper-snazzy)                                       |                ![snazzy](images/snazzy.png)                |
|         **seashells**<br>[source](https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/SeaShells.itermcolors)          |             ![seashells](images/seashells.png)             |
| **smoooooth**<br>[source](https://github.com/gnachman/iTerm2/blob/33945e63ad48ed80d6cc1adf7cbeb663217652d2/plists/ColorPresets.plist#L4345-L4685) |             ![smoooooth](images/smoooooth.png)             |
|                                      **_solarized_dark_**<br>[source](http://ethanschoonover.com/solarized)                                       |        ![solarized_dark](images/solarized_dark.png)        |
|                                      **_solarized_light_**<br>[source](http://ethanschoonover.com/solarized)                                      |       ![solarized_light](images/solarized_light.png)       |
|                               **_solarized_osaka_**<br>[source](https://github.com/craftzdog/solarized-osaka.nvim)                                |     ![solarized_osaka](images/solarized_osaka.png)         |
|                                    **_taerminal_**<br>[source](https://github.com/cozywigwam/iterm-taerminal)                                     |             ![taerminal](images/taerminal.png)             |
|   **_tango_dark_**<br>[source](https://github.com/GNOME/gnome-terminal/blob/18939a24d21d6b7c6edd57a00a3a8a48f3aecec5/src/profile-editor.c#L213)   |            ![tango_dark](images/tango_dark.png)            |
|                                      **_tender_**<br>[source](https://github.com/huyvohcmc/tender-alacritty)                                      |                ![tender](images/tender.png)                |
|                                                                **_terminal_app_**                                                                 |          ![terminal_app](images/terminal_app.png)          |
|                                                                 **_thelovelace_**                                                                 |          ![terminal_app](images/thelovelace.png)           |
|                             **_tokyo-night_**<br>[source](https://github.com/zatchheems/tokyo-night-alacritty-theme)                              |           ![tokyo-night](images/tokyo-night.png)           |
|                          **_tokyo-night-storm_**<br>[source](https://github.com/zatchheems/tokyo-night-alacritty-theme)                           |     ![tokyo-night-storm](images/tokyo-night-storm.png)     |
|                                 **_tomorrow_night_**<br>[source](https://github.com/ChrisKempson/Tomorrow-Theme)                                  |        ![tomorrow_night](images/tomorrow_night.png)        |
|                              **_tomorrow_night_bright_**<br>[source](https://github.com/ChrisKempson/Tomorrow-Theme)                              | ![tomorrow_night_bright](images/tomorrow_night_bright.png) |
|                                     **_ubuntu_**<br>[source](https://design.ubuntu.com/brand/colour-palette/)                                     |                ![ubuntu](images/ubuntu.png)                |
|                                        **_wombat_**<br>[source](https://github.com/djoyner/iTerm2-wombat)                                         |                ![wombat](images/wombat.png)                |
|                                                                    **_xterm_**                                                                    |                 ![xterm](images/xterm.png)                 |
|                                          **_zenburn_**<br>[source](https://github.com/jnurmine/Zenburn)                                           |               ![zenburn](images/zenburn.png)               |

## Contributing

Bug reports and pull requests are welcome on GitHub at the [alacritty-theme]
repository.

[alacritty-theme]: https://github.com/alacritty/alacritty-theme

To add a new theme, just create a Pull Request with the following changes:

 - Add your theme to the `themes` directory with the `{theme}.toml` file format
 - Create a screenshot of your theme using the [`print_colors.sh`](./print_colors.sh) script
 - Add the screenshot to the `images` directory with the `{theme}.png` file format
 - Add your theme to the `README.md`, following alphabetical ordering

## Maintainers

 * **indrajit** - *Author* - [eendroroy](https://github.com/eendroroy)
 * **Christian Dürr** - *Maintainer* - [chrisduerr](https://github.com/chrisduerr)

## License

The project is available as open source under the terms of the [Apache License, Version 2.0](LICENSE)
