# oblivion is freedom

Experimento visual inspirado na música **"No One Lasts Forever"**, de Charli xcx.
O projeto apresenta frases curtas em uma tela escura enquanto o fundo alterna
rapidamente entre preto e branco.

> **Aviso de acessibilidade:** esta página contém flashes de luz muito rápidos.
> Pessoas sensíveis a luzes piscantes ou com epilepsia fotossensível devem evitar
> abrir a experiência.

## Como executar

O projeto não exige instalação nem dependências. Abra o arquivo
[`index.html`](index.html) diretamente no navegador.

Para servir a página localmente, também é possível usar um servidor HTTP simples:

```bash
python3 -m http.server
```

Depois, acesse <http://localhost:8000>.

## Como funciona

- As frases `OBLIVION IS FREEDOM`, `THEY ARE DEAD, THEY ARE GONE` e
	`NO ONE LASTS FOREVER` aparecem em sequência.
- O texto muda a cada 800 milissegundos.
- As cores do fundo e do texto são invertidas a cada 100 milissegundos.
- Toda a experiência está implementada em um único arquivo HTML, com CSS e
	JavaScript embutidos.

## Estrutura

```text
.
├── index.html  # página e lógica da experiência
└── README.md   # documentação do projeto
```

## Tecnologias

- HTML5
- CSS3
- JavaScript puro
- Fonte Montserrat, carregada pelo Google Fonts