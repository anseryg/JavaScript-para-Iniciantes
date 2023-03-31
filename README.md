# Príncipios da linguagem de programação JavaScript.

Um "Guia" **básico** sobre Javascript e de como a linguagem funciona. Este guia poderá ser util para estudar ou para revisão. </br>
**Feito por:** Dreynus

## Variáveis - var/let/const
**Variáveis** São uma espécie de caixa, onde você pode guardar dados ou valores dentro delas para utiliza-las depois.  
Antes de declarar uma variável, você primeiro precisa declarar qual o tipo dela, e eles são:  

### **`var`** -> Declarações com `var` tem escopo global ou escopo de função/local:  
O escopo é global quando uma variável `var` é declarada fora de uma função. Isso significa que qualquer variável que seja declarada com `var` fora de um bloco de função pode ser utilizada na janela inteira.  
O escopo é local quando uma variável `var` é declarada dentro de uma função, assim ela só pode ser acessada somente dentro daquela função.  

**Exemplo:**  

~~~javascript
var ola = "Hey, olá"

function novaFunção {
  var bemVindo = "Bem-vindo"
}
~~~

Acima, `ola` tem um *Escopo Global*, pois foi criada fora de uma função, então poderá ser utilizada em qualquer parte do código, enquanto `bemVindo` tem *Escopo Local* pois foi criada dentro de uma função, então só poderá ser acessada dentro daquela função, então se tentarmos chamar ela fora da função dará erro pois ela não foi declarada globalmente. Além disso, variáveis var podem ser declaradas de novo e atualizadas.

### **`let`** ->



### **`const`**
