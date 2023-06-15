    Projeto Alura Cast

Utilizando a propriedade GRID no CSS foi possível entregar uma plataforma trabalahndo com colunas, diferentemente do Flexbox, aqui utilizo a propriedade GAP para trabalhar dentro das boxes.

    Grid Container
Como o próprio nome indica, é um container que aloca todos os itens do Grid, atua como elemento pai e é nele que o display: grid deve ser aplicado.

    Grid Item
Esses elementos são os filhos diretos do Grid Container. No exemplo abaixo há um Grid Container com três Grid Items.

    Grid Line
São linhas ou traços que atuam como uma divisória entre as linhas e colunas. Existem as Grid Lines horizontais (linhas) e as verticais (colunas). Por meio delas realiza-se uma contagem, no exemplo abaixo está destacado a linha/traço 4 vertical.

    Grid Cell
A célula é um espaço entre 4 grid lines que se cruzam. É a menor unidade no Grid, muito parecido com uma célula de tabela. No exemplo, está destacado a célula que o ocupa do traço 1 até o traço 2 horizontalmente e do traço 1 até o 2 verticalmente.

    Grid Area
É um conjunto de uma ou mais grid cells que formam uma área que pode ser nomeada. Abaixo a grid área, ocupa o traço 1 até o 3 horizontalmente e o traço 2 e 4 verticalmente.

    Grid Track
Uma trilha de grade é o espaço entre duas grid lines adjacentes. Essa trilha pode ser uma linha completa ou uma coluna completa. No exemplo, a grid track ocupa da grid line 2 até a grid line 3 horizontalmente.

- Como otimizar um projeto com o uso das variáveis de CSS;
- Uso avançado da função minmax;
- Como incluir o gap na largura das colunas.
- A propriedade do CSS box-sizing com o valor border-box é usado para emular o comportamento dos navegadores, incluindo nas propriedades width e/ou height para incluirem os valores de padding e border. Ao invés de valores de padding e border, incluí na largura das colunas o valor do gap.

      -> auto-fit:
  Ajusta o tamanho das colunas para ocupar o tamanho total do espaço disponível do container, expandindo-as para que não fique nenhum espaço sobrando. Independente do tamanho da tela.
  
      ->  Sobre o gap:
  Definindo um único valor que será aplicado entre linhas e colunas. Exemplo:
  .grid-container {
  gap: 16px;
  }
  
  Definindo dois valores de uma vez só na propriedade gap. Sendo que o primeiro valor é referente ao row-gap e o segundo ao column-gap. Exemplo:
  .grid-container {
  gap: 16px 24px;
  }
  
  A propriedade do CSS gap admite qualquer valor de CSS válido e não negativo, como píxel, em, rem, porcentagem (%), entre outros. 
  Você também pode usar a função calc() para especificar o tamanho do gap.
  
