# Tipos-de-Dados
Distinguir e utilizar diferentes tipos de dados (numéricos, textos e booleanos) em algoritmos e conhecer suas representações pelo computador.

Como visto no material em sala, o ECMA Script ou popularmente conhecido, JavaScript, contém uma variedade de tipos de dados, como:
- Número: representa valores numéricos, sejam inteiros ou decimais (flutuantes). Ex: 25, 34, 48, 3.14, 1.99, etc.
- String (texto): representa sequências de caracteres. Pode ser utilizado para texto simples ou multi-linha. Ex: “José”, “Um bombom para cada nota maior que 9 em prova”.
- Boolean (booleano): representa valores lógicos, sendo true (verdadeiro) ou false (falso).
- Null (nulo) e undefined (indefinido): null é utilizado para indicar a ausência intencional de valor. undefined é atribuído automaticamente a variáveis que ainda não receberam valor.

Para além desses dados também existem os operadores:
- Aritméticos: + (adição), - (subtração), * (multiplicação), / (divisão), % (módulo), ** (potenciação).
- Atribuição: = (atribuição), += (atribuição com adição), -= (atribuição com subtração), *= (atribuição com multiplicação), /= (atribuição com divisão).

E para criar um código teremos a presença das variáveis, que podem ser declaradas em três estados:
- const: variáveis que recebem um único valor na sua declaração, sem a possibilidade de troca depois.
- let: variáveis locais que podem ou não receber um valor na declaração e que podem receber atribuições depois.
- var: semelhante a let, porém são variáveis globais, podem ser chamadas em qualquer lugar do código.

Por padrão a estrutura de um algoritmo possui:
- Entrada de dados: onde são recebidos todos os dados e variáveis do programa.
- Processamento: onde são feitos todos os cálculos.
- Saída de dados: onde é apresentado o resultado final do programa.

Um exemplo de código nesta estrutura é:

```
<script>
  // Entrada de dados
  let x = 5;
  let y = 8;

  // Processameno
  let soma = x + y;

  // Saída de dados
  document.write(`O resultado da soma é $(soma)`);
</script>
```
