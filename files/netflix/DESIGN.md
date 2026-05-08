---
title: "Netflix Inspired Design System"
description: "Design system inspirado na Netflix para interfaces de streaming, entretenimento e catálogos visuais em design.md."
version: "1.0.0"
author: "Camaraux"
language: "pt-BR"
tags:
  - design-system
  - design-md
  - streaming
  - entretenimento
  - netflix
  - ui
  - ux
source_url: "https://www.netflix.com/browse"
inspiration: "Netflix"
license: "Uso educacional e referência visual. Não afiliado à Netflix."
---

# Netflix Inspired Design System

## Overview

Design system inspirado na experiência visual da Netflix, focado em interfaces escuras, consumo audiovisual, navegação por catálogo, cards cinematográficos, hierarquia editorial forte e ações rápidas de reprodução.

Use este design.md para criar produtos digitais com estética premium de streaming, páginas de catálogo, plataformas de vídeo, dashboards de conteúdo, hubs de mídia, apps de entretenimento e experiências de descoberta visual.

## Brand Personality

- Cinemático
- Imersivo
- Direto
- Premium
- Editorial
- Escuro
- Visual
- Rápido
- Personalizado
- Focado em conteúdo

## Visual Direction

A interface deve parecer uma sala de cinema digital: fundo escuro, conteúdo em primeiro plano, forte contraste, imagens grandes, cards horizontais e chamadas de ação simples. A navegação deve ser discreta, deixando filmes, séries, capas e trailers dominarem a experiência.

## Design Principles

### Content first

O conteúdo visual deve ser o elemento mais importante da interface. Menus, filtros e controles devem apoiar a navegação sem competir com capas, thumbnails e banners.

### Dark immersion

Use fundos escuros como base principal. O preto e os tons de cinza criam foco, reduzem ruído visual e aumentam a sensação de entretenimento premium.

### Strong hierarchy

Use títulos grandes, descrições curtas, etiquetas de categoria e CTAs evidentes. O utilizador precisa entender rapidamente o que assistir e onde clicar.

### Horizontal discovery

Organize conteúdos em fileiras horizontais, carrosséis e coleções editoriais. A sensação deve ser de navegação contínua por prateleiras de conteúdo.

### Motion with purpose

Animações devem reforçar foco, seleção, preview e transição. Evite movimentos decorativos sem função clara.

## Color System

### Primary Colors

```css
--color-netflix-red: #E50914;
--color-netflix-red-dark: #B9090B;
--color-netflix-red-deep: #B00500;
--color-netflix-red-bright: #FF0A16;
```

### Background Colors

```css
--color-background-primary: #141414;
--color-background-secondary: #181818;
--color-background-deep: #000000;
--color-background-elevated: #1A1A1A;
--color-background-card: #181818;
--color-background-overlay: rgba(0, 0, 0, 0.70);
--color-background-scrim: rgba(0, 0, 0, 0.55);
```

### Text Colors

```css
--color-text-primary: #FFFFFF;
--color-text-secondary: #E5E5E5;
--color-text-muted: #B3B3B3;
--color-text-subtle: #999999;
--color-text-disabled: #666666;
```

### Border Colors

```css
--color-border-subtle: #333333;
--color-border-muted: #4D4D4D;
--color-border-light: #666666;
--color-border-focus: #FFFFFF;
```

### Feedback Colors

```css
--color-success: #5FA53F;
--color-info: #0080FF;
--color-warning: #FFA00A;
--color-error: #E50914;
```

## Typography

### Font Family

Use Netflix Sans como referência principal. Quando não estiver disponível, use fontes de sistema com boa leitura em interfaces digitais.

```css
--font-primary: "Netflix Sans", "Helvetica Neue", "Segoe UI", Roboto, Ubuntu, sans-serif;
--font-fallback: Arial, Helvetica, sans-serif;
```

### Type Scale

```css
--font-size-display: 64px;
--font-size-hero: 48px;
--font-size-title-xl: 32px;
--font-size-title-lg: 24px;
--font-size-title-md: 20px;
--font-size-body-lg: 18px;
--font-size-body: 16px;
--font-size-body-sm: 14px;
--font-size-caption: 12px;
```

### Font Weights

```css
--font-weight-regular: 400;
--font-weight-medium: 500;
--font-weight-bold: 700;
```

### Typography Usage

- Use títulos grandes para hero banners e destaques editoriais.
- Use texto curto em cards e descrições.
- Evite parágrafos longos em áreas de catálogo.
- Use peso bold para títulos e labels importantes.
- Use texto secundário para metadados, géneros, duração e ano.

## Spacing System

```css
--space-0: 0;
--space-1: 4px;
--space-2: 8px;
--space-3: 12px;
--space-4: 16px;
--space-5: 24px;
--space-6: 32px;
--space-7: 48px;
--space-8: 64px;
--space-9: 96px;
```

### Layout Spacing

- Margem lateral desktop: 60px.
- Margem lateral tablet: 40px.
- Margem lateral mobile: 20px.
- Espaçamento entre fileiras: 32px a 48px.
- Espaçamento entre cards: 8px a 12px.
- Espaçamento interno de overlays: 16px a 24px.

