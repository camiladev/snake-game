# Snake Game

Projeto faz parte do último modulo do BootCamp HTML Web Developer da Digital Innovation One.

**Telas**

:hourglass_flowing_sand: Em construção

### :page_with_curl: Informações sobre o Projeto

A criação do jogo da cobrinha, tão famoso, é para aplicar conhecimentos de CSS3 e JavaScript. 

**Versão 1.0**

Nesta versão inicial foi seguido os fundamentos passados durante a aula do Bootcamp, onde a cobrinha se movimenta pelas setas direcionais do teclado, e ela pode atravessar as paredes mas não pode encostar no próprio corpo. E o objetivo da cobrinha é comer as frutinhas que aparecem em lugares aleatórios no campo.

Não tem sistema de contagem de pontos e não armazena as informações dos pontos anteriores.

 

### :clipboard: Resolução

**Movimentação**

A movimentação é realizada com a captura e mapeamento das teclas do teclado referente a as setas.

**Criação da Cobra**

Para criar a personagem principal foi usado a interface Canvas de Renderização de Contexto de duas Dimensões (2D), onde o .fillStyle define a cor do personagem e o .fillrect desenha o elemento dentro do canvas.

**Criação da Comida**

Para criar a comida foi usado a mesma estrutura da criação da cobrinha, porem a localização dentro do canvas é aleatória  e para isso as variáveis X e Y que se referem a posição vertical e horizontal, recebe o seguinte código:

```jsx
let food = {
    x: Math.floor(Math.random() * 15 + 1) * box,
    y: Math.floor(Math.random() * 15 + 1) * box
}
```

### :hammer_and_wrench: Tecnologias usadas

- HTML5
- CSS3
- JavaScript

### :computer: Execução

**Versão 1.0**

Para você rodar o projeto localmente é necessário que realize o clone do projeto e abrir o arquivo index.html no navegador.

### :octocat: Deploy

:hourglass_flowing_sand: Em construção

 

### :running: Milha Extra

Para a versão 2.0, pretendo implementar:

- Autenticação de usuário;
- Deixar a aplicação responsiva para as outras plataformas;
- Alterar o layout
- Colocar sistema de pontuação