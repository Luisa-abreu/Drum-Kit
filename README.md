# Drum Kit

Um drum kit interativo direto no navegador: aperte as teclas do computador e ouça os sons, com uma animação de destaque na tecla pressionada.

## Motivação

Esse projeto foi feito como prática de manipulação do DOM, eventos de teclado e animações em CSS puro, sem uso de frameworks. A ideia é reforçar fundamentos de JavaScript (event listeners, seleção de elementos, transições) 

## Demo

🔗 [Ver demo ao vivo]((https://drum-kit-chi.vercel.app/))

Ou rode localmente: abra o `index.html` no navegador e comece a tocar!

## Como usar

Aperte as seguintes teclas do teclado para tocar cada som:

| Tecla | Som |
|:---:|---|
| `A` | Clap |
| `S` | Hihat |
| `D` | Kick |
| `F` | Openhat |
| `G` | Boom |
| `H` | Ride |
| `J` | Snare |
| `K` | Tom |

## Funcionalidades

- Reprodução de som ao pressionar as teclas do teclado
- Animação visual na tecla pressionada (escala + destaque)
- Efeito de "explosão" de cor no fundo da tecla ao tocar
- Cada tecla com uma cor própria, formando uma paleta degradê

## Tecnologias

- HTML5 (elemento `<audio>`)
- CSS3 (animações, keyframes, grid)
- JavaScript puro (sem frameworks)

## Estrutura do projeto

```
drum-kit/
├── index.html      # Estrutura da página e elementos de áudio
├── style.css        # Estilos e animações das teclas
├── script.js         # Lógica de captura de teclado e reprodução de som
├── sounds/           # Arquivos de áudio (.wav) de cada som
└── README.md
```

## Como rodar localmente

1. Clone o repositório
2. Abra o arquivo `index.html` diretamente no navegador

Não é necessário instalar dependências nem rodar um servidor.

## Deploy

Publicado na [Vercel](https://vercel.com), com deploy automático a cada push na branch principal.

## Créditos

Projeto baseado no clássico desafio "Drum Kit" (JavaScript30).
