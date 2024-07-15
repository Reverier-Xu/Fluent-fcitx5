# Fluent theme for Fcitx5

A Fluent-Design theme with blur effect and shadow.

This skin is using BlurEffect which is provided by KWin, so plz use it on the KDE Plasma desktop environment or other DEs with KWin as backend.

## Theme

Fluent dark:

![](imgs/sample-dark.webp)

Fluent light:

![](imgs/sample-light.webp)

## Usage

put the `Fluent*` folder under `/usr/share/fcitx5/themes/` or `$HOME/.local/share/fcitx5/themes/`, then open config tool and choose the theme you want to use.

Arch Linux users:

```shell
# Dark theme
paru -S fcitx5-skin-fluentdark-git
# Light theme
paru -S fcitx5-skin-fluentlight-git
```

## Misc

This theme uses a new feature here: [fcitx5/pull/474](https://github.com/fcitx/fcitx5/pull/474), old versions may have unexpected offsets. if you like, you can modify the margins and remove the shadow of panel.png.

Please note that the fcitx5 blurring effects provided by lower versions of kwin may not work on Wayland, so if you don't like transparent-but-not-blurred panels, I have provided a solid theme `Fluent*-solid`. Also, the input panels are positioned by Wayland, not fcitx5, so the shadow margin feature will not work on Wayland either.

## LICENSE

Mozilla Public License v2

@ 2022 Reverier-Xu.
