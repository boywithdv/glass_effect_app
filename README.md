# Glass (or blur) Effect in Flutter - No Package

Apple just introduced the Liquid Glass effect at WWDC25!

![Flutter Blur Effect Demo Image](blur_thum.jpg)
![Flutter Blur Effect Demo Video](flutter_blur_intro.gif)

## 概要

このプロジェクトは、FlutterでAppleのLiquid Glass（ガラス・ブラー）エフェクトをパッケージなしで実装したサンプルアプリです。

## 特徴

- パッケージ未使用でのガラス効果実装
- クロスプラットフォーム（iOS, Android, Web, Windows, macOS, Linux）対応
- シンプルなメディアプレイヤーUI

## 使い方

1. Flutter環境をセットアップしてください。
2. このリポジトリをクローンします。

   ```sh
   git clone <このリポジトリのURL>
   cd glass_effect_app
   ```

3. 依存パッケージを取得します。

   ```sh
   flutter pub get
   ```

4. アプリを起動します。

   ```sh
   flutter run
   ```

## ビルド方法

各プラットフォームごとに以下のコマンドでビルドできます。

- Android: `flutter build apk`
- iOS: `flutter build ios`
- Web: `flutter build web`
- Windows: `flutter build windows`
- macOS: `flutter build macos`
- Linux: `flutter build linux`

## ディレクトリ構成

- `lib/` ... メインのDartコード
- `assets/` ... 画像などのアセット
- `android/`, `ios/`, `web/`, `windows/`, `macos/`, `linux/` ... 各プラットフォーム用コード

## ライセンス

MIT
