# ACR (Across Report)

**Printer-Independent Reporting Architecture**
Render once. Output everywhere.

**Patent Pending**

---

## Overview

ACR (Across Report) is a next-generation reporting architecture designed to separate **report definition**, **rendering**, and **output generation**.

Traditional reporting systems tightly couple layout, rendering engines, and printer commands.
ACR solves this by introducing a **printer-independent template architecture**.

With ACR, a single template can generate multiple outputs without modification.

Typical outputs include:

* PDF
* PNG / Image
* Thermal printer commands
* Screen display
* Future device-specific renderers

---

## Architecture

```
Template → Layout Engine → Rendering Engine → Output
```

ACR separates the reporting process into four independent layers.

| Layer            | Description                                |
| ---------------- | ------------------------------------------ |
| Template         | Defines report structure and layout        |
| Layout Engine    | Calculates positioning and pagination      |
| Rendering Engine | Converts layout into drawable objects      |
| Output           | Generates PDF, images, or printer commands |

This architecture enables **true device-independent report generation**.

---

## Key Features

* Printer-independent report templates
* Multi-output rendering from a single definition
* High-performance rendering engine
* JSON-based template format
* Support for thermal printers
* Cross-platform architecture
* Designed for modern microservice environments

---

## Supported Output Formats

ACR is designed to support multiple output targets.

Current implementations include:

* PDF
* PNG image rendering
* Screen display
* Thermal printer command generation

Future output targets may include:

* ESC/POS
* Zebra ZPL
* Star printer commands
* WebCanvas / WASM rendering

---

## Example

Example command using the CLI renderer.

```
acr_cli template.json data.json
```

Example template structure:

```json
{
  "page": {
    "width": 595,
    "height": 842
  },
  "sections": [
    {
      "type": "text",
      "x": 100,
      "y": 100,
      "text": "Hello ACR"
    }
  ]
}
```

The same template can be rendered to multiple formats without modification.

---

## Design Philosophy

ACR was designed with the following principles:

* **Device independence**
* **Separation of concerns**
* **High performance**
* **Extensibility**

The goal is to provide a universal reporting architecture that works across printers, servers, and modern application environments.

---

## Intellectual Property

The core architecture of **ACR (Across Report)** is currently **patent pending**.

The technology introduces a novel approach to **printer-independent report rendering using an intermediate template representation**.

---

## License

This project is released under an open-source license.

See the LICENSE file for details.

---

## Author

ACR Architecture
Hisanobu Araki

