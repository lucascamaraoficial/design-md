---
title: "Design System inspirado em Kraken"
description: "Exchange cripto. Roxo intenso, interfaces escuras premium, módulos financeiros e componentes orientados à confiança."
brand: "Kraken"
source: "https://www.kraken.com/pt-br"
language: "pt-BR"
version: "1.0.0"
category: "crypto, fintech, exchange"
tokens:
  colors:
    brand:
      purple: "#7132F5"
      purpleDark: "#5741D8"
      purpleDeep: "#5B1ECF"
      purpleSoft: "rgba(133, 91, 251, 0.16)"
      violetNight: "#1A082D"
      violetSurface: "#2A1247"
    neutral:
      black: "#000000"
      nearBlack: "#101114"
      darkSurface: "#07040D"
      surface: "#F7F5FA"
      white: "#FFFFFF"
      gray100: "#F4F4F7"
      gray200: "#E5E6EC"
      gray300: "#DEDEE5"
      gray500: "#9497A9"
      gray700: "#686B82"
    semantic:
      success: "#149E61"
      successDark: "#026B3F"
      danger: "#E65353"
      warning: "#F2B84B"
      info: "#7132F5"
  typography:
    display: "Kraken-Brand, IBM Plex Sans, Helvetica, Arial, sans-serif"
    body: "Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif"
    fallback: "IBM Plex Sans, Helvetica, Arial, sans-serif"
  radius:
    xs: "3px"
    sm: "6px"
    md: "8px"
    lg: "12px"
    xl: "16px"
    full: "9999px"
  shadows:
    soft: "0 4px 24px rgba(0, 0, 0, 0.03)"
    card: "0 24px 80px rgba(16, 17, 20, 0.18)"
    glowPurple: "0 24px 80px rgba(113, 50, 245, 0.28)"
---

# Design System inspirado em Kraken

## Overview

Exchange de criptomoedas. Roxo intenso, superfícies escuras premium, cards cinematográficos, dados financeiros e sensação de segurança institucional.

O design inspirado na Kraken combina uma base clara e limpa com grandes blocos escuros de alta densidade visual. A experiência usa roxo como principal assinatura de marca, tipografia direta, componentes arredondados e imagens 3D ou interfaces financeiras para transmitir controlo, tecnologia e confiança.

## Visual Language

### Direção visual

- Estética fintech premium com foco em cripto, investimento e negociação.
- Blocos grandes em preto, roxo profundo e gradientes escuros.
- Hero limpo com muito espaço em branco e CTA roxo.
- Cards imersivos com mockups, gráficos, dispositivos, cartões e objetos 3D.
- Mistura de linguagem institucional com visual futurista.

### Atmosfera

- Confiante
- Tecnológica
- Financeira
- Premium
- Direta
- Segura

## Color System

### Brand Colors

| Token | Valor | Uso |
|---|---:|---|
| `color.brand.purple` | `#7132F5` | CTA principal, links, destaques e botões |
| `color.brand.purpleDark` | `#5741D8` | Estados ativos, foco, bordas e variações |
| `color.brand.purpleDeep` | `#5B1ECF` | Fundos intensos e detalhes escuros |
| `color.brand.purpleSoft` | `rgba(133, 91, 251, 0.16)` | Badges, fundos subtis e estados suaves |
| `color.brand.violetNight` | `#1A082D` | Cards escuros com tom roxo |
| `color.brand.violetSurface` | `#2A1247` | Superfícies secundárias escuras |

### Neutral Colors

| Token | Valor | Uso |
|---|---:|---|
| `color.neutral.black` | `#000000` | Fundos de alto contraste |
| `color.neutral.nearBlack` | `#101114` | Texto principal e fundos escuros |
| `color.neutral.darkSurface` | `#07040D` | Cards imersivos |
| `color.neutral.surface` | `#F7F5FA` | Fundo geral claro |
| `color.neutral.white` | `#FFFFFF` | Texto sobre fundos escuros e cards claros |
| `color.neutral.gray100` | `#F4F4F7` | Chips, áreas subtis e divisórias leves |
| `color.neutral.gray200` | `#E5E6EC` | Bordas de campos e tabelas |
| `color.neutral.gray300` | `#DEDEE5` | Divisórias |
| `color.neutral.gray500` | `#9497A9` | Texto secundário |
| `color.neutral.gray700` | `#686B82` | Texto auxiliar e bordas fortes |

### Semantic Colors

