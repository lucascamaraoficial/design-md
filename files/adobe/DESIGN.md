---
version: alpha
name: "Adobe"
description: "Design system extraído automaticamente de adobe.com. Inclui cores, tipografia, componentes e padrões visuais observados na página atual."
source: "https://www.adobe.com/br/"
generatedAt: "2026-05-08T23:43:32.072Z"
generator: "Site to DESIGN.md Chrome Extension"

colors:
  primary: "#FED800"
  primary-active: "#FED800"
  canvas: "#FFFFFF"
  surface-card: "#FFFFFF"
  surface-soft: "#F8F8F8"
  ink: "#2C2C2C"
  body: "#FFFFFF"
  muted: "#000000"
  border: "#2C2C2C"
  on-primary: "#111111"
  on-dark: "#ffffff"
  extracted-1: "#2C2C2C"
  extracted-2: "#FFFFFF"
  extracted-3: "#000000"
  extracted-4: "#F8F8F8"
  extracted-5: "#292929"
  extracted-6: "#FED800"
  extracted-7: "#EC1000"
  extracted-8: "#76E2FF"
  extracted-9: "#E72C00"
  extracted-10: "#FAFAFA"

typography:
  display-xl:
    fontFamily: "\"Adobe Clean\", adobe-clean, \"Trebuchet MS\", sans-serif"
    fontSize: "44px"
    fontWeight: "700"
    lineHeight: "55px"
    letterSpacing: "0"
  display-lg:
    fontFamily: "\"Adobe Clean\", adobe-clean, \"Trebuchet MS\", sans-serif"
    fontSize: "36px"
    fontWeight: "700"
    lineHeight: "45px"
    letterSpacing: "0"
  body-md:
    fontFamily: "\"Adobe Clean\", adobe-clean, \"Trebuchet MS\", sans-serif"
    fontSize: "18px"
    fontWeight: "400"
    lineHeight: "27px"
    letterSpacing: "0"
  button-md:
    fontFamily: "\"Adobe Clean\", adobe-clean, \"Trebuchet MS\", sans-serif"
    fontSize: "14px"
    fontWeight: "400"
    lineHeight: "19.6px"
    letterSpacing: "0"
  caption:
    fontFamily: "\"Adobe Clean\", adobe-clean, \"Trebuchet MS\", sans-serif"
    fontSize: "18px"
    fontWeight: "400"
    lineHeight: "27px"
    letterSpacing: "0"

rounded:
  none: "0px"
  sm: "25px"
  md: "16px"
  lg: "20px"
  full: "9999px"

spacing:
  xs: "100px"
  sm: "16px 24px"
  md: "8px normal"
  lg: "32px"
  xl: "32px"
  section: "64px"

shadows:
  soft: "none"
  card: "none"

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "#292929"
    typography: "{typography.body-md}"
    rounded: "0px"
    padding: "0px 20px 0px 20px"
    height: "63px"
  button-secondary:
    backgroundColor: "{colors.canvas}"
    textColor: "#FFFFFF"
    typography: "{typography.body-md}"
    rounded: "20px"
    padding: "7px 18px 8px 18px"
    height: "40px"
    border: "2px solid #FFFFFF"

  surface-card:
    backgroundColor: "#FFFFFF"
    textColor: "#2C2C2C"
    typography: "{typography.body-md}"
    rounded: "16px"
    padding: "0px 0px 0px 0px"
    height: "547px"

  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "#2C2C2C"
    typography: "{typography.body-md}"
    rounded: "0px"
    padding: "0px 0px 0px 0px"
    height: "63px"
---

# Design System extraído de Adobe: soluções de criação, de marketing e de gerenciamento de documentos

## Overview

Este DESIGN.md foi gerado automaticamente a partir da página **adobe.com**.

A extensão analisou o DOM renderizado no navegador e capturou estilos computados de cores, tipografia, componentes, espaçamentos, raios, sombras e superfícies visíveis.