## Grid and Layout

### Page Structure

```text
Header fixo ou transparente
Hero banner cinematográfico
Fileiras de conteúdo horizontal
Cards de títulos
Área de detalhes em overlay
Footer discreto
```

### Content Rows

- Use fileiras horizontais com título de seção.
- Cards devem ter proporção visual consistente.
- Carrosséis devem sugerir continuidade lateral.
- Evite grelhas muito estáticas quando o objetivo for exploração.

### Breakpoints

```css
--breakpoint-mobile: 480px;
--breakpoint-tablet: 768px;
--breakpoint-desktop: 1024px;
--breakpoint-wide: 1440px;
```

## Components

### Header

O header deve ser simples, escuro e funcional.

#### Structure

- Logo à esquerda.
- Links de navegação principais.
- Pesquisa, notificações e perfil à direita.
- Fundo transparente sobre hero ou fundo escuro sólido ao rolar.

#### Style

```css
.header {
  height: 68px;
  padding: 0 60px;
  background: linear-gradient(to bottom, rgba(0,0,0,.70), rgba(0,0,0,0));
  color: #FFFFFF;
}
```

### Hero Banner

Hero deve ter imagem ou vídeo de fundo, título grande, descrição curta e CTAs principais.

#### Content

- Título do conteúdo.
- Descrição curta.
- Metadados opcionais.
- Botão primário de reprodução.
- Botão secundário de informações.

#### Style

```css
.hero {
  min-height: 70vh;
  padding: 160px 60px 80px;
  background-color: #141414;
  color: #FFFFFF;
}

.hero::after {
  content: "";
  background: linear-gradient(to top, #141414 0%, rgba(20,20,20,0) 60%);
}
```

### Buttons

#### Primary Button

Use para ações principais como assistir, reproduzir ou começar.

```css
.button-primary {
  background: #FFFFFF;
  color: #000000;
  border-radius: 4px;
  padding: 10px 24px;
  font-weight: 700;
}

.button-primary:hover {
  background: rgba(255,255,255,.75);
}
```

#### Secondary Button

Use para informações, detalhes ou ações complementares.

```css
.button-secondary {
  background: rgba(109,109,110,.70);
  color: #FFFFFF;
  border-radius: 4px;
  padding: 10px 24px;
  font-weight: 700;
}

.button-secondary:hover {
  background: rgba(109,109,110,.45);
}
```

#### Icon Button

Use para adicionar à lista, avaliar, expandir, fechar ou navegar no carrossel.

```css
.button-icon {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  border: 2px solid rgba(255,255,255,.50);
  background: rgba(42,42,42,.60);
  color: #FFFFFF;
}
```

### Content Card

Cards são o principal componente do catálogo.

#### Style

```css
.card-content {
  background: #181818;
  border-radius: 4px;
  overflow: hidden;
  transition: transform 180ms ease, box-shadow 180ms ease;
}

.card-content:hover {
  transform: scale(1.06);
  box-shadow: 0 12px 32px rgba(0,0,0,.60);
  z-index: 2;
}
```

#### Usage

- Use imagem de capa ou thumbnail como área dominante.
- Título pode aparecer em overlay ou abaixo da imagem.
- Exiba ações rápidas no hover.
- Evite bordas coloridas em excesso.

### Card Metadata

```text
Match percentage
Ano
Classificação indicativa
Duração
Género
```

Use metadados curtos e discretos. O foco deve continuar na capa e no título.

### Carousel Row

```css
.carousel-row {
  display: flex;
  gap: 8px;
  overflow-x: auto;
  padding: 0 60px;
}
```

#### Behaviour

- Navegação lateral com setas.
- Cards parcialmente visíveis nas extremidades.
- Título da seção alinhado à margem do conteúdo.
- Movimento suave, sem pausas bruscas.

### Modal Details

Use modal escuro para apresentar detalhes de um filme, série ou episódio.

```css
.modal-details {
  background: #181818;
  color: #FFFFFF;
  border-radius: 8px;
  box-shadow: 0 24px 80px rgba(0,0,0,.85);
}
```

#### Structure

- Imagem ou vídeo no topo.
- Gradiente escuro sobre a mídia.
- Título e CTAs.
- Sinopse curta.
- Metadados.
- Lista de episódios ou conteúdos relacionados.

### Search

A pesquisa deve ser discreta e rápida.

```css
.search-input {
  background: rgba(0,0,0,.75);
  border: 1px solid #FFFFFF;
  color: #FFFFFF;
  height: 36px;
  padding: 0 12px;
}
```

### Profile Avatar

- Use avatares simples em formato quadrado com cantos suaves.
- Tamanho recomendado: 32px x 32px.
- Menu de perfil deve usar fundo escuro e borda sutil.

### Badges

```css
.badge-rating {
  border: 1px solid rgba(255,255,255,.40);
  color: #B3B3B3;
  padding: 2px 6px;
  font-size: 12px;
}
```

