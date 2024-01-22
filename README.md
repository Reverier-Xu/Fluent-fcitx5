# Fluent Dark theme for Fcitx5

A Fluent-Design dark theme with blur effect and shadow.

This skin is using BlurEffect which is provided by KWin, so plz use it on the KDE Plasma desktop environment or other DEs with KWin as backend.

![](imgs/sample1.png)

![](imgs/sample2.png)

![](imgs/sample3.png)

## Usage

put the `FluentDark` folder under `/usr/share/fcitx5/themes/` or `$HOME/.local/share/fcitx5/themes/`, then open config tool and choose `FluentDark`.

suggested that use a monospace font such as `JetBrains Mono` in 12pt.

Arch Linux users:

```shell
paru -S fcitx5-skin-fluentdark-git
```

## Misc

This theme uses a new feature here: [fcitx5/pull/474](https://github.com/fcitx/fcitx5/pull/474), old versions may have unexpected offsets. if you like, you can modify the margins and remove the shadow of panel.png.

And please note that the fcitx5 blur effect provided by kwin won't work on Wayland, so I provided a solid theme `FluentDark-solid` if you don't like the transparent-but-not-blurred panel.

## LICENSE

Mozilla Public License v2

@ 2022 Reverier-Xu.
