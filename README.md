# Estudos de HTML5 e CSS3

Repositório de estudos práticos de **HTML5** e **CSS3**, organizado como uma trilha progressiva de exercícios e desafios. O conteúdo parte da estrutura básica de uma página e avança por semântica, tipografia, modelo de caixas, responsividade, formulários, Flexbox e CSS Grid.

Os exemplos são páginas estáticas e podem ser abertos diretamente no navegador. Não há processo de compilação, gerenciador de pacotes ou framework.

## Conteúdo

O material está dividido em duas áreas:

- `exercicios/`: exemplos menores, focados em uma propriedade ou conceito;
- `desafios/`: páginas que combinam os conceitos estudados em projetos mais completos.

Cada área é separada em cinco módulos:

| Módulo | Principais assuntos |
| --- | --- |
| 01 | Estrutura HTML, títulos, parágrafos, imagens, favicon, semântica, listas, links, áudio, vídeo e formas de aplicar CSS |
| 02 | Cores, gradientes, tipografia, fontes externas, seletores, pseudo-classes, links e modelo de caixas |
| 03 | Imagens de fundo, posicionamento, efeito parallax, alinhamento e tabelas |
| 04 | Iframes, formulários, orientação de tela, media queries e layouts responsivos |
| 05 | Flexbox e CSS Grid |

## Estrutura do repositório

```text
HTML-CSS/
├── exercicios/
│   ├── modulo-01/   # ex001 a ex015
│   ├── modulo-02/   # ex016 a ex021
│   ├── modulo-03/   # ex022 e ex023
│   ├── modulo-04/   # ex024 a ex026
│   └── modulo-05/   # ex027 e ex028
└── desafios/
    ├── modulo-01/   # d001 a d009
    ├── modulo-02/   # d010
    ├── modulo-03/   # d011 a d014
    ├── modulo-04/   # d015 e d016
    └── modulo-05/   # d016 e d017
```

Dentro de alguns exercícios há várias páginas ou subpastas. Por exemplo, `ex027` reúne uma sequência de experimentos com Flexbox, enquanto `ex028` contém exemplos progressivos de Grid Layout.

## Projetos de destaque

- **Site Android** — artigo responsivo com HTML semântico, imagens adaptáveis, fonte local e vídeo incorporado em [`desafios/modulo-02/d010/android.html`](desafios/modulo-02/d010/android.html).
- **Cordel Moderno** — página com imagens de fundo e efeito parallax em [`desafios/modulo-03/d012/index.html`](desafios/modulo-03/d012/index.html).
- **Projeto Redes Sociais** — simulação de um celular com navegação entre páginas por `iframe` em [`desafios/modulo-04/d015/index.html`](desafios/modulo-04/d015/index.html).
- **Tela de login** — interface responsiva com formulário e breakpoints para diferentes telas em [`desafios/modulo-04/d016/index.html`](desafios/modulo-04/d016/index.html).
- **Álbum com Flexbox** — galeria de imagens construída com layout flexível em [`desafios/modulo-05/d016/index.html`](desafios/modulo-05/d016/index.html).
- **Layout com Grid** — estrutura de página dividida em topo, menu, conteúdo, área secundária e rodapé em [`desafios/modulo-05/d017/index.html`](desafios/modulo-05/d017/index.html).

## Como executar

### Abrir diretamente

Escolha um arquivo HTML e abra-o no navegador. Exemplos de pontos de entrada:

```text
exercicios/modulo-01/ex001/index.html
desafios/modulo-02/d010/android.html
desafios/modulo-05/d017/index.html
```

### Usar um servidor local

Um servidor local evita restrições do navegador em exemplos com iframes e caminhos relativos. Na raiz do repositório, execute uma das opções abaixo:

```bash
# Python
python3 -m http.server 8000

# Node.js, caso tenha o pacote disponível
npx serve .
```

Depois, acesse `http://localhost:8000` e navegue até a pasta desejada. Também é possível usar a extensão **Live Server** do VS Code.

## Tecnologias e recursos praticados

- HTML5 semântico;
- CSS3 interno, inline e externo;
- seletores, pseudo-classes e pseudo-elementos;
- fontes locais e Google Fonts;
- imagens responsivas com `picture` e `source`;
- áudio, vídeo e conteúdo incorporado;
- tabelas, formulários e iframes;
- media queries e abordagem responsiva;
- Flexbox;
- CSS Grid Layout.

## Observações

- O projeto não possui dependências para instalar nem testes automatizados.
- Alguns exemplos usam Google Fonts, Material Icons, YouTube ou links externos e precisam de conexão com a internet para exibir todo o conteúdo.
- A tela de login referencia `login.php` apenas para demonstrar o envio do formulário; não há backend implementado neste repositório.
- Os diretórios preservam a numeração original dos estudos. Por isso, o identificador `d016` aparece tanto no módulo 04 quanto no módulo 05.
- Para estudar em sequência, comece por `exercicios/modulo-01/ex001` e avance pela numeração; ao final de cada etapa, consulte os desafios do módulo correspondente.

## Objetivo

Este repositório funciona como registro de aprendizado e material de consulta. Cada arquivo demonstra um conceito específico, e os desafios mostram como esses conceitos podem ser combinados na construção de páginas completas.
