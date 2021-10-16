[経緯](https://github.com/NullPopPoLab/batocera.linux/blob/master/!NullPopPo-Custom.md)

## とりあえず(かなり強引に)ビルド通してみた

- cmakeのエラーはてけとーに回避して .sln できたらあとは手動で
- 各種依存ライブラリ x64 MT でビルドしなおし

## 目的

システム構成の把握とカスタマイズ実験用。
本実装はbatocera側ということで。

## ブランチ説明

master: 派生元の更新捕捉用 
MyCustom: ここでの各種変更点をマージしたもの

### 差分管理ブランチ

BatoceraCustom: batocera版ソース捕捉用 (ビルド確認対象外)
ForVisualStudio2019: cmake捨ててベタslnで構成管理 個人環境差は各自で直して系なやつ
