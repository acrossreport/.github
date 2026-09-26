🇬🇧 [English](README.md) | 🇫🇷 [Français](README.fr.md)

# Across Report Renderer (ACR)

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
| ACR Viewer for VSCode | VS Code 上での印刷プレビューと PDF 出力 | [Marketplace](https://marketplace.visualstudio.com/items?itemName=across-systems.acr-viewer-vscode) / [Open VSX](https://open-vsx.org/extension/across-systems/acr-viewer-vscode) |
| ACR Migrate | ActiveReports RPX / Microsoft RDL を ACR 形式に変換 | [GitHub](https://github.com/acrossreport/acr-migrate) |
| acr-spec | テンプレート仕様 | [GitHub](https://github.com/acrossreport/acr-spec) |

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

## 🌍 リンク

<!-- リンクを追加するときは、ここに1行足す -->

- https://acrossreport.com
- https://zenn.dev/maskedridersys/scraps/72fe431a892341
- https://qiita.com/maskedridersystem

---

## 💬 フィードバック

ご意見・不具合報告・コントリビューションを歓迎します。