Use badges para classificação indicativa, qualidade de vídeo, novo episódio ou conteúdo em destaque.

## Imagery

### Image Style

- Fotografia cinematográfica.
- Alto contraste.
- Rostos, cenas e composições dramáticas.
- Thumbnails com atmosfera narrativa.
- Fundos escuros ou com profundidade.
- Evite imagens genéricas ou muito claras.

### Aspect Ratios

```css
--ratio-card-landscape: 16 / 9;
--ratio-card-poster: 2 / 3;
--ratio-hero: 16 / 9;
--ratio-avatar: 1 / 1;
```

### Gradients

Use gradientes para garantir leitura sobre imagens.

```css
--gradient-hero-bottom: linear-gradient(to top, #141414 0%, rgba(20,20,20,0) 65%);
--gradient-hero-side: linear-gradient(to right, rgba(0,0,0,.85) 0%, rgba(0,0,0,.30) 45%, rgba(0,0,0,0) 100%);
--gradient-card-overlay: linear-gradient(to top, rgba(0,0,0,.85), rgba(0,0,0,0));
```

## Motion

### Timing

```css
--motion-fast: 120ms;
--motion-base: 180ms;
--motion-slow: 300ms;
--motion-ease: cubic-bezier(.4, 0, .2, 1);
```

### Animation Rules

- Hover de card deve ampliar levemente.
- Modais devem surgir com fade e scale suave.
- Carrosséis devem mover de forma fluida.
- Evite transições lentas em ações principais.
- Use motion para indicar foco, não para decorar.

## Accessibility

### Contrast

- Texto principal branco sobre fundo escuro.
- Texto secundário nunca abaixo de contraste aceitável.
- Botões devem ter estados visíveis de foco e hover.

### Focus

```css
:focus-visible {
  outline: 2px solid #FFFFFF;
  outline-offset: 2px;
}
```

### Keyboard Navigation

- Todos os cards devem ser acessíveis por teclado.
- Carrosséis devem permitir navegação sem rato.
- Modais devem prender foco enquanto abertos.
- Botões de fechar devem ter label acessível.

### Alt Text

- Descreva o conteúdo visual do título ou thumbnail.
- Não comece alt text com “imagem de” ou “foto de”.
- Use descrições curtas e úteis.

## Voice and Copy

### Tone

- Direto
- Curto
- Confiante
- Editorial
- Orientado à ação

### CTA Examples

- Assistir
- Reproduzir
- Mais informações
- Adicionar à lista
- Continuar assistindo
- Ver detalhes
- Explorar catálogo

### Microcopy Rules

- Use frases curtas.
- Evite explicações longas.
- Priorize ação imediata.
- Em estados vazios, ajude o utilizador a encontrar conteúdo.

## Page Templates

### Browse Page

```text
Header
Hero em destaque
Continuar assistindo
Minha lista
Populares agora
Lançamentos
Categorias editoriais
Footer
```

### Title Detail Page

```text
Hero com imagem/vídeo
Título
CTAs
Sinopse
Metadados
Episódios
Títulos semelhantes
```

### Search Results Page

```text
Header com campo ativo
Termo pesquisado
Resultados em grid/carrossel
Sugestões relacionadas
Estado vazio quando necessário
```

### Profile Selection

```text
Fundo preto
Título central
Lista de perfis
Botão gerir perfis
```

## Do

- Use fundo escuro como base.
- Dê protagonismo às imagens.
- Use vermelho apenas para marca, alertas e ênfase.
- Crie hierarquia clara entre destaque, seção e card.
- Mantenha CTAs simples e visíveis.
- Use cards com proporções consistentes.

## Don't

- Não use fundos claros como base principal.
- Não sobrecarregue cards com texto.
- Não use muitas cores fora da paleta.
- Não aplique bordas decorativas pesadas.
- Não esconda ações principais.
- Não use animações lentas demais.

## CSS Token Export

```css
:root {
  --color-brand-primary: #E50914;
  --color-brand-primary-dark: #B9090B;
  --color-bg-primary: #141414;
  --color-bg-secondary: #181818;
  --color-bg-black: #000000;
  --color-text-primary: #FFFFFF;
  --color-text-secondary: #E5E5E5;
  --color-text-muted: #B3B3B3;
  --color-border: #333333;
  --font-primary: "Netflix Sans", "Helvetica Neue", "Segoe UI", Roboto, Ubuntu, sans-serif;
  --radius-sm: 4px;
  --radius-md: 8px;
  --shadow-card-hover: 0 12px 32px rgba(0,0,0,.60);
  --shadow-modal: 0 24px 80px rgba(0,0,0,.85);
  --motion-fast: 120ms;
  --motion-base: 180ms;
  --motion-ease: cubic-bezier(.4, 0, .2, 1);
}
```

## Implementation Notes

Este arquivo é uma referência de design inspirada na linguagem visual da Netflix. Use como base para interfaces próprias de streaming, entretenimento e catálogo, sem copiar marcas, logótipos, conteúdos protegidos ou elementos proprietários.
