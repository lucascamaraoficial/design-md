---
version: alpha
name: "adobe"
description: "Design system extraído automaticamente de adobe. Inclui cores, tipografia, componentes e padrões visuais observados na página atual."
source: "https://www.adobe.com/"
generatedAt: "2026-05-08T23:56:22.370Z"
generator: "Site to DESIGN.md Chrome Extension"
stylesheetSources:
  - "inline <style>"
  - "https://www.adobe.com/libs/styles/styles.css"
  - "CSSOM inline stylesheet"
  - "https://www.adobe.com/libs/blocks/hero-marquee/hero-marquee.css"
  - "https://www.adobe.com/libs/blocks/global-navigation/global-navigation.css"
  - "https://www.adobe.com/libs/blocks/brand-concierge/brand-concierge.css"
  - "https://www.adobe.com/homepage/styles/styles.css"
  - "https://www.adobe.com/libs/styles/breakpoint-theme.css"
  - "https://use.typekit.net/hah7vzn.css"
  - "https://www.adobe.com/libs/mep/ace0861/section-metadata/section-metadata.css"
  - "https://www.adobe.com/libs/blocks/global-navigation/base.css"
  - "https://www.adobe.com/libs/features/georoutingv2/georoutingv2.css"
  - "https://www.adobe.com/libs/blocks/modal/modal.css"
  - "https://www.adobe.com/upp/blocks/homepage-link-bar/homepage-link-bar.css"
  - "https://www.adobe.com/libs/features/icons/icons.css"
  - "https://www.adobe.com/upp/blocks/homepage-brick/homepage-brick.css"
  - "https://www.adobe.com/libs/blocks/merch/merch.css"
  - "https://www.adobe.com/libs/blocks/text/text.css"
  - "https://www.adobe.com/libs/blocks/global-footer/global-footer.css"
  - "https://prod.adobeccstatic.com/unav/1.5/UniversalNav.css"
cssVariables:
  "--accent-height": "10px"
  "--alias-background-semantic-accent-default-express": "#A7AAFF"
  "--alias-background-semantic-accent-default-spectrum": "#0367E0"
  "--alias-background-semantic-accent-default-spectrum-2": "#4069FD"
  "--alias-background-semantic-accent-hover-express": "#BCBEFF"
  "--alias-background-semantic-accent-hover-spectrum": "#0059C2"
  "--alias-background-semantic-accent-hover-spectrum-2": "#345BF8"
  "--alias-content-background-neutral-default": "#292929"
  "--alias-content-neutral-default": "#292929"
  "--alias-content-neutral-key-focus": "#507BFF"
  "--alias-icon-background-neutral-default": "#DBDBDB"
  "--alias-icon-neutral-default": "#DBDBDB"
  "--alias-icon-neutral-key-focus": "#3860FA"
  "--app-banner-height": "76px"
  "--appFrame-layer-2": "#FFFFFF"
  "--aspect-ratio-square": "1/1"
  "--aspect-ratio-standard": "4/3"
  "--aspect-ratio-tall": "9/16"
  "--aspect-ratio-wide": "16/9"
  "--avatar-size": "1.875rem"
  "--background-color": "#fff"
  "--bc-button-color": "#292929"
  "--bc-button-dimensions": "32px"
  "--bc-button-hover-color": "#131313"
  "--bc-button-radius": "50%"
  "--bc-card-border-color": "rgba(0 0 0 / 12%)"
  "--bc-card-border-color-hover": "rgba(0 0 0 / 22%)"
  "--bc-card-font-size": "16px"
  "--bc-card-line-height": "24px"
  "--bc-card-radius": "12px"
  "--bc-card-text-color": "#292929"
  "--bc-floating-button-border-color": "rgba(0 0 0 / 12%)"
  "--bc-floating-button-border-color-hover": "rgba(0 0 0 / 22%)"
  "--bc-floating-button-height": "48px"
  "--bc-floating-button-spacing": "24px"
  "--bc-header-color": "#131313"

colors:
  primary: "#1473E6"
  primary-active: "#1473E6"
  canvas: "#FFFFFF"
  surface-card: "#F8F8F8"
  surface-soft: "#292929"
  ink: "#2C2C2C"
  body: "#2C2C2C"
  muted: "#000000"
  border: "#000000"
  on-primary: "#FFFFFF"
  on-dark: "#ffffff"
  extracted-1: "#000000"
  extracted-2: "#FFFFFF"
  extracted-3: "#2C2C2C"
  extracted-4: "#292929"
  extracted-5: "#EAEAEA"
  extracted-6: "#505050"
  extracted-7: "#E1E1E1"
  extracted-8: "#1473E6"
  extracted-9: "#4B4B4B"
  extracted-10: "#B3B3B3"

