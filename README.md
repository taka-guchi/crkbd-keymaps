# crkbd-keymaps

## Setting Up Your QMK Environment
- [セットアップガイド](https://docs.qmk.fm/#/newbs_getting_started)を参考にファームウェアをビルドする
  - keyboard: crkbd/rev1(`~/qmk_firmware/keyboards/crkbd/`配下のフォルダ構成から判断する)
  - `~/qmk_firmware/keyboards/crkbd/keymaps/`配下に任意の名前でフォルダを作る(GitHubのusername推奨)
  - 上で作成したフォルダに`config.h`,`keymap.c`,`rules.mk`の3ファイルを配置する
  
## Change Keymaps
- [Keycodes Full List](https://docs.qmk.fm/#/keycodes)を参考に`keymap.c`をカスタマイズする

## Write The Firmware
- QMK Toolboxを使用して上記でビルドしたファームウェアをキーボードに書き込む
- [参考](https://github.com/foostan/crkbd/blob/master/doc/firmware_jp.md)
