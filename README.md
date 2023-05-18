<h1 align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="50px" height="50px" alt="JavaScript">
  JavaScript para iniciantes
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/IDE-Visual%20Studio%20Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" alt="Visual Studio Code">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Linguagem-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=323330" alt="JavaScript">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Ambiente%20de%20Execução-Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js">
</p>


<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="100px" alt="JavaScript Logo">
  <h1 style="font-size: 32px; margin-top: 16px; margin-bottom: 16px;">JavaScript: A Linguagem da Web</h1>
</div>

<p align="justify"> JavaScript é uma linguagem de programação amplamente utilizada para desenvolvimento web. Com ela, você pode criar interatividade, adicionar comportamento dinâmico e manipular o conteúdo das páginas da web.</p>

<h3 align="justify">Principais características do JavaScript:</h3>

- **Linguagem de programação interpretada**: O código JavaScript é executado diretamente pelos navegadores, sem a necessidade de compilação prévia.
- **Cliente e servidor**: O JavaScript pode ser executado tanto no lado do cliente, nos navegadores dos usuários, quanto no lado do servidor, usando o Node.js.
- **Multiplataforma**: O JavaScript pode ser executado em diferentes sistemas operacionais, tornando-o uma escolha versátil para o desenvolvimento web.


## Por que utilizar o Node.js?

O Node.js é um ambiente de execução JavaScript baseado no motor V8 do Google Chrome. Ele permite que você execute código JavaScript no servidor, fornecendo uma série de benefícios:

- **Ampla variedade de aplicativos**: Com o Node.js, você pode criar desde pequenos scripts a aplicativos de grande escala, como servidores web, APIs, aplicativos em tempo real e muito mais.
- **Gerenciamento assíncrono de eventos**: O Node.js utiliza uma abordagem orientada a eventos e não bloqueante, o que significa que é altamente eficiente em lidar com várias solicitações concorrentes de forma não sequencial.
- **Módulos e pacotes**: O Node.js possui um gerenciador de pacotes chamado npm, que permite acessar um vasto ecossistema de bibliotecas e módulos prontos para uso.
- **Compartilhamento de código**: Com o Node.js, você pode compartilhar código entre o lado do cliente e do servidor, tornando o desenvolvimento mais eficiente e facilitando a criação de aplicativos em tempo real.

Utilizar o Node.js para desenvolvimento JavaScript permite que você aproveite as características da linguagem e facilite a criação de aplicativos mais complexos sem a necessidade de abrir constantemente o console no navegador. Além disso, o Node.js fornece uma ampla gama de recursos e ferramentas para o desenvolvimento de aplicações servidor-side em JavaScript.