| Token | Valor | Uso |
|---|---:|---|
| `color.semantic.success` | `#149E61` | Variação positiva, crescimento e ganhos |
| `color.semantic.successDark` | `#026B3F` | Texto de badge positivo |
| `color.semantic.danger` | `#E65353` | Perda, erro e alerta crítico |
| `color.semantic.warning` | `#F2B84B` | Atenção e avisos |
| `color.semantic.info` | `#7132F5` | Informação e links |

## Typography

### Font Families

| Token | Família | Uso |
|---|---|---|
| `font.display` | `Kraken-Brand, IBM Plex Sans, Helvetica, Arial, sans-serif` | Títulos, hero e chamadas principais |
| `font.body` | `Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif` | Interface, menus, texto e tabelas |
| `font.fallback` | `IBM Plex Sans, Helvetica, Arial, sans-serif` | Fallback universal |

### Type Scale

| Token | Tamanho | Peso | Altura | Espaçamento | Uso |
|---|---:|---:|---:|---:|---|
| `text.display.hero` | `48px` | `500–700` | `1.12` | `-1.76px` | Hero principal |
| `text.display.section` | `40px` | `500–700` | `1.16` | `-1.4px` | Títulos de secção |
| `text.heading.lg` | `32px` | `500–600` | `1.2` | `-1px` | Títulos de cards grandes |
| `text.heading.md` | `24px` | `500–600` | `1.25` | `-0.5px` | Subtítulos |
| `text.body.lg` | `18px` | `400` | `1.5` | `0` | Texto de apoio |
| `text.body.md` | `16px` | `400` | `1.45` | `0` | Corpo principal |
| `text.body.sm` | `14px` | `400–500` | `1.45` | `0` | Menus, tabelas e legendas |
| `text.caption` | `12px` | `500` | `1.35` | `0` | Badges, labels e metadados |
| `text.micro` | `10px` | `600` | `1` | `0.5px` | Selo pequeno e uppercase |

## Spacing

### Scale

| Token | Valor |
|---|---:|
| `space.1` | `4px` |
| `space.2` | `8px` |
| `space.3` | `12px` |
| `space.4` | `16px` |
| `space.5` | `20px` |
| `space.6` | `24px` |
| `space.8` | `32px` |
| `space.10` | `40px` |
| `space.12` | `48px` |
| `space.16` | `64px` |
| `space.20` | `80px` |
| `space.24` | `96px` |

### Layout Rules

- Usar `24px` como padding mínimo para cards pequenos.
- Usar `48px–80px` em secções principais.
- Manter cards com espaçamento amplo e conteúdo centralizado.
- Criar contraste entre secções claras e blocos escuros.
- Usar gaps de `8px–16px` em menus, chips e ações.

## Radius

| Token | Valor | Uso |
|---|---:|---|
| `radius.xs` | `3px` | Detalhes pequenos |
| `radius.sm` | `6px` | Badges e labels |
| `radius.md` | `8px` | Inputs e tabelas |
| `radius.lg` | `12px` | Botões e cards compactos |
| `radius.xl` | `16px` | Cards grandes |
| `radius.full` | `9999px` | Chips e avatares |

## Shadows

| Token | Valor | Uso |
|---|---|---|
| `shadow.soft` | `0 4px 24px rgba(0, 0, 0, 0.03)` | Cards claros |
| `shadow.card` | `0 24px 80px rgba(16, 17, 20, 0.18)` | Cards escuros premium |
| `shadow.glowPurple` | `0 24px 80px rgba(113, 50, 245, 0.28)` | Elementos roxos em destaque |

## Components

### Header

#### Estrutura

- Header fixo no topo ou estável no fluxo.
- Altura entre `56px` e `72px`.
- Fundo branco ou translúcido.
- Logo à esquerda.
- Navegação central com itens curtos.
- Ações à direita com idioma, login e CTA.

#### Tokens

```css
.header {
  height: 64px;
  padding: 0 32px;
  background: #ffffff;
  color: #101114;
  border-bottom: 1px solid rgba(222, 222, 229, 0.6);
}
```

#### Itens esperados

- Logo
- Menu principal
- Ícone ou seletor de idioma
- Botão de login
- Botão primário de cadastro

### Hero

#### Estrutura

- Fundo claro.
- Título grande centralizado.
- Subtítulo curto.
- Campo de e-mail ou input de entrada rápida.
- CTA roxo.
- Indicadores de confiança abaixo do CTA.

#### Tokens