typography:
  display-xl:
    fontFamily: "\"Adobe Clean\", adobe-clean, \"Trebuchet MS\", sans-serif"
    fontSize: "36px"
    fontWeight: "700"
    lineHeight: "45px"
    letterSpacing: "0"
  display-lg:
    fontFamily: "\"Adobe Clean\", adobe-clean, \"Trebuchet MS\", sans-serif"
    fontSize: "20px"
    fontWeight: "700"
    lineHeight: "25px"
    letterSpacing: "0"
  body-md:
    fontFamily: "\"Adobe Clean\", adobe-clean, \"Trebuchet MS\", sans-serif"
    fontSize: "16px"
    fontWeight: "700"
    lineHeight: "20px"
    letterSpacing: "0"
  button-md:
    fontFamily: "\"Adobe Clean\", adobe-clean, \"Trebuchet MS\", sans-serif"
    fontSize: "14px"
    fontWeight: "400"
    lineHeight: "19.6px"
    letterSpacing: "0"
  caption:
    fontFamily: "\"Adobe Clean\", adobe-clean, \"Trebuchet MS\", sans-serif"
    fontSize: "16px"
    fontWeight: "700"
    lineHeight: "20px"
    letterSpacing: "0"

rounded:
  none: "0px"
  sm: "50%"
  md: "16px"
  lg: "20px"
  full: "9999px"

spacing:
  xs: "4px"
  sm: "16px"
  md: "32px"
  lg: "15px normal"
  xl: "32px"
  section: "64px"

shadows:
  soft: "none"
  card: "rgba(0, 0, 0, 0.06) 0px 4px 12px 0px"

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
    textColor: "#292929"
    typography: "{typography.body-md}"
    rounded: "16px"
    padding: "6px 16px 8px 16px"
    height: "32px"
    border: "2px solid #DADADA"



  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "#2C2C2C"
    typography: "{typography.body-md}"
    rounded: "0px"
    padding: "0px 0px 0px 0px"
    height: "63px"
---

# Design System extraído de adobe

## Overview

Este DESIGN.md foi gerado automaticamente a partir da página **adobe**.

A extensão analisou o DOM renderizado no navegador e capturou estilos computados de cores, tipografia, componentes, espaçamentos, raios, sombras e superfícies visíveis.

> Fonte analisada: https://www.adobe.com/

## Visual Theme

A interface usa como base a cor de canvas `#FFFFFF`, texto principal em `#2C2C2C` e cor de ação provável em `#1473E6`. O sistema visual foi inferido a partir dos elementos visíveis na página atual.

## Colors

- **Extraída 1**: `#000000` (2399 ocorrências)
- **Extraída 2**: `#FFFFFF` (943.5 ocorrências)
- **Extraída 3**: `#2C2C2C` (770 ocorrências)
- **Extraída 4**: `#292929` (420.5 ocorrências)
- **Extraída 5**: `#EAEAEA` (259 ocorrências)
- **Extraída 6**: `#505050` (219.5 ocorrências)
- **Extraída 7**: `#E1E1E1` (164 ocorrências)
- **Extraída 8**: `#1473E6` (136 ocorrências)
- **Extraída 9**: `#4B4B4B` (125 ocorrências)
- **Extraída 10**: `#B3B3B3` (112 ocorrências)

### CSS profundo

- Fontes CSS analisadas: 25.
- Regras CSS úteis extraídas: 260.
- Variáveis CSS detectadas: 242.

- `inline <style>`
- `https://www.adobe.com/libs/styles/styles.css`
- `CSSOM inline stylesheet`
- `https://www.adobe.com/libs/blocks/hero-marquee/hero-marquee.css`
- `https://www.adobe.com/libs/blocks/global-navigation/global-navigation.css`
- `https://www.adobe.com/libs/blocks/brand-concierge/brand-concierge.css`
- `https://www.adobe.com/homepage/styles/styles.css`
- `https://www.adobe.com/libs/styles/breakpoint-theme.css`
- `https://use.typekit.net/hah7vzn.css`
- `https://www.adobe.com/libs/mep/ace0861/section-metadata/section-metadata.css`
- `https://www.adobe.com/libs/blocks/global-navigation/base.css`
- `https://www.adobe.com/libs/features/georoutingv2/georoutingv2.css`

### Variáveis CSS relevantes

