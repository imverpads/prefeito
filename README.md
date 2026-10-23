# Site — Eduardo Da Machado

Site **pessoal** de Eduardo Da Machado, prefeito de Santana do Araguaia (PA).

⚠️ **Não é canal oficial** da Prefeitura — é um site pessoal (evita o Art. 37 §1º da Constituição).

## Como abrir

Abra `index.html` num navegador. Funciona em `file://` (duplo clique), mas para a melhor experiência
(o vídeo de fundo usa *range requests* para a rolagem) prefira servir por um servidor local, por exemplo:

```bash
npx serve .
```

## Stack

- HTML + CSS puro, sem build (um único arquivo `index.html`).
- **Tailwind CSS** (via CDN) para utilidades de layout.
- **GSAP + ScrollTrigger** e **Lenis** para a rolagem suave e o vídeo de herói sincronizado ao scroll.
- **Lucide** para os ícones.
- Fontes: **Inter** (lettering/display) + **Manrope** (corpo) + **IBM Plex Mono** (rótulos) — Google Fonts.
- Paleta: branco/tinta (`#15171c`) com acento laranja (`#ff5a36`), tokens herdados do design system do projeto.

## Estrutura

- `index.html` — o site.
- `img/video-hero.mp4` — vídeo aéreo da cidade, usado como trilho de scroll do herói.
- `img/logo-crop.svg` — logo oficial (recorte de `img/logo_transparente.svg`, sem a margem transparente).
- `img/logo_transparente.svg` — arquivo-fonte da logo, caso precise recortar de novo.

## ⛔ Pendências

1. **Conteúdo real** das seções Obras, Plano de Governo, Biografia e Transparência (hoje são placeholders "a publicar").
2. **Formulário de contato** sem endpoint configurado ainda.
3. **Domínio real** — trocar `https://www.eduardodamachado.com.br/` no canonical/OG quando publicar.
4. **Nome civil** — confirmar `alternateName` no JSON-LD (`Eduardo Alves Conti`).
