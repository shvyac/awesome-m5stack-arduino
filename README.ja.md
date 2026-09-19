# Awesome M5Stack Arduino（日本語）

[English README](README.md)

[M5Stack](https://m5stack.com/) デバイスを Arduino（および記載がある場合は PlatformIO）で開発するための厳選リンク集。新規プロジェクトでは **M5Unified + M5GFX** を推奨。クラシックな `M5Stack` ライブラリは、古い Core 向けサンプルに引き続き有用です。

## 目次

- [公式](#公式)
- [ライブラリ](#ライブラリ)
- [サンプル](#サンプル)
- [ハードウェアと回路図](#ハードウェアと回路図)
- [コミュニティ](#コミュニティ)

---

## 公式

- [m5-docs](https://docs.m5stack.com/) — 公式ドキュメント（製品、Arduino、API）
- [Arduino Board Manager](https://docs.m5stack.com/en/arduino/arduino_board) — Additional Board Manager URL `https://static-cdn.m5stack.com/resource/arduino/package_m5stack_index.json` でボードをインストール
- [Arduino Library Manager](https://docs.m5stack.com/en/arduino/arduino_library) — IDE から M5 ドライバライブラリをインストール
- [Getting started](https://docs.m5stack.com/en/start) — Arduino およびその他の M5Stack ツールチェーンの概要
- [M5Unified Hello World](https://docs.m5stack.com/en/arduino/m5unified/helloworld) — 統合 API による最初のスケッチ
- [PlatformIO + M5Unified](https://docs.m5stack.com/en/arduino/m5unified/intro_vscode) — VS Code / PlatformIO のセットアップ（[日本語](https://docs.m5stack.com/ja/arduino/m5unified/intro_vscode)）
- [M5Stack shop](https://shop.m5stack.com/) — ハードウェアカタログ

## ライブラリ

- [M5Unified](https://github.com/m5stack/M5Unified) — ほとんどの M5 コントローラ向け推奨統合ドライバ（LCD、ボタン、タッチ、オーディオ、IMU、電源、RTC）
- [M5GFX](https://github.com/m5stack/M5GFX) — M5Unified が使うグラフィックスライブラリ（フォント、キャンバス、ディスプレイ）
- [M5Stack (legacy)](https://github.com/m5stack/M5Stack) — M5Stack Core / Basic / Gray / Fire 向けクラシック Arduino ライブラリ
- [M5UnitUnified](https://github.com/m5stack/M5UnitUnified) — Unit シリーズ周辺機器向け統合ドライバ
- [TFT_eSPI](https://github.com/Bodmer/TFT_eSPI) — STM32、ESP8266、ESP32、RP2040 向けに最適化された Arduino / PlatformIO TFT ライブラリ

## サンプル

- [M5Unified examples](https://github.com/m5stack/M5Unified/tree/master/examples) — Basic / Advanced スケッチ（ディスプレイ、ボタン、タッチ、スピーカー、マイク、IMU、RTC）
- [M5GFX examples](https://github.com/m5stack/M5GFX/tree/master/examples) — グラフィックスデモ
- [M5Stack library examples](https://github.com/m5stack/M5Stack/tree/master/examples) — レガシー Core 向けサンプル（Basics、Modules ほか）

## ハードウェアと回路図

- [M5-Schematic](https://github.com/m5stack/M5-Schematic) — Core / Module / Unit の回路図（アーカイブ済みだが今も有用）
- [M5 Core Basic schematic (2017)](https://github.com/m5stack/M5-Schematic/blob/master/Core/Basic/M5-Core-Schematic(20171206).pdf) — オリジナル Core/Basic の PDF
- [Basic product docs](https://docs.m5stack.com/en/core/basic) — m5-docs 上のピンマップと現行回路図リンク

## コミュニティ

- [M5Stack Community Forum](https://community.m5stack.com/) — 公式フォーラム（Software 配下に Arduino）
- [日本語フォーラム](https://community.m5stack.com/category/27/%E6%97%A5%E6%9C%AC%E8%AA%9E%E3%83%95%E3%82%A9%E3%83%BC%E3%83%A0) — 日本語コミュニティセクション
- [m5stack on GitHub](https://github.com/m5stack) — 公式オーガニゼーションのリポジトリ