> Fonte analisada: https://www.adobe.com/br/

## Visual Theme

A interface usa como base a cor de canvas `#FFFFFF`, texto principal em `#2C2C2C` e cor de ação provável em `#FED800`. O sistema visual foi inferido a partir dos elementos visíveis na página atual.

## Colors

- **Extraída 1**: `#2C2C2C` (210 ocorrências)
- **Extraída 2**: `#FFFFFF` (163.5 ocorrências)
- **Extraída 3**: `#000000` (48 ocorrências)
- **Extraída 4**: `#F8F8F8` (16 ocorrências)
- **Extraída 5**: `#292929` (13 ocorrências)
- **Extraída 6**: `#FED800` (8 ocorrências)
- **Extraída 7**: `#EC1000` (8 ocorrências)
- **Extraída 8**: `#76E2FF` (8 ocorrências)
- **Extraída 9**: `#E72C00` (8 ocorrências)
- **Extraída 10**: `#FAFAFA` (8 ocorrências)

### Papéis sugeridos

- **Primary**: `#FED800`
- **Canvas**: `#FFFFFF`
- **Ink**: `#2C2C2C`
- **Muted**: `#000000`
- **Border**: `#2C2C2C`
- **Surface Card**: `#FFFFFF`

## Typography

- `"Adobe Clean", adobe-clean, "Trebuchet MS", sans-serif` (72 ocorrências)

### Hierarquia inferida

| Papel | Fonte | Tamanho | Peso | Linha | Espaçamento |
|---|---|---:|---:|---:|---:|
| hero | `"Adobe Clean", adobe-clean, "Trebuchet MS", sans-serif` | `44px` | `700` | `55px` | `normal` |
| section | `"Adobe Clean", adobe-clean, "Trebuchet MS", sans-serif` | `36px` | `700` | `45px` | `normal` |
| heading | `"Adobe Clean", adobe-clean, "Trebuchet MS", sans-serif` | `24px` | `700` | `30px` | `normal` |
| body | `"Adobe Clean", adobe-clean, "Trebuchet MS", sans-serif` | `18px` | `400` | `27px` | `normal` |
| button | `"Adobe Clean", adobe-clean, "Trebuchet MS", sans-serif` | `14px` | `400` | `19.6px` | `normal` |
| nav-link | `"Adobe Clean", adobe-clean, "Trebuchet MS", sans-serif` | `18px` | `400` | `27px` | `normal` |

## Layout

- Viewport analisado: 1470×717px.
- Espaçamentos recorrentes: `32px`, `8px normal`, `16px 24px`, `100px`, `16px`, `4px`, `8px`, `56px`.
- Raios recorrentes: `20px`, `16px`, `25px`, `50%`, `5.008px`.

## Elevation & Depth

- Nenhuma sombra relevante foi detectada.

## Components

- **button**: capturado em `button.feds-navLink.feds-navLink--hoverCaret` com 169×63px.
- **card**: capturado em `div.editorial-card.l-rounded-corners.no-border` com 276×547px.
- **nav**: capturado em `nav.feds-topnav` com 1440×63px.
- **secondaryButton**: capturado em `a.con-button.outline.button-l` com 144×40px.

## Do's and Don'ts

### Do

- Use os tokens do frontmatter como fonte principal.
- Revise manualmente os componentes antes de usar em produção.
- Complete estados não visíveis, como hover, focus, disabled e erro.

### Don't

- Não trate este arquivo como design system oficial da marca.
- Não assuma estados ou componentes que não estavam visíveis na página.
- Não use cores extraídas sem validar contraste e acessibilidade.

## Known Gaps

- O arquivo foi gerado por inspeção visual do DOM renderizado.
- Estados interativos podem não ter sido capturados.
- Componentes fora da viewport ou carregados após interação podem estar ausentes.
- A intenção de marca precisa de revisão humana.