```css
.hero {
  padding: 56px 24px 40px;
  background: #f7f5fa;
  text-align: center;
}

.hero-title {
  font-family: Kraken-Brand, IBM Plex Sans, Helvetica, Arial, sans-serif;
  font-size: 48px;
  line-height: 1.12;
  letter-spacing: -1.76px;
  color: #101114;
}

.hero-description {
  font-size: 18px;
  line-height: 1.5;
  color: #101114;
}
```

#### Conteúdo recomendado

- Headline forte sobre controlo financeiro.
- Subtexto sobre cripto, ações, futuros ou gestão de dinheiro.
- CTA direto.
- Métricas como tempo de mercado, volume negociado e confiança.

### Trust Metrics

#### Estrutura

- Linha horizontal com 3 ou 4 indicadores.
- Cada indicador com número forte e texto pequeno.
- Separadores subtis.

#### Tokens

```css
.trust-metric {
  display: grid;
  gap: 4px;
  text-align: center;
}

.trust-metric-value {
  font-size: 20px;
  font-weight: 600;
  color: #101114;
}

.trust-metric-label {
  font-size: 12px;
  color: #686b82;
}
```

### Feature Card Large

#### Estrutura

- Card grande, largura total.
- Fundo preto, roxo escuro, gradiente ou imagem.
- Conteúdo centralizado no topo.
- Badge pequeno no topo.
- Título curto.
- Descrição breve.
- CTA compacto.
- Imagem, mockup ou objeto visual na metade inferior.

#### Tokens

```css
.feature-card-large {
  border-radius: 16px;
  overflow: hidden;
  padding: 48px 32px 0;
  min-height: 560px;
  background: #07040d;
  color: #ffffff;
  box-shadow: 0 24px 80px rgba(16, 17, 20, 0.18);
}

.feature-card-large.is-purple {
  background: radial-gradient(circle at 50% 100%, #7132f5 0%, #1a082d 45%, #07040d 100%);
}
```

#### Variações

- Trading platform card
- Mobile app card
- Pro card
- Institutional card
- Global money app card

### Split Feature Grid

#### Estrutura

- Grid com 2 colunas no desktop.
- Cards escuros com altura semelhante.
- Cada card com título, descrição, CTA e visual.
- No mobile, empilhar em coluna única.

#### Tokens

```css
.split-feature-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 16px;
}

.split-feature-card {
  border-radius: 16px;
  padding: 40px 32px;
  min-height: 420px;
  background: #1a082d;
  color: #ffffff;
  overflow: hidden;
}
```

### Buttons

#### Primary Button

```css
.button-primary {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 44px;
  padding: 13px 16px;
  border-radius: 12px;
  border: 1px solid #7132f5;
  background: #7132f5;
  color: #ffffff;
  font-family: Kraken-Product, Helvetica Neue, Helvetica, Arial, sans-serif;
  font-size: 16px;
  font-weight: 600;
  line-height: 1.2;
}

.button-primary:hover {
  background: #5741d8;
  border-color: #5741d8;
}
```

#### Secondary Button

```css
.button-secondary {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 44px;
  padding: 13px 16px;
  border-radius: 12px;
  border: 1px solid #5741d8;
  background: #ffffff;
  color: #5741d8;
  font-size: 16px;
  font-weight: 600;
}
```

#### Subtle Button

```css
.button-subtle {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 36px;
  padding: 8px 12px;
  border-radius: 12px;
  background: rgba(133, 91, 251, 0.16);
  color: #7132f5;
  font-size: 14px;
  font-weight: 600;
}
```

#### White Button on Dark

```css
.button-white {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 40px;
  padding: 10px 14px;
  border-radius: 10px;
  background: #ffffff;
  color: #101114;
  font-size: 14px;
  font-weight: 600;
  box-shadow: 0 4px 24px rgba(0, 0, 0, 0.03);
}
```

### Inputs

#### Text Input

```css
.input {
  width: 100%;
  min-height: 44px;
  padding: 12px 14px;
  border: 1px solid #e5e6ec;
  border-radius: 8px;
  background: #ffffff;
  color: #101114;
  font-size: 14px;
  outline: 2px solid transparent;
  outline-offset: 2px;
}

.input:focus {
  border-color: #5741d8;
}
```

#### Email Capture

- Input curto.
- CTA ao lado no desktop.
- Empilhado no mobile.
- Usar placeholder direto e simples.

### Badges

#### Product Badge

```css
.badge-product {
  display: inline-flex;
  align-items: center;
  gap: 4px;
  min-height: 22px;
  padding: 4px 8px;
  border-radius: 6px;
  background: rgba(133, 91, 251, 0.16);
  color: #7132f5;
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 0.5px;
  text-transform: uppercase;
}
```

