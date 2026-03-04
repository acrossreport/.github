# Across Report (ACR)

ACR (Across Report) is a printer-independent reporting architecture.

Render once. Output everywhere.

ACR separates layout description, rendering, and output generation.

---

## Architecture

```
Template → Layout → Rendering Engine → Output
```

ACR templates describe layout and content independently of printer or rendering technology.

The same template can be rendered to multiple output formats such as PDF, PNG, printer commands, or screen display.