Entre no site oficial do NodeJS: [https://nodejs.org/en](https://nodejs.org/en), baixe e instale caso não tenha pois iremos utiliza-lo.



<div align="center">
  <h1 style="font-size: 80px;">Configurando o Visual Studio Code como Ambiente de Desenvolvimento</h1>
</div>

O Visual Studio Code é uma poderosa IDE (Ambiente de Desenvolvimento Integrado) que oferece suporte ao desenvolvimento em diversas linguagens, incluindo JavaScript. Siga os passos abaixo para baixar e instalar e também instalar a extensão Code Runner que iremos utilizar, em seu computador:

## Baixando e Instalando o Visual Studio Code

1. Acesse o site oficial do Visual Studio Code em [https://code.visualstudio.com](https://code.visualstudio.com).
2. Clique no botão de download para o sistema operacional em que você está utilizando (Windows, macOS ou Linux).
3. Após o download ser concluído, execute o arquivo de instalação e siga as instruções para instalar o Visual Studio Code em seu sistema.

## Instalando a Extensão Code Runner

A extensão Code Runner é uma ferramenta útil para executar o código JavaScript diretamente no Visual Studio Code, sem a necessidade de abrir o navegador. Para instalar a extensão, siga os passos abaixo:

1. Abra o Visual Studio Code.
2. Clique no ícone de extensões na barra lateral esquerda (ou pressione `Ctrl+Shift+X`).
3. Na barra de pesquisa, digite "Code Runner".
4. Localize a extensão "Code Runner" na lista de resultados e clique em "Instalar".
5. Após a instalação ser concluída, você estará pronto para usar a extensão Code Runner.

Agora você tem o Visual Studio Code instalado em seu computador e a extensão Code Runner pronta para ser utilizada. Basta criar um arquivo com a extensão ".js" e começar a criar seus códigos.


<div align="center">
  <h1 style="font-size: 80px;">Exibindo Informações no Console com console.log()</h1>
</div>

O `console.log()` é uma função em JavaScript que permite exibir informações no console do navegador ou ambiente de execução. Vamos começar com algo simples:

Use o comando `console.log()` para exibir mensagens no console do navegador:

~~~javascript
console.log('Olá, Mundo!')  // Manda exibir uma mensagem no console
~~~

```
Olá, Mundo!
```

Você pode usar tanto aspas "duplas", quanto aspas 'simples' e  \`crases\`. Mas veremos sobre crases mais a frente, pois ela tem uma função chamada Template String. As aspas servem para mostrar que aquele valor é um texto, uma string (todo texto é uma string, porém veremos isso mais a frente). Você pode alternar entre as aspas dentro de um texto, mas lembre-se, se você iniciou com um tipo de aspas, você deve fechar com o mesmo tipo.

~~~javascript
console.log('Meu nome é "Gabriel"')  // Aspas duplas dentro de aspas simples
console.log("Meu nome é 'Gabriel'")  // Aspas simples dentro de aspas duplas
console.log(`Meu nome é "Gabriel"`)  // Aspas duplas dentro de crases
~~~

```
Meu nome é "Gabriel"
Meu nome é 'Gabriel'
Meu nome é "Gabriel"
```

Você também pode separar valores e mandar exibi-los no console, utiliza-se a virgula para separar valores. É útil quando se trata de mostrar vários dados.

~~~javascript
console.log('Olá', 'Mundo!')
~~~

```
Olá Mundo!
```

Também utilizamos o `+` para fazer junção, que seria a concatenação (Também veremos mais adiante)

~~~javascript
console.log('Olá' + ' Mundo')
~~~

```
Olá Mundo
```

<div align="center">
  <h1 style="font-size: 80px;">Comentários no Código</h1>
</div>

`Comentários` em JavaScript são trechos de texto que você pode adicionar ao seu código para fazer anotações ou observações. Eles são usados para fornecer informações extras sobre o código, mas não afetam a forma como o programa é executado.

Imagine que você está escrevendo um código e quer adicionar uma explicação para você mesmo ou para outras pessoas que vão ler o código. Os comentários permitem que você faça isso. Eles são como pequenas notas que você escreve no seu código.

Os comentários não são interpretados pelo computador, então o programa ignora completamente o que está escrito nos comentários. Eles existem apenas para ajudar os humanos a entender o código.

Existem 2 tipos de comentários em JavaScript:

1. Comentários de uma linha: São usados para adicionar uma explicação rápida em apenas uma linha.  
Exemplo:
~~~javascript
// Este é um Comentário de uma Linha ou Comentário de Linha.

console.log('Olá!') // Comentário de linha também pode ser feito na linha de um código
~~~

2. Comentários em bloco: São usados para anotações maiores que podem ocupar várias linhas.  
Exemplo:
~~~javascript
/*
Este é um comentário em bloco.
Tudo o que estiver entre esses asteriscos e barra será considerado um comentário.
Não importa quantas linhas tenha.
*/
~~~

Comentários são muito úteis quando você quer lembrar o que um pedaço de código faz ou quando você quer explicar o seu pensamento enquanto escreve o código. Eles também ajudam outras pessoas a entenderem o seu código caso você compartilhe com elas. Ah e claro, é uma boa prática de programação você adicionar comentários aos seus códigos até para não se perder caso ele fique enorme.


<div align="center">
  <h1 style="font-size: 80px;">Diferenças entre Node e Navegador</h1>
</div>

Quando falamos de programação em JavaScript, é importante entender que existem dois ambientes principais nos quais podemos executar nosso código: o navegador (como o Google Chrome, Mozilla Firefox, etc.) e o Node.js.

O navegador é o programa que usamos para acessar a internet e visualizar páginas da web. Ele possui um mecanismo interno chamado mecanismo de renderização, que interpreta e executa o JavaScript contido nas páginas. No navegador, podemos interagir com elementos da página, manipular o DOM (Document Object Model), criar animações e muito mais. É o ambiente onde o JavaScript é amplamente utilizado para tornar as páginas da web interativas e dinâmicas.

Já o Node.js é um ambiente de execução do JavaScript fora do navegador. Ele nos permite executar código JavaScript em um servidor, ou seja, em uma máquina remota. Com o Node.js, podemos construir servidores web, APIs, aplicativos em tempo real e muitas outras aplicações do lado do servidor. Diferentemente do navegador, o Node.js não tem um mecanismo de renderização, mas oferece acesso a recursos do sistema operacional, como arquivos, rede e bancos de dados, permitindo que construamos aplicativos completos e escaláveis.

Uma das principais diferenças entre o Node.js e o navegador é o conjunto de recursos disponíveis. No navegador, temos acesso ao DOM, eventos do navegador, APIs específicas do navegador (como acesso à câmera ou geolocalização) e muitas outras funcionalidades voltadas para interações com o usuário. Já o Node.js oferece recursos voltados para o desenvolvimento do lado do servidor, como acesso ao sistema de arquivos, criação de servidores web, suporte a bancos de dados, entre outros.

Outra diferença é a forma como o código é executado. No navegador, o código JavaScript é executado em resposta a eventos do usuário ou do próprio navegador. Por exemplo, quando clicamos em um botão, o código associado a esse evento é executado. Já no Node.js, o código é executado de forma contínua, esperando por solicitações externas. Ele é capaz de lidar com várias solicitações simultaneamente de maneira assíncrona, o que o torna ideal para aplicações que exigem alta escalabilidade e desempenho.

Portanto, resumindo, o navegador é o ambiente onde o JavaScript é executado nas páginas da web, permitindo interações com o usuário e manipulação do conteúdo da página. Já o Node.js é um ambiente de execução do JavaScript fora do navegador, voltado para o desenvolvimento do lado do servidor, oferecendo acesso a recursos do sistema operacional e suporte para construção de aplicativos mais complexos.

Um exemplo da diferença seria o uso de algumas funções que possui no Navegador e não no Node (Onde estamos executando nossos códigos). Uma função que se encaixa nisso é a `alert()`, essa função emite aquelas janelas de alerta do navegador, e podemos fazer isso da seguinte maneira:

1. Precisamos de uma página, então vamos criar uma página de teste. Para isso criaremos um arquivo chamado "*index.html*", é importante que ele possua a extensão ".html".
2. No Visual Studio Code, quando você abre um html e digita apenas "!" aparece uma sugestão de código 


<!-- 
1. Uso do console.log() - Feito
2. Comentários - Feito
3. A diferenças entre o Node e Navegador
4. Variáveis let
5. Váriaveis const
6. Dados Primitivos
7. Operadores Aritimeticos
8. Arrays (básico)
9. Funções (básico)
10. Objetos (básico)
11. Operadores de Comparação
12. Operadores Lógicos
13. Estruturas Condicionais
 -->
