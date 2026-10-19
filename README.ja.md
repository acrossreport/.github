# Across Report Renderer (ACR)

🇬🇧 [English](README.md) | 🇫🇷 [Français](README.fr.md)

**一度作れば、どこにでも出力できる。**

ACR は、プリンタを選ばない、クロスプラットフォームの帳票描画エンジンです。

ACR は、プリンタドライバに頼ることなく、画面表示と印刷の両方でピクセル単位の再現性を保証します。

---

## 🚀 特徴

- クロスプラットフォーム(Windows / Linux / macOS)
- ピクセル単位のレイアウト再現(WYSIWYG)
- プリンタドライバに依存しない描画
- 自動化に向いた CLI ベースのエンジン
- テンプレート仕様(ACR spec)の公開
- 高い可搬性と、決定論的な出力

---

## 📦 プロダクト

<!-- 製品を追加するときは、この表に1行足す。形式: | 名前 | 説明 | リンク | -->

| 名前 | 説明 | リンク |
|---|---|---|
| ACR Tech Articles | ACR に関する技術記事（日本語/英語） | [GitHub](https://github.com/acrossreport/acr-tech-articles) |
| ACR Viewer for VSCode | VS Code 上での印刷プレビューと PDF 出力 | [Marketplace](https://marketplace.visualstudio.com/items?itemName=across-systems.acr-viewer-vscode) / [Open VSX](https://open-vsx.org/extension/across-systems/acr-viewer-vscode) |
| ACR CLI | CLI ベースの描画エンジン — プリンタドライバや GUI なしで PDF・PNG を生成(macOS 版はコード署名済み) | [GitHub](https://github.com/acrossreport/acr-cli) |
| ACR Node | Node.js / Electron から ACR テンプレートを PDF・PNG に描画(napi-rs ネイティブアドオン) | [npm](https://www.npmjs.com/package/@acrossreport/acr-node) / [GitHub](https://github.com/acrossreport/acr-node) |
| ACR Designer | 帳票デザインツール(バンド / Free Canvas、DB 接続、PDF・PNG・HTML 出力) | [GitHub](https://github.com/acrossreport/acr-designer) |
| ACR Generator | acr-png2json の出力を読み込み、セクションを付けて ACR JSON として保存 | [GitHub](https://github.com/acrossreport/acr-generator) |
| ACR Viewer | 監視フォルダ / HTTP で受け取ったデータの印字と PDF・PNG 出力を行う常駐アプリ(macOS 版はコード署名済み) | [GitHub](https://github.com/acrossreport/acr-viewer) |
| ACR Migrate | ActiveReports RPX / Microsoft RDL を ACR 形式に変換 | [GitHub](https://github.com/acrossreport/acr-migrate) |
| ACR PNG2JSON | 紙の帳票をスキャンした PNG を、ACR Free Canvas 用の JSON に変換 | [GitHub](https://github.com/acrossreport/acr-png2json) |
| ACR Spec | テンプレート仕様 | [GitHub](https://github.com/acrossreport/acr-spec) |
| ACR Libs Samples | C# / VB.NET / Python / Java から ACR ネイティブライブラリを呼び出す最小サンプル | [GitHub](https://github.com/acrossreport/acr-libs-samples) |
| ACR Data Samples | すぐに試せるサンプルテンプレート・データ | [GitHub](https://github.com/acrossreport/acr-data-samples) |

---

## 🔧 アーキテクチャ

テンプレート → レイアウトエンジン → 描画エンジン → 出力

---

## 📄 出力形式

<!-- 出力形式を追加するときは、ここに1行足す -->

- PDF
- PNG / 画像
- レシート・ラベルプリンタ向けコマンド(ESC/POS、StarPRNT、ZPL、SBPL、TPCL、TSPL)
- 画面表示
- 今後の機器別レンダラー

---

## 📜 ライセンスとサポート

- 各プロジェクトの基本機能は無償でご利用いただけます。
- サポートが必要な場合は、別途ご相談ください。
- ライセンスキー(メールアドレス1つにつき1キー)で、PC 3台まで登録できます。それ以上必要な場合もご相談ください。
- 故障などで端末を入れ替える場合は、メールをいただければ再登録・復旧対応いたします。

---

## 🌍 リンク

<!-- リンクを追加するときは、ここに1行足す -->

- https://acrossreport.com
- https://zenn.dev/maskedridersys/scraps/72fe431a892341
- https://qiita.com/maskedridersystem

---

## 💬 フィードバック

ご意見・不具合報告・コントリビューションを歓迎します。
