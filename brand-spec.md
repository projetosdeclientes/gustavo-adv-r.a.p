# Brand spec — Método R.A.P.

Extraído do brief do projeto. Aplicar como sistema de tokens no :root do HTML.

## Paleta (6 tokens)

| Token | Hex | Uso |
|---|---|---|
| `--bg` | `#F9F7F4` | Fundo padrão do site (off-white quente) |
| `--surface` | `#FFFFFF` | Cards, áreas elevadas, fundos de seção branca |
| `--fg` | `#2E2E2E` | Texto corpo (quase preto) |
| `--muted` | `#4A5568` | Texto secundário, opacidades em dark mode |
| `--border` | `#E2DCD3` | Linhas divisórias, bordas sutis |
| `--accent` | `#C8963E` | Dourado terroso — destaques, ícones, bordas de ênfase |
| `--primary` | `#1A3A5C` | Azul-marinho — títulos, botões, seções de fundo escuro |

## Tipografia

- **Display (títulos):** Playfair Display, Bold — Google Fonts
  - Desktop: mínimo 36px (hero 48px)
  - Mobile: mínimo 28px (hero 32px)
- **Body (texto):** Inter, Regular/Medium — Google Fonts
  - 16–18px, line-height 1.7
  - Mínimo 15px em qualquer breakpoint
- **Mono:** não usado neste projeto

## Postura visual (inspirada em Basecamp + Linear + escritório jurídico)

- Seções bem separadas por espaço generoso (padding vertical 80–120px)
- Headlines grandes e sem ornamento
- Copy que fala de dor sem dramatizar
- Hierarquia onde o texto é protagonista
- Peso tipográfico extremo nos títulos (bold, tamanho grande)
- Uso cirúrgico do dourado (acento): máximo 2 elementos por seção
- Foto do fundador como elemento central de humanização
- Estética sóbria, profissional — comunica "advogado de confiança", não "startup"
- Sem sombras exageradas, sem gradientes chamativos, sem elementos decorativos desnecessários
- Zero parallax, zero carrossel

## Layouts

- **Hero:** duas colunas (texto + foto), coluna única mobile
- **Seções internas:** max-width 1120px, centralizadas, padding generoso
- **Grids:** 2 ou 3 colunas desktop, empilhado mobile (breakpoint 768px)
- **Sem menu de navegação, sem múltiplas páginas**
- **Única conversão:** WhatsApp

## Responsivo

- Mobile-first. Breakpoints: 390px, 768px, 1280px
- Botões CTA ≥ 52px altura em mobile
- Nenhuma fonte < 15px
- Colunas colapsam para empilhado em mobile
