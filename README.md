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

<p align="justify">JavaScript é uma linguagem de programação amplamente utilizada para desenvolvimento web. Com ela, você pode criar interatividade, adicionar comportamento dinâmico e manipular o conteúdo das páginas da web.</p>

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


<!-- 1. Uso do console.log()
2. Comentários
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