#### Success Badge

```css
.badge-success {
  display: inline-flex;
  align-items: center;
  padding: 4px 8px;
  border-radius: 6px;
  background: rgba(20, 158, 97, 0.16);
  color: #026b3f;
  font-size: 12px;
  font-weight: 600;
}
```

### Market Table

#### Estrutura

- Card branco arredondado.
- Abas no topo.
- Linhas com ícone, nome do ativo, preço, variação e capitalização.
- Valores positivos em verde.
- Valores negativos em vermelho.
- Link inferior para ver mais mercados.

#### Tokens

```css
.market-table {
  width: 100%;
  max-width: 720px;
  margin: 0 auto;
  border: 1px solid #dedee5;
  border-radius: 12px;
  background: #ffffff;
  overflow: hidden;
}

.market-row {
  display: grid;
  grid-template-columns: 1.4fr 1fr 1fr 1fr;
  align-items: center;
  gap: 16px;
  padding: 16px 24px;
  border-bottom: 1px solid #f4f4f7;
  font-size: 14px;
}

.market-change.is-positive {
  color: #149e61;
}

.market-change.is-negative {
  color: #e65353;
}
```

### Market Tabs

```css
.market-tabs {
  display: inline-flex;
  gap: 8px;
  padding: 4px;
  border-radius: 9999px;
  background: #ffffff;
}

.market-tab {
  padding: 8px 14px;
  border-radius: 9999px;
  color: #686b82;
  font-size: 14px;
  font-weight: 500;
}

.market-tab.is-active {
  background: #f4f4f7;
  color: #101114;
}
```

### Logo Strip

#### Estrutura

- Título pequeno acima ou abaixo.
- Logos em preto ou tons neutros.
- Espaçamento amplo.
- Baixo contraste para não competir com os cards.

```css
.logo-strip {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 32px;
  padding: 40px 24px;
  color: #101114;
}
```

### CTA Section

#### Estrutura

- Fundo claro.
- Ícone ou mascote central.
- Título grande.
- Texto curto.
- CTA roxo.
- Conteúdo centralizado.

```css
.cta-section {
  padding: 80px 24px;
  background: #f7f5fa;
  text-align: center;
}

.cta-title {
  font-size: 40px;
  line-height: 1.16;
  letter-spacing: -1.4px;
  color: #101114;
}
```

### Footer

#### Estrutura

- Fundo branco.
- Coluna de marca e CTA à esquerda.
- Grupos de links à direita.
- Tipografia pequena.
- Espaçamento denso, mas organizado.

```css
.footer {
  padding: 64px 32px;
  background: #ffffff;
  color: #101114;
}

.footer-grid {
  display: grid;
  grid-template-columns: 1.2fr repeat(4, 1fr);
  gap: 40px;
}

.footer-title {
  font-size: 14px;
  font-weight: 700;
}

.footer-link {
  color: #686b82;
  font-size: 13px;
  line-height: 1.7;
}
```

## Page Sections

### 1. Header Navigation

- Logo Kraken.
- Links: Produtos, Recursos, Preços, NFT, Institucional, Aprender.
- Ações: idioma, login, criar conta.
- CTA roxo de alta visibilidade.

### 2. Hero

- Título: controlo financeiro.
- Subtítulo sobre cripto, ações, futuros e ativos.
- Campo de e-mail.
- CTA principal.
- Métricas de confiança.

### 3. Trading Platform Feature

- Card escuro em largura total.
- Badge pequeno.
- Título sobre negociação avançada.
- CTA compacto.
- Imagem de interface de trading.

### 4. Mobile App Feature

- Card preto.
- Título sobre cripto e ações sem complicação.
- Mockups de telemóvel.
- Gradiente radial subtil.

### 5. Pro Feature

- Card roxo profundo.
- Título sobre acesso reinventado.
- Objeto 3D metálico.
- CTA central.

### 6. Institutional Feature

- Card azul-roxo escuro.
- Título institucional.
- Visual 3D abstrato.
- CTA de contacto.

### 7. Global Money Feature

- Card escuro com tom vermelho/marrom.
- Cartões físicos ou digitais.
- Texto sobre aplicativo global de dinheiro.
- CTA branco.

### 8. Two Column Feature Cards

- Card de agente ou automação.
- Card sobre alavancagem.
- Layout em duas colunas no desktop.

### 9. Social Proof

- Logos ou selos de presença social.
- Baixa densidade visual.

