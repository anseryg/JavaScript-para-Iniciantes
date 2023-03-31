# Príncipios da linguagem de programação JavaScript.

Um "Guia" **básico** sobre Javascript e de como a linguagem funciona. Este guia poderá ser util para estudar ou para revisão. </br>
**Feito por:** Dreynus

## Variáveis - var/let/const
**Variáveis** São uma espécie de caixa, onde você pode guardar dados ou valores dentro delas para utiliza-las depois.  
Antes de declarar uma variável, você primeiro precisa declarar qual o tipo dela, e eles são:  

### **`Var`** -> Declarações com `var` tem escopo global ou escopo de função/local:
O escopo é global quando uma variável `var` é declarada fora de uma função. Isso significa que qualquer variável que seja declarada com `var` fora de um bloco de função pode ser utilizada na janela inteira.  
O escopo é local quando uma variável `var` é declarada dentro de uma função, assim ela só pode ser acessada somente dentro daquela função.  

**Exemplo:**  

~~~javascript
var ola = "Hey, olá";

function novaFunção {
  var bemVindo = "Bem-vindo";
}
~~~

Acima, `ola` tem um *Escopo Global*, pois foi criada fora de uma função, então poderá ser utilizada em qualquer parte do código, enquanto `bemVindo` tem *Escopo Local* pois foi criada dentro de uma função, então só poderá ser acessada dentro daquela função, então se tentarmos chamar ela fora da função dará erro pois ela não foi declarada globalmente. Além disso, variáveis var podem ser declaradas de novo e atualizadas.


### **`Let`** -> Declarações com `let` tem escopo de bloco:
Um bloco é uma porção de código cercado por {}. Um bloco vive dentro dessas chaves. Tudo o que estiver cercado por chaves é um bloco.  
Assim, uma variável declarada com let em um bloco estará disponível apenas dentro daquele bloco.  

**Exemplo:**

~~~javascript
let digaOla = "Olá, tudo bem?";
let vezes = 5;

if (times > 3) {
  let hey = "Hey, como está?";
  console.log(hey) // dirá "Hey, como está?"
}

console.log(hey) // variável hey não declarada
~~~

Como visto acima, usar `hey` fora do bloco na qual ela foi criada retornará erro, pois `let` é tem escopo de bloco.  
Você pode atualiza-la (dentro de seu escopo) mas não pode declarar novamente (dentro de seu escopo), podendo assim ser declarada novamente em outros escopos.


### **`Const`**

**Obs:** Quando usa var/let/const antes do nome de uma variável você está declarando ela, e quando você quer atualizar ela, você não necessariamente precisa declarar se é var, let ou const novamente, apenas `var` aceita ser declarada novamente, `let` e `const` darão erros, ja que `let` pode ser atualizada mas não declarada novamente e `const` não pode ser atualizada e nem declarada novamente. Então para atualizar o valor utilize apenas o nome da variável e defina o valor que atualizará, a não ser que queira declarar ela novamente.
~~~javascript
var nome = "Gabriel"; // Aqui você declarou uma variável do tipo nome.
nome = "Santos"; // Aqui você apenas alterou o seu valor.
~~~

Saiba mais sobre a [diferença entre as variáveis aqui.](https://www.freecodecamp.org/portuguese/news/var-let-e-const-qual-e-a-diferenca/)
