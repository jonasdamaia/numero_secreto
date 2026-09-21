NÚMERO SECRETO

Jogo de adivinhação feito com HTML, CSS e JavaScript puros, sem frameworks nem dependências. O computador sorteia um número entre 1 e 100 e você tenta descobrir qual é, recebendo a dica "alto demais" ou "baixo demais" a cada palpite.

[Jogar agora](https://jonasdamaia.github.io/numero_secreto/)

## Como jogar

1. Abra o jogo. Um número secreto entre 1 e 100 é sorteado automaticamente.
2. Digite um palpite no campo e pressione **Enter**.
3. O jogo informa se o palpite foi **ALTO demais** ou **BAIXO demais**.
4. Continue até acertar. Ao acertar, o campo é bloqueado e a mensagem de parabéns aparece.
5. Clique em **Reiniciar jogo** para jogar de novo com um novo número.

## Recursos

- Contador de tentativas.
- Histórico com todos os números já chutados.
- Dica a cada palpite (alto ou baixo demais).
- Layout responsivo, que se adapta de celulares pequenos a telas grandes.
- Tema claro e escuro automático, de acordo com a preferência do sistema.
- Foco visível para navegação por teclado e suporte a leitores de tela (`aria-label` e `aria-live`).
- Respeita a preferência por movimento reduzido.

## Tecnologias

- HTML5
- CSS3 (variáveis CSS, Flexbox, Grid e `prefers-color-scheme`)
- JavaScript (ES6+)
- Fonte [Bricolage Grotesque](https://fonts.google.com/specimen/Bricolage+Grotesque), carregada do Google Fonts. Sem conexão, o jogo usa a fonte padrão do sistema e continua funcionando normalmente.

## Estrutura do projeto

```
.
├── index.html   # Estrutura da página
├── style.css    # Estilos e responsividade
├── index.js     # Lógica do jogo
└── README.md
```

## Como executar

Não é preciso instalar nada.

**Opção 1: abrir direto no navegador**

Baixe ou clone o repositório e abra o arquivo `index.html` com um duplo clique.
