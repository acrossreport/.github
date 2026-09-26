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

<!-- Pour ajouter un produit, ajoutez une ligne à ce tableau. Format : | Nom | Description | Lien | -->

| Nom | Description | Lien |
|---|---|---|
| ACR Viewer for VSCode | Aperçu avant impression et export PDF dans VS Code | [Marketplace](https://marketplace.visualstudio.com/items?itemName=across-systems.acr-viewer-vscode) / [Open VSX](https://open-vsx.org/extension/across-systems/acr-viewer-vscode) |
| ACR Migrate | Convertit ActiveReports RPX / Microsoft RDL au format ACR | [GitHub](https://github.com/acrossreport/acr-migrate) |
| ACR PNG2JSON | Convertit un rapport papier numérisé (PNG) en JSON pour ACR Free Canvas | [GitHub](https://github.com/acrossreport/acrpng2json) |
| acr-spec | Spécification du gabarit | [GitHub](https://github.com/acrossreport/acr-spec) |

---

## 🔧 Architecture

Gabarit → Moteur de mise en page → Moteur de rendu → Sortie

---

## 📄 Formats de sortie

<!-- Pour ajouter un format de sortie, ajoutez une ligne ici -->

- PDF
- PNG / Image
- Commandes pour imprimantes de reçus/étiquettes (ESC/POS, StarPRNT, ZPL, SBPL, TPCL, TSPL)
- Rendu à l'écran
- Futurs moteurs de rendu spécifiques aux appareils

---

## 🌍 Liens

<!-- Pour ajouter un lien, ajoutez-le ici -->

- https://acrossreport.com
- https://zenn.dev/maskedridersys/scraps/72fe431a892341
- https://qiita.com/maskedridersystem

---

## 💬 Retours

Vos retours, signalements de problèmes et contributions sont les bienvenus !
