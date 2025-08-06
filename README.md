# 🎯 Jogo do Número Secreto

Este é um jogo simples de adivinhação de número secreto, desenvolvido com HTML, CSS e JavaScript, como parte do curso da Alura. O objetivo do jogo é adivinhar um número aleatório entre 1 e 100 com o menor número de tentativas possível.

## 🕹️ Como jogar

1. Ao abrir o jogo, será exibida uma mensagem pedindo para você escolher um número entre 1 e 100.
2. Digite seu palpite no campo de entrada e clique no botão **"Chutar"**.
3. O sistema dirá se o número secreto é **maior** ou **menor** do que o número informado.
4. Continue tentando até acertar!
5. Ao acertar, você verá uma mensagem com a quantidade de tentativas e poderá clicar em **"Novo jogo"** para recomeçar.

## 💻 Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- [ResponsiveVoice API](https://responsivevoice.org/) – para leitura em voz alta das mensagens

## 📁 Estrutura do Projeto

projeto/
├── index.html # Página principal do jogo
├── style.css # Estilização da interface
├── app.js # Lógica do jogo em JavaScript
└── img/
├── ia.png # Imagem decorativa
└── Ruido.png # Fundo com ruído para a interface


## 🗣️ Acessibilidade

Este projeto usa a biblioteca `responsiveVoice` para tornar a experiência mais acessível, com leitura em voz das mensagens exibidas na tela.

📌 Observações
O número sorteado nunca se repete até que todos os números entre 1 e 100 tenham sido utilizados.

O botão "Novo jogo" só é habilitado quando você acerta o número.




## 🚀 Para rodar localmente

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
