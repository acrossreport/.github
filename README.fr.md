# Across Report Renderer (ACR)

🇬🇧 [English](README.md) | 🇯🇵 [日本語](README.ja.md)

**Concevez une fois. Imprimez partout.**

ACR est un moteur de rendu de documents multiplateforme, indépendant de l'imprimante.

ACR garantit un rendu fidèle au pixel près, à l'écran comme à l'impression, sans dépendre des pilotes d'imprimante.

---

## 🚀 Caractéristiques

- Multiplateforme (Windows / Linux / macOS)
- Mise en page fidèle au pixel près (WYSIWYG)
- Rendu indépendant de l'imprimante (aucune dépendance aux pilotes)
- Moteur en ligne de commande, adapté à l'automatisation
- Spécification de gabarit publiée (ACR spec)
- Grande portabilité et sortie déterministe

---

## 📦 Produits

<!-- 製品を追加するときは、この表に1行足す。形式: | 名前 | 説明 | リンク | -->

| Nom | Description | Lien |
|---|---|---|
| ACR Viewer for VSCode | Aperçu avant impression et export PDF dans VS Code | [Marketplace](https://marketplace.visualstudio.com/items?itemName=across-systems.acr-viewer-vscode) / [Open VSX](https://open-vsx.org/extension/across-systems/acr-viewer-vscode) |
| ACR Designer | Outil de conception de rapports (bandes / Free Canvas, connexions aux bases de données, sortie PDF/PNG/HTML) | [GitHub](https://github.com/acrossreport/acr-designer) |
| ACR Generator | Charge la sortie d'acr-png2json, ajoute des sections et enregistre au format JSON ACR | [GitHub](https://github.com/acrossreport/acr-generator) |
| ACR Viewer | Application résidente d'impression par dossier surveillé / HTTP et de sortie PDF/PNG | [GitHub](https://github.com/acrossreport/acr-viewer) |
| ACR Migrate | Convertit ActiveReports RPX / Microsoft RDL au format ACR | [GitHub](https://github.com/acrossreport/acr-migrate) |
| ACR PNG2JSON | Convertit un rapport papier numérisé (PNG) en JSON pour ACR Free Canvas | [GitHub](https://github.com/acrossreport/acr-png2json) |
| acr-spec | Spécification du gabarit | [GitHub](https://github.com/acrossreport/acr-spec) |

---

## 🔧 Architecture

Gabarit → Moteur de mise en page → Moteur de rendu → Sortie

---

## 📄 Formats de sortie

<!-- 出力形式を追加するときは、ここに1行足す -->

- PDF
- PNG / Image
- Commandes pour imprimantes de reçus/étiquettes (ESC/POS, StarPRNT, ZPL, SBPL, TPCL, TSPL)
- Rendu à l'écran
- Futurs moteurs de rendu spécifiques aux appareils

---

## 🌍 Liens

<!-- リンクを追加するときは、ここに1行足す -->

- https://acrossreport.com
- https://zenn.dev/maskedridersys/scraps/72fe431a892341
- https://qiita.com/maskedridersystem

---

## 💬 Retours

Vos retours, signalements de problèmes et contributions sont les bienvenus !