### 10. Market Explorer

- Título central.
- Abas de mercado.
- Tabela com ativos.
- Link para explorar todos os mercados.

### 11. Final CTA

- Mascote ou ícone pequeno.
- Título “Faça sua primeira jogada”.
- Texto curto.
- Botão primário roxo.

### 12. Footer

- Mensagem institucional.
- Botões de download de apps.
- Links por categoria.
- Avisos legais em texto pequeno.

## Interaction States

### Hover

- Botões roxos escurecem para `#5741D8`.
- Links roxos podem sublinhar ou reduzir opacidade.
- Cards podem subir `-2px` com sombra suave.
- Market rows podem usar fundo `#F7F5FA`.

### Focus

- Usar outline visível em roxo.
- Inputs com borda `#5741D8`.
- Botões com anel `rgba(113, 50, 245, 0.32)`.

### Disabled

- Fundo `#E5E6EC`.
- Texto `#9497A9`.
- Sem sombra.
- Cursor default.

## Accessibility

- Garantir contraste mínimo de 4.5:1 para texto.
- Não usar apenas cor para indicar ganhos ou perdas.
- Tabelas devem ter cabeçalhos claros.
- Botões precisam de texto descritivo.
- Cards clicáveis devem ter foco visível.
- Imagens financeiras devem ter alt text claro.
- Componentes interativos devem funcionar por teclado.

## Responsive Behavior

### Breakpoints

| Token | Valor |
|---|---:|
| `breakpoint.xs` | `375px` |
| `breakpoint.sm` | `640px` |
| `breakpoint.md` | `768px` |
| `breakpoint.lg` | `1024px` |
| `breakpoint.xl` | `1280px` |
| `breakpoint.2xl` | `1536px` |

### Mobile

- Header simplificado com menu.
- Hero com CTA empilhado.
- Cards grandes com padding reduzido.
- Split grid vira coluna única.
- Tabela de mercados pode ter scroll horizontal.
- Footer vira lista em coluna.

### Desktop

- Layout máximo entre `1180px` e `1280px`.
- Cards largos com altura imersiva.
- Tabelas centralizadas.
- Footer em múltiplas colunas.

## AI Usage Guidelines

### Prompt base

Crie uma interface inspirada na Kraken, com fundo claro, roxo intenso como cor principal, tipografia limpa, cards grandes escuros, cantos arredondados, tabelas financeiras e visual premium de exchange cripto.

### Prompt para hero

Crie um hero fintech com fundo `#F7F5FA`, título central grande, subtítulo curto, campo de e-mail, botão roxo `#7132F5`, métricas de confiança abaixo e espaçamento amplo.

### Prompt para cards

Crie cards grandes com fundo preto ou roxo profundo, raio de 16px, texto branco centralizado, badge pequeno no topo, CTA compacto e imagem/mockup financeiro na parte inferior.

### Prompt para tabela

Crie uma tabela de mercados com card branco, raio de 12px, abas em formato pill, linhas com ícone do ativo, preço, variação em verde/vermelho e link roxo no rodapé.

## Do

- Usar roxo como assinatura principal.
- Alternar secções claras com cards escuros.
- Usar cards grandes e visuais.
- Manter CTAs curtos e diretos.
- Trabalhar confiança com métricas e tabela.
- Usar dados financeiros com boa hierarquia.
- Usar radius consistente em botões, cards, inputs e tabelas.
- Usar imagens ou objetos 3D para reforçar tecnologia e premium.

## Don't

- Não usar excesso de cores fora da paleta.
- Não transformar todos os botões em pill.
- Não criar interfaces muito coloridas ou infantis.
- Não usar gradientes claros sem contraste.
- Não esconder dados financeiros importantes.
- Não usar textos longos dentro dos cards principais.
- Não remover estados de foco.
- Não depender apenas de cor para comunicar variação positiva ou negativa.

## Component Checklist

- Header completo
- Hero com input e CTA
- Métricas de confiança
- Cards grandes de feature
- Grid de cards secundários
- Botões primário, secundário, subtle e white
- Inputs e captura de e-mail
- Badges de produto e status
- Tabela de mercados
- Abas de mercado
- Logo strip
- CTA final
- Footer completo
- Estados de hover, focus e disabled
- Responsividade mobile e desktop
- Regras de acessibilidade

## Final Notes

Este arquivo deve orientar a criação de páginas, componentes e previews inspirados no universo visual da Kraken, preservando uma linguagem premium, tecnológica, financeira e confiável.
