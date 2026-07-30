# A2O Sistemas — Protótipo do site

Protótipo navegável do site da **A2O Sistemas** (gestão logística integrada: TMS, Frota e Agro).

HTML/CSS/JS puro, sem dependências além do Google Fonts. As imagens são de preenchimento (uso livre) e devem ser substituídas pelas oficiais.

## Estrutura

```
.
├── index.html            # home (servida pelo GitHub Pages)
├── solucoes.html         # página-mãe de soluções
├── tms.html              # solução · A2O TMS
├── frota.html            # solução · A2O Frota
├── agro.html             # solução · A2O Agro
├── wms.html              # solução · A2O WMS
├── locacao.html          # solução · A2O Locação
├── como-funciona.html    # visão geral da plataforma
├── sobre.html            # institucional / história
├── cases.html            # listagem de cases
├── case.html             # case interno (template)
├── blog.html             # listagem do blog
├── artigo.html           # artigo interno (template)
├── contato.html          # canais + formulário
├── figma/                # mesmas 14 páginas em versão ESTÁTICA
│                         # (sem animações/pin/hover) para importar no Figma
└── assets/
    ├── logo-vetorizada.svg       # logo do menu
    ├── logo-branca.svg           # logo do rodapé (fundo escuro)
    ├── divisor-hero.svg
    ├── new-image-bg.png          # fundo da hero
    ├── image-caminhao.png        # caminhão da hero
    ├── solucoes-imagens/         # imagens das soluções
    └── conteudo-imagens/         # imagens de blog e cases
```

Cada página é autocontida (CSS inline no próprio arquivo). As versões em
`figma/` diferem das da raiz apenas pelo bloco "MODO ESTÁTICO" no fim do
CSS (que desliga animações, pin e hover) e pelos caminhos de assets
(`../assets/`).

## Rodar localmente

Basta abrir o `index.html` no navegador.

## Publicação

Hospedado via **GitHub Pages** (branch `main`, raiz do repositório).
