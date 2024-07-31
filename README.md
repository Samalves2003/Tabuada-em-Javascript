# Tabuada em JavaScript
## Estudos de JS


Nos meus estudos de JavaScript, desenvolvi um programa de tabuada utilizando estruturas de condição e loop while. Este projeto é uma aplicação prática do que estou aprendendo com Gustavo Guanabara e tem sido uma ótima maneira de consolidar meus conhecimentos.
## Estrutura do Código
O código consiste em uma função chamada tab(), que é responsável por gerar a tabuada de um número inserido pelo usuário. A função utiliza os seguintes elementos e conceitos:

### Seleção de Elementos do DOM

 - let num = document.getElementById('txtn'): Captura o valor digitado pelo usuário no campo de texto.
 - let tab = document.getElementById('seltab'): Seleciona o elemento <select> onde a tabuada será exibida.

### Estrutura de Condição

- if (num.value.length == 0): Verifica se o usuário não digitou nenhum número e, se for o caso, exibe um alerta solicitando a inserção de um número.
- else: Caso um número tenha sido inserido, a execução continua para gerar a tabuada.

### Conversão de Tipos

- let n = Number(num.value): Converte o valor inserido no campo de texto de string para número, permitindo cálculos matemáticos.

### Loop While

- let c = 1: Inicializa o contador c com o valor 1.

- while(c <= 10): Loop que itera de 1 a 10, gerando os resultados da tabuada.

- let item = document.createElement('option'): Cria um novo elemento <option> para ser adicionado ao <select>.

- item.text = ${n} x ${c} = ${n*c}: Define o texto do item como o resultado da multiplicação do número inserido pelo contador.

- tab.appendChild(item): Adiciona o item criado ao elemento <select>.
c++: Incrementa o contador para a próxima iteração.

- A função verificar() é a principal responsável por validar os dados do usuário, calcular a idade, determinar o gênero e exibir a imagem correspondente.

## Aplicação Prática
Esse exercício foi essencial para aplicar conceitos básicos de JavaScript, como manipulação do DOM, condicionais, conversão de tipos e loops. Além disso, a prática me ajudou a entender como integrar JavaScript com HTML para criar uma interface interativa, o que é fundamental para o desenvolvimento web.

Com esse projeto, dei mais um passo em direção ao domínio do JavaScript, complementando minha stack de desenvolvimento web e aprimorando minhas habilidades práticas. Estou ansioso para continuar explorando novos desafios e avançando nos meus estudos!
