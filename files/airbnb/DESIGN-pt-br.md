---
version: alpha
name: Airbnb
description: Um marketplace acolhedor e generoso para o consumidor, ancorado em um fundo branco limpo e na identidade visual Airbnb Rausch (#ff385c), a principal força da marca presente em todos os CTAs principais, botões de busca e indicadores de avaliação. A tipografia utiliza Airbnb Cereal VF com pesos moderados — os títulos variam entre 22–28px utilizando pesos 500/600, em vez dos pesados 700+ comuns em fintechs e sistemas corporativos; a marca prioriza fotografia e amplo espaço em branco acima de impacto tipográfico exagerado. Três categorias de produto (Casas, Experiências e Serviços) aparecem na navegação superior com ícones ilustrados manualmente de 32px e selos "NOVO", sinalizando expansão do marketplace em vez de excesso de funcionalidades. As barras de busca em formato pílula (`{rounded.full}`), os cartões de propriedades com cantos suavemente arredondados (`{rounded.lg}` ~14px) e os botões com raio de 32px transmitem sensação amigável e humana — não existe nenhum canto rígido além da própria grade estrutural da interface.

colors:
  primary: "#ff385c"
  primary-active: "#e00b41"
  primary-disabled: "#ffd1da"
  primary-error-text: "#c13515"
  primary-error-text-hover: "#b32505"
  luxe: "#460479"
  plus: "#92174d"
  ink: "#222222"
  body: "#3f3f3f"
  muted: "#6a6a6a"
  muted-soft: "#929292"
  hairline: "#dddddd"
  hairline-soft: "#ebebeb"
  border-strong: "#c1c1c1"
  canvas: "#ffffff"
  surface-soft: "#f7f7f7"
  surface-card: "#ffffff"
  surface-strong: "#f2f2f2"
  on-primary: "#ffffff"
  on-dark: "#ffffff"
  legal-link: "#428bff"
  star-rating: "#222222"
  scrim: "#000000"

typography:
  display-xl:
    fontFamily: "'Airbnb Cereal VF', Circular, -apple-system, system-ui, Roboto, 'Helvetica Neue', sans-serif"
    fontSize: 28px
    fontWeight: 700
    lineHeight: 1.43
    letterSpacing: 0
  display-lg:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 22px
    fontWeight: 500
    lineHeight: 1.18
    letterSpacing: -0.44px
  display-md:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 21px
    fontWeight: 700
    lineHeight: 1.43
    letterSpacing: 0
  display-sm:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 20px
    fontWeight: 600
    lineHeight: 1.20
    letterSpacing: -0.18px
  title-md:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: 0
  title-sm:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: 0
  rating-display:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 64px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -1px
  body-md:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-sm:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: 0
  caption:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.29
    letterSpacing: 0
  caption-sm:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.23
    letterSpacing: 0
  badge:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 11px
    fontWeight: 600
    lineHeight: 1.18
    letterSpacing: 0
  micro-label:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 12px
    fontWeight: 700
    lineHeight: 1.33
    letterSpacing: 0
  uppercase-tag:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 8px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0.32px
    textTransform: uppercase
  button-md:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: 0
  button-sm:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.29
    letterSpacing: 0
  link:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: 0
  nav-link:
    fontFamily: "'Airbnb Cereal VF', Circular, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: 0

rounded:
  none: 0px
  xs: 4px
  sm: 8px
  md: 14px
  lg: 20px
  xl: 32px
  full: 9999px

spacing:
  xxs: 2px
  xs: 4px
  sm: 8px
  md: 12px
  base: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 64px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-md}"
    rounded: "{rounded.sm}"
    padding: 14px 24px
    height: 48px
  button-primary-active:
    backgroundColor: "{colors.primary-active}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.sm}"
  button-primary-disabled:
    backgroundColor: "{colors.primary-disabled}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.sm}"
  button-secondary:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.button-md}"
    rounded: "{rounded.sm}"
    padding: 13px 23px
    height: 48px
  button-tertiary-text:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button-md}"
  button-pill-rausch:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-sm}"
    rounded: "{rounded.full}"
    padding: 10px 20px
  search-orb:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.full}"
    height: 48px
  icon-button-circle:
    backgroundColor: "{colors.surface-strong}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    height: 32px
  icon-button-outline:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    height: 40px
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 80px
  product-tab-active:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.none}"
  product-tab-inactive:
    backgroundColor: transparent
    textColor: "{colors.muted}"
    typography: "{typography.nav-link}"
  search-bar-pill:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.full}"
    padding: 14px 24px
    height: 64px
  search-field-segment:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.caption}"
    padding: 8px 24px
  category-strip:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.muted}"
    typography: "{typography.button-sm}"
  category-tab-active:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button-sm}"
    rounded: "{rounded.none}"
  property-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
  property-card-photo:
    rounded: "{rounded.md}"
  experience-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.title-md}"
    rounded: "{rounded.md}"
  city-link-block:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.title-sm}"
  rating-display-card:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.rating-display}"
  guest-favorite-badge:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.badge}"
    rounded: "{rounded.full}"
    padding: 4px 10px
  new-tag:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.uppercase-tag}"
    rounded: "{rounded.full}"
    padding: 2px 6px
  amenity-row:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    padding: 12px 0
  reviews-card:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
  host-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 24px
  reservation-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: 24px
  date-picker-day:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.full}"
  date-picker-day-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.full}"
  text-input:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.sm}"
    padding: 14px 12px
    height: 56px
  footer-light:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    padding: 48px 80px
  footer-link:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
  legal-band:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.muted}"
    typography: "{typography.caption-sm}"