- `--accent-height`: `10px`
- `--alias-background-semantic-accent-default-express`: `#A7AAFF`
- `--alias-background-semantic-accent-default-spectrum`: `#0367E0`
- `--alias-background-semantic-accent-default-spectrum-2`: `#4069FD`
- `--alias-background-semantic-accent-hover-express`: `#BCBEFF`
- `--alias-background-semantic-accent-hover-spectrum`: `#0059C2`
- `--alias-background-semantic-accent-hover-spectrum-2`: `#345BF8`
- `--alias-content-background-neutral-default`: `#292929`
- `--alias-content-neutral-default`: `#292929`
- `--alias-content-neutral-key-focus`: `#507BFF`
- `--alias-icon-background-neutral-default`: `#DBDBDB`
- `--alias-icon-neutral-default`: `#DBDBDB`
- `--alias-icon-neutral-key-focus`: `#3860FA`
- `--app-banner-height`: `76px`
- `--appFrame-layer-2`: `#FFFFFF`
- `--aspect-ratio-square`: `1/1`
- `--aspect-ratio-standard`: `4/3`
- `--aspect-ratio-tall`: `9/16`
- `--aspect-ratio-wide`: `16/9`
- `--avatar-size`: `1.875rem`
- `--background-color`: `#fff`
- `--bc-button-color`: `#292929`
- `--bc-button-dimensions`: `32px`
- `--bc-button-hover-color`: `#131313`

### Papéis sugeridos

- **Primary**: `#1473E6`
- **Canvas**: `#FFFFFF`
- **Ink**: `#2C2C2C`
- **Muted**: `#000000`
- **Border**: `#000000`
- **Surface Card**: `#F8F8F8`

## Typography

- `"Adobe Clean", adobe-clean, "Trebuchet MS", sans-serif` (381 ocorrências)
- `adobe-clean` (39 ocorrências)
- `var(--body-font-family)` (30 ocorrências)
- `"Adobe Clean Black", var(--body-font-family)` (12 ocorrências)
- `adobe-clean,-apple-system,BlinkMacSystemFont,Segoe UI,sans-serif` (12 ocorrências)
- `16px` (12 ocorrências)

### Hierarquia inferida

| Papel | Fonte | Tamanho | Peso | Linha | Espaçamento |
|---|---|---:|---:|---:|---:|
| hero | `"Adobe Clean", adobe-clean, "Trebuchet MS", sans-serif` | `36px` | `700` | `45px` | `normal` |
| section | `"Adobe Clean", adobe-clean, "Trebuchet MS", sans-serif` | `20px` | `700` | `25px` | `normal` |
| heading | `"Adobe Clean", adobe-clean, "Trebuchet MS", sans-serif` | `16px` | `700` | `20px` | `normal` |
| body | `"Adobe Clean", adobe-clean, "Trebuchet MS", sans-serif` | `16px` | `700` | `20px` | `normal` |
| button | `"Adobe Clean", adobe-clean, "Trebuchet MS", sans-serif` | `14px` | `400` | `19.6px` | `normal` |
| nav-link | `"Adobe Clean", adobe-clean, "Trebuchet MS", sans-serif` | `18px` | `400` | `27px` | `normal` |

## Layout

- Viewport analisado: 1104×717px.
- Espaçamentos recorrentes: `15px normal`, `32px`, `16px`, `4px`, `8px`, `30px normal`, `16px 12px`, `normal 8px`.
- Raios recorrentes: `20px`, `16px`, `50%`, `5.008px`, `25px`, `24px`, `4px`, `0`.

## Elevation & Depth

- **Shadow 1**: `rgba(0, 0, 0, 0.06) 0px 4px 12px 0px`
- **Shadow 2**: `none`
- **Shadow 3**: `0 1px 4px #00000026`
- **Shadow 4**: `0 2px 10px rgba(0 0 0 / 10%)`
- **Shadow 5**: `0 -2px 24px rgba(0 0 0 / 18%)`
- **Shadow 6**: `0 0 .188rem 0 rgba(0,0,0,.12),0 .188rem .5rem 0 rgba(0,0,0,.04),0 .25rem 1rem 0 rgba(0,0,0,.08)`

## Components

- **button**: capturado em `button.feds-navLink.feds-navLink--hoverCaret` com 160×63px.
- **nav**: capturado em `nav.feds-topnav` com 1104×63px.
- **secondaryButton**: capturado em `button.profile-comp.secondary-button` com 76×32px.

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

- O arquivo foi gerado por inspeção visual do DOM renderizado e leitura profunda dos arquivos CSS acessíveis.
- Estados interativos podem não ter sido capturados.
- Componentes fora da viewport ou carregados após interação podem estar ausentes.
- A intenção de marca precisa de revisão humana.