---
## Visão Geral

O Airbnb é o exemplo clássico de um marketplace de consumo generoso e guiado por fotografia. O canvas base é **branco puro** (`{colors.canvas}` — #ffffff), com texto quase preto profundo (`{colors.ink}` — #222222) para títulos e corpo, além de uma única força de marca: **Rausch** (`{colors.primary}` — #ff385c). Essa cor sustenta todos os CTAs principais, o botão circular de busca, o estado de favorito do coração e os links de marca no conteúdo. Não existe uma cor secundária de marca no marketing principal — o **roxo Luxe** (`{colors.luxe}` — #460479) e o **magenta Plus** (`{colors.plus}` — #92174d) são acentos de submarca e aparecem apenas em contextos Airbnb Luxe / Plus.

A tipografia utiliza **Airbnb Cereal VF**, uma fonte variável personalizada licenciada pelo Airbnb, com **Circular** como fallback histórico interno e uma pilha de fontes do sistema abaixo. A Cereal usa pesos moderados — títulos de destaque aparecem entre 22–28px com peso 500–600, e não com os pesos 700+ comuns em sistemas financeiros ou corporativos. O h1 da página inicial (“Inspiration for future getaways”) usa apenas 28px / 700, o que pareceria pequeno em uma página SaaS típica; aqui funciona porque o layout se apoia em fotografia, colagens de cidades e cards de propriedades para criar peso visual, em vez de depender de força tipográfica.

A linguagem de forma é **suave**. Botões usam raio de 8px (`{rounded.sm}`), cards de propriedades ficam em torno de 14px (`{rounded.md}`), a barra de busca é totalmente arredondada em formato pílula (`{rounded.full}`), corações de favoritos e botões de busca são circulares (`{rounded.full}`), e os cantos da faixa de categorias usam 32px (`{rounded.xl}`). Praticamente não há cantos rígidos em lugar nenhum, exceto na própria grade estrutural da página — todos os elementos interativos são arredondados.

**Características Principais:**
- Cor de destaque única: `{colors.primary}` (#ff385c — “Rausch”) sustenta todos os CTAs principais, o botão de busca, o estado de favorito do coração e a marca. É usada com moderação — a maior parte das páginas é composta por 90% branco + texto escuro, com um ou dois momentos em Rausch.
- Tipografia variável personalizada: `Airbnb Cereal VF`. Pesos de destaque ficam entre 500–700; corpo em 400. O peso moderado é intencional — o sistema confia na fotografia para criar presença visual.
- Navegação superior com três produtos: Casas, Experiências e Serviços — cada um com ícone ilustrado à mão de 32px e selos “NOVO” (`{component.new-tag}`) nos dois produtos mais recentes. A aba ativa usa uma linha inferior (`{component.product-tab-active}`).
- Barra de busca global em formato pílula: superfície branca, totalmente arredondada (`{rounded.full}`), dividida por linhas de 1px em segmentos Onde / Quando / Quem, encerrada por um botão circular Rausch de busca (`{component.search-orb}`).
- Cards de propriedades priorizam fotografia: retângulos com proporção visual forte e cantos em `{rounded.md}`, carrossel de imagens, selo flutuante “Preferido dos hóspedes” no canto superior esquerdo, ícone de coração no canto superior direito e 4–5 linhas de metadados abaixo.
- Dropdowns editoriais, como rodapé e seletor de idioma, são colunas de texto limpas sobre canvas branco — sem superfície de card e sem sombra.
- O design system limita elevação a um único nível de sombra (`box-shadow: rgba(0,0,0,0.02) 0 0 0 1px, rgba(0,0,0,0.04) 0 2px 6px, rgba(0,0,0,0.1) 0 4px 8px`) — usado em cards elevados no hover e dropdowns de busca/conta.
- Sistema de espaçamento baseado em 8px, com seções principais em `{spacing.section}` (64px) — generoso, mas não tão arejado quanto uma revista editorial; a densidade de marketplace pede mais cards por rolagem.

## Cores

### Marca e Acento
- **Rausch** (`{colors.primary}` — #ff385c): A cor principal da marca. Usada em fundos de CTAs principais (“Reservar”, “Continuar”), no botão de busca, no estado salvo dos cards de propriedade e em links de marca no conteúdo. É a cor mais reconhecível no contexto de viagens de consumo.
- **Rausch Ativo** (`{colors.primary-active}` — #e00b41): Variante de pressionamento / clique — levemente mais saturada. Usada em `{component.button-primary-active}`.
- **Rausch Desativado** (`{colors.primary-disabled}` — #ffd1da): Tom claro usado em CTAs desativados.
- **Roxo Luxe** (`{colors.luxe}` — #460479): Acento de submarca para Airbnb Luxe. Aparece apenas em superfícies Luxe — nunca no marketing principal.
- **Magenta Plus** (`{colors.plus}` — #92174d): Acento de submarca para Airbnb Plus. Segue o mesmo escopo do Luxe — uso restrito ao subproduto.

### Superfícies
- **Canvas** (`{colors.canvas}` — #ffffff): Base padrão de todas as páginas públicas. O Airbnb não possui modo escuro na web pública.
- **Superfície Suave** (`{colors.surface-soft}` — #f7f7f7): Preenchimento mais claro — usado em campos desativados, fundos de hover em subnavegação e faixa de filtros de busca.
- **Superfície Forte** (`{colors.surface-strong}` — #f2f2f2): Preenchimento levemente mais intenso — usado em botões circulares de ícone, como seta de voltar e botões da barra de listagem.

### Linhas e Bordas
- **Linha** (`{colors.hairline}` — #dddddd): Tom padrão de borda de 1px — divisores da barra de busca, separadores de tabela, divisões de colunas do rodapé e bordas de cards.
- **Linha Suave** (`{colors.hairline-soft}` — #ebebeb): Divisor mais claro usado em separadores de conteúdos editoriais longos.
- **Borda Forte** (`{colors.border-strong}` — #c1c1c1): Traço mais pesado usado em botões outline desativados e contornos de inputs após foco.

### Texto
- **Ink** (`{colors.ink}` — #222222): Cor dominante para texto em superfícies claras. Títulos, parágrafos, links principais da navegação e boa parte dos links inline. Nunca é preto puro.
- **Corpo** (`{colors.body}` — #3f3f3f): Cor secundária para texto corrido em reviews longos e descrições de comodidades, onde o ink pareceria pesado demais.
- **Suave** (`{colors.muted}` — #6a6a6a): Subtítulos em blocos de cidades (“Cottage rentals”, “Villa rentals”), abas inativas, subtítulos de categorias do rodapé e links “Ver tudo”.
- **Suave Claro** (`{colors.muted-soft}` — #929292): Texto de links desativados. Usado com muita moderação.
- **Avaliação por Estrela** (`{colors.star-rating}` — #222222): Mesmo token de ink — o ícone de estrela e números de avaliação como “4.81” aparecem em ink, não em amarelo/dourado. Essa é uma escolha deliberada da marca, já que estrelas amarelas podem parecer baratas no contexto de viagens.
- **Sobre Primário** (`{colors.on-primary}` — #ffffff): Texto branco sobre CTAs Rausch.

### Semântica
- **Erro** (`{colors.primary-error-text}` — #c13515): Texto de erro inline para validação de formulário. Diferente do Rausch — vermelho mais escuro e saturado.
- **Erro Hover** (`{colors.primary-error-text-hover}` — #b32505): Escurece no hover de links.
- **Azul de Link Legal** (`{colors.legal-link}` — #428bff): Links inline em textos legais, como Privacidade e Termos. Usado apenas na faixa legal.

### Scrim
- **Scrim** (`{colors.scrim}` — #000000 com 50% de opacidade): Tom global de fundo para modais — seletor de datas, login e seletor de idioma. Armazenado como hex base; a opacidade é aplicada na renderização.

## Tipografia

### Família Tipográfica
O sistema usa **Airbnb Cereal VF** para tudo — títulos, corpo, navegação, legendas e microcopy. Os fallbacks seguem `Circular, -apple-system, system-ui, Roboto, "Helvetica Neue", sans-serif`. **Circular** é a fonte histórica interna mantida como primeiro fallback não variável; a pilha do sistema funciona como apoio.

Não existe uma família separada para display. A fonte variável sustenta toda a escala.

### Hierarquia

| Token | Tamanho | Peso | Altura de Linha | Espaçamento entre Letras | Uso |
|---|---|---|---|---|---|
| `{typography.rating-display}` | 64px | 700 | 1.1 | -1px | Exibição de avaliação na página de anúncio (“4.81”) |
| `{typography.display-xl}` | 28px | 700 | 1.43 | 0 | H1 da página inicial (“Inspiration for future getaways”) |
| `{typography.display-lg}` | 22px | 500 | 1.18 | -0.44px | H1 do detalhe do anúncio (“Close to Fethiye Aliyah Bali Beach…”) |
| `{typography.display-md}` | 21px | 700 | 1.43 | 0 | Títulos de seção no detalhe do anúncio (“What this place offers”) |
| `{typography.display-sm}` | 20px | 600 | 1.20 | -0.18px | Títulos de subseção (“Things to know”) |
| `{typography.title-md}` | 16px | 600 | 1.25 | 0 | Títulos de blocos de cidade (“Wilmington”, “Athens”) |
| `{typography.title-sm}` | 16px | 500 | 1.25 | 0 | Títulos de colunas do rodapé (“Support”, “Hosting”, “Airbnb”) |
| `{typography.body-md}` | 16px | 400 | 1.5 | 0 | Texto corrido padrão em páginas de anúncio |
| `{typography.body-sm}` | 14px | 400 | 1.43 | 0 | Metadados de cards, datas, preços e distância |
| `{typography.caption}` | 14px | 500 | 1.29 | 0 | Rótulos dos segmentos da busca (“Where”, “When”, “Who”) |
| `{typography.caption-sm}` | 13px | 400 | 1.23 | 0 | Linha legal do rodapé (“© 2026 Airbnb, Inc.”) |
| `{typography.badge}` | 11px | 600 | 1.18 | 0 | Texto do selo flutuante “Guest favorite” |
| `{typography.micro-label}` | 12px | 700 | 1.33 | 0 | Micro-rótulos de comodidades em cards (“Inline 6”) |
| `{typography.uppercase-tag}` | 8px | 700 | 1.25 | 0.32px (uppercase) | Selo “NEW” nas abas de produto |
| `{typography.button-md}` | 16px | 500 | 1.25 | 0 | Rótulos de botões de CTA principal |
| `{typography.button-sm}` | 14px | 500 | 1.29 | 0 | Rótulos de botões em formato pílula |
| `{typography.link}` | 14px | 400 | 1.43 | 0 | Links inline no corpo do texto |
| `{typography.nav-link}` | 16px | 600 | 1.25 | 0 | Rótulos da navegação superior de produtos |

### Princípios
Os pesos de display permanecem moderados. O h1 da página inicial em 28px / 700 é deliberadamente pequeno — ele fica abaixo da barra de busca para que a fotografia e a grade de links de cidades conduzam a hierarquia visual. O h1 do detalhe do anúncio, em 22px / 500, é ainda mais discreto; o banner fotográfico acima faz o trabalho principal.

O único momento tipograficamente forte em todo o sistema é a **exibição de avaliação** (`{typography.rating-display}` — 64px / 700) nas páginas de anúncio. É o único lugar onde o sistema confia somente na tipografia para criar hierarquia — números de avaliação são um forte sinal de confiança, por isso recebem o tratamento mais chamativo.

### Observação sobre Fontes Substitutas
Se Airbnb Cereal VF e Circular não estiverem disponíveis, **Inter** é o substituto open-source mais próximo. Ajuste a altura de linha dos títulos de display para baixo em aproximadamente 2% para se aproximar da altura de caixa da Cereal; fora isso, as proporções se transferem bem.

## Layout

### Sistema de Espaçamento
- **Unidade base:** 4px, com microetapa de 2px.
- **Tokens:** `{spacing.xxs}` 2px · `{spacing.xs}` 4px · `{spacing.sm}` 8px · `{spacing.md}` 12px · `{spacing.base}` 16px · `{spacing.lg}` 24px · `{spacing.xl}` 32px · `{spacing.xxl}` 48px · `{spacing.section}` 64px.
- **Padding vertical de seção:** `{spacing.section}` (64px) em grandes blocos de página; mais compacto que o marketing SaaS típico (80–96px), porque páginas de marketplace precisam de maior densidade de cards por rolagem.
- **Padding interno de cards:** `{spacing.lg}` (24px) para `{component.host-card}` e `{component.reservation-card}`; `{spacing.base}` (16px) para metadados de `{component.property-card}`; `{spacing.sm}` (8px) para legendas e linhas de data.
- **Gutters:** `{spacing.base}` (16px) entre cards na grade de cidades da página inicial; `{spacing.lg}` (24px) entre colunas do rodapé; `{spacing.xs}` (4px) em divisores densos da faixa de categorias.

### Grade e Container
- **Largura máxima de conteúdo:** cerca de 1280px centralizados na página inicial e em páginas editoriais. Páginas de detalhe de anúncio ficam mais próximas de 1080px para manter o banner fotográfico e a coluna de reserva legíveis.
- **Grade de links de cidade:** 6 colunas no desktop, com cada célula contendo nome da cidade em `{typography.title-md}` e subrótulo de categoria em `{typography.body-sm}` suave.
- **Detalhe do anúncio:** 2 colunas, com corpo/fotos/comodidades à esquerda (~64% de largura) e card de reserva fixo (`{component.reservation-card}`) à direita (~32%).
- **Rodapé:** lista de links em 3 colunas no desktop (Support / Hosting / Airbnb), colapsando para 1 coluna no mobile.

### Filosofia de Espaço em Branco
O sistema oferece 64px de respiro vertical para blocos editoriais, mas comprime grades de cards — cards de propriedades e links de cidade ficam a apenas 16px de distância. O contraste é intencional: a página comunica “hero aberto, marketplace denso abaixo”, reforçando a natureza de marketplace sem sobrecarregar o visitante acima da dobra.

## Elevação

O sistema tem essencialmente **um único nível de sombra**, além do estado plano.

- **Plano, sem sombra:** Corpo, hero, rodapé e todos os blocos editoriais — 95% das superfícies.
- **Elevação de card no hover:** `box-shadow: rgba(0, 0, 0, 0.02) 0 0 0 1px, rgba(0, 0, 0, 0.04) 0 2px 6px 0, rgba(0, 0, 0, 0.1) 0 4px 8px 0` — aplicado a cards de propriedades no hover, à barra de busca em repouso e aos menus suspensos (menu de conta, seletor de idioma, seletor de datas). Essa é a única definição de sombra em todo o sistema.
- **Scrim de modal:** `{colors.scrim}` renderizado com 50% de opacidade — fundo global de modal. Usado em seletores de data, diálogos de login e seletor de idioma.

Não existem níveis progressivos de elevação — o sistema tem uma única sombra ou nenhuma. A profundidade vem da fotografia, da separação branco-sobre-branco das superfícies e do recorte por cantos arredondados, não de sombras em camadas.

## Componentes

### Botões

**`button-primary`** — Preenchimento Rausch, texto branco, raio de 8px, padding de 14×24px, altura de 48px e peso 500. É o CTA mais comum do sistema: “Reserve”, “Continue”, “Search” e ações principais de fluxo de conta.

**`button-primary-active`** — Estado pressionado. O fundo muda para `{colors.primary-active}`. Sem transformações e sem mudança de sombra.

**`button-primary-disabled`** — Tom claro de Rausch em #ffd1da com texto branco. Cursor não permitido.

**`button-secondary`** — Preenchimento branco com texto ink e contorno ink de 1px. Raio de 8px. Usado em “Save”, “Cancel” e CTAs inversos sobre superfícies Rausch.

**`button-tertiary-text`** — Texto simples em ink, sem superfície e sem borda. Sublinhado no hover. Usado em links do tipo “Show more” e rótulos de fechar modal.

**`button-pill-rausch`** — CTA Rausch em formato pílula usado em células em destaque, como sub-CTA “Become a host” — raio de 9999px, padding 10×20px e rótulo de 14px.

### Superfície de Busca

**`search-bar-pill`** — A barra de busca global característica. Preenchimento branco, raio de 9999px, altura de 64px, borda hairline de 1px e sombra de 1px. Internamente, é dividida por linhas verticais hairline em células `{component.search-field-segment}` (Onde / Quando / Quem). Cada segmento contém um rótulo de legenda acima de uma linha de placeholder em `{typography.caption}`.

**`search-orb`** — O botão circular Rausch que encerra a extremidade direita da barra de busca. 48×48px, totalmente arredondado, com ícone de lupa branco centralizado. É o momento de cor mais forte da página inicial.

### Navegação Superior

**`top-nav`** — Superfície branca, altura de 80px e linha inferior de 1px. O logotipo Airbnb fica alinhado à esquerda, as três abas de produto (Casas / Experiências / Serviços) ficam centralizadas, e utilitários de conta (link de anfitrião, globo de idioma e menu de conta) ficam alinhados à direita.

**`product-tab-active`** — Rótulo em ink com `{typography.nav-link}`, ícone ilustrado à mão de 32px e linha inferior ink de 2px abaixo do par ícone-rótulo.

**`product-tab-inactive`** — Rótulo suave, ícone ilustrado e sem linha inferior. Torna-se ativo ao clicar.

**`new-tag`** — Pequeno selo em formato pílula (`{rounded.full}`) fixado no canto superior direito de um ícone, com o rótulo “NOVO” em `{typography.uppercase-tag}` (8px / 700 com tracking de 0.32px e uppercase). Usado em Experiências e Serviços para indicar novidade.

### Cards de Anúncio

**`property-card`** — Card orientado por fotografia. Imagem em proporção 1:1 com cantos recortados em `{rounded.md}`, pontos do carrossel sobrepostos, selo “Preferido dos hóspedes” no canto superior esquerdo (`{component.guest-favorite-badge}`) e ícone de coração no canto superior direito (`{component.icon-button-circle}` no estado contornado padrão, preenchido com Rausch quando salvo). Abaixo da imagem: 4–5 linhas de metadados — título (`{typography.title-md}`), distância / datas (`{typography.body-sm}` suave) e preço (“$X por noite”) alinhado à direita.

**`property-card-photo`** — A própria área da foto, separada como token porque algumas superfícies, como wishlist e resultados de busca, reutilizam apenas a foto sem o bloco de metadados.

**`experience-card`** — Card mais vertical, em proporção 4:5, para experiências. Mesmo recorte em `{rounded.md}`, selo “NOVO” flutuante no canto superior esquerdo, coração no canto superior direito e título de uma linha abaixo.

**`guest-favorite-badge`** — Pílula branca arredondada (`{rounded.full}`) com texto em 11px / 600. Fica sobre a foto com o único nível de sombra do sistema aplicado para criar elevação.

### Detalhe do Anúncio

**`rating-display-card`** — Momento característico do detalhe do anúncio. Número de avaliação em 64px / 700 (“4.81”) ladeado por pequenos ornamentos SVG de louro à esquerda e à direita. Abaixo da avaliação: tagline “Preferido dos hóspedes” e linha de colunas estatísticas em ink. É o maior peso tipográfico de todo o sistema.

**`amenity-row`** — Lista em uma coluna com ícones de comodidades + rótulos em ink usando `{typography.body-md}`. Padding de 12px por linha, sem borda entre linhas; a seção é encerrada por divisores hairline de 1px acima e abaixo.

**`reviews-card`** — Grade de reviews em 2 colunas. Cada coluna contém linha do autor (avatar, nome, data) acima de um trecho de 3 linhas com link terciário “Show more”.

**`host-card`** — Card branco com cantos em `{rounded.md}` e padding de 24px, contendo avatar do anfitrião, nome, selo “Superhost”, estatística de taxa de resposta e botão secundário “Contact host” (`{component.button-secondary}`).

**`reservation-card`** — Card fixo da coluna direita nas páginas de anúncio. Superfície branca, cantos em `{rounded.md}`, borda hairline de 1px, elevação com o único nível de sombra e padding de 24px. Contém: preço por noite (`{typography.display-md}` em ink), seletor de intervalo de datas, seletor de número de hóspedes, CTA principal “Reserve” em largura total e pilha de taxas abaixo em `{typography.body-sm}`.

### Seletor de Datas

**`date-picker-day`** — Célula circular de 40×40px com o número do dia em `{typography.body-sm}`. Estado padrão com preenchimento transparente e texto ink.

**`date-picker-day-selected`** — Preenchimento ink, texto branco e círculo completo (`{rounded.full}`). Estados de intervalo entre dois dias selecionados usam fundo em cápsula com `{colors.surface-soft}` para conectá-los.

### Formulários

**`text-input`** — Superfície branca, contorno hairline de 1px, raio de 8px (`{rounded.sm}`), altura de 56px e padding 14×12px. Rótulo empilhado acima em `{typography.caption}` suave, placeholder em `{typography.body-md}` suave. No foco, a borda aumenta para 2px em ink e a cor da borda muda para `{colors.ink}` — sem brilho e sem anel.

### Rodapé

**`footer-light`** — Superfície branca, igual ao canvas da página, já que o Airbnb não usa rodapé contrastante; padding de 48×80px. Três colunas de links (Suporte / Hospedagem / Airbnb), separadas por gutters generosos de 24px. Cada coluna começa com rótulo ink em `{typography.title-sm}` e empilha linhas `{component.footer-link}` em `{typography.body-sm}` ink.

**`legal-band`** — Faixa inferior abaixo das colunas do rodapé, contendo linha de direitos autorais, seletor de idioma (ícone de globo + link “English (US)”), seletor de moeda e ícones sociais (Facebook, X, Instagram). Todo o texto usa `{colors.muted}` em `{typography.caption-sm}`.

## Comportamento Responsivo

| Nome | Largura | Principais Mudanças |
|---|---|---|
| Mobile | < 744px | A navegação superior colapsa para logotipo + hamburger; abas de produto ficam escondidas em uma folha; a barra de busca vira uma única pílula tocável; cards de propriedades ficam em 1 coluna; grade de cidades fica em 1 coluna; o detalhe do anúncio transforma o card de reserva em uma barra fixa inferior. |
| Tablet | 744–1128px | A navegação superior mantém as abas de produto, mas a barra de busca estreita; cards de propriedades ficam em 2 colunas; grade de cidades fica em 2–3 colunas; o card de reserva permanece fixo na coluna direita em largura menor. |
| Desktop | 1128–1440px | Navegação superior completa com três abas de produto centralizadas; barra de busca em largura total com os 3 segmentos visíveis; cards de propriedades em 4 colunas; grade de cidades em 6 colunas; detalhe do anúncio em 2 colunas com coluna de reserva. |
| Wide | > 1440px | A largura do conteúdo é limitada a 1440px em páginas de listagem/busca e cerca de 1280px em editoriais; o restante é absorvido pelos gutters. |

### Áreas de Toque
- CTAs principais com mínimo de 48×48px, acima do padrão WCAG AAA.
- Botão de busca circular com 48×48px — o elemento mais tocado da página.
- Botão de coração para salvar com 32×32px — no limite para AAA, mas compensado por padding generoso de 12px dentro do card de foto.
- Células do seletor de datas com 40×40px circulares.

### Estratégia de Colapso
- As abas superiores de produto colapsam em uma folha acionada pelo hamburger abaixo de 744px.
- Os 3 segmentos da barra de busca colapsam em uma entrada única, que abre um overlay de busca em tela cheia no mobile.
- Grades de propriedades e links de cidade reduzem a contagem de colunas de forma limpa em cada breakpoint — nunca reorganizam linhas de forma imprevisível; apenas reduzem colunas.
- O card de reserva no detalhe do anúncio muda de coluna fixa à direita para barra inferior fixa no mobile, contendo apenas o CTA “Reserve” + resumo do preço por noite.

## Limitações Conhecidas

- **Cores de hover:** não documentadas intencionalmente por causa da política global de não registrar hover — o estilo real de `:hover` dos cards de propriedade é uma elevação sutil, mas a extração precisa não é confiável.
- **Estados de carregamento / skeleton screens:** não visíveis nas superfícies extraídas.
- **Estilo da visualização em mapa:** os resultados de busca em mapa usam tiles Mapbox com tonalidade personalizada e marcadores Rausch; não foram capturados aqui.
- **Estados de erro em inputs:** a cor de erro (`{colors.primary-error-text}`) está documentada, mas a combinação completa de contorno do input + texto auxiliar em falha de validação não estava visível nas superfícies capturadas.
- **Paletas de submarca:** Luxe (`{colors.luxe}`) e Plus (`{colors.plus}`) estão documentadas como tokens, mas seus subsistemas completos, incluindo overrides tipográficos e tratamento de superfície, ficam em subdomínios separados e não foram capturados aqui.
