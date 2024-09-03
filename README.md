<h1 align="center"> Plataforma de Ensino</h1>

Você foi contratada(o) para criar um sistema de plataforma de ensino. Para isto você deve criar um
programa para ler os dados das aulas de um curso, e em seguida mostrar a duração total do curso, que é
a soma das durações de cada aula.
Cada aula pode ser um conteúdo em vídeo, ou então uma tarefa. Os dados de cada aula são:
Vídeo: título, url e duração em segundos
Tarefa: título, descrição e quantidade de questões
A duração (em segundos) de uma aula vídeo é a
própria duração do vídeo, e a duração de uma aula
tarefa é de cinco minutos por questão (exemplo: se a
tarefa possui 3 questões, então a duração da tarefa é
15 minutos).
Você deve representar os dados conforme modelo ao
lado. O método duration() na classe Lesson é um
método abstrato que retorna a duração da aula.
Você deve criar uma única lista do tipo
List<Lesson> para armazenar todas aulas. A
chamada do método duration() deve ser polimórfica.

<h2 align="center"> Modelo Conceitual </h2>

<p align="center">
  <img src="https://github.com/user-attachments/assets/978b9b6a-b739-4935-baa8-fb04b6b92521" alt="diagrama-uml">
</p>

<h2 align="center"> Exemplo</h2>

![exemplo](https://github.com/user-attachments/assets/bf69d7c7-ee5a-403a-97da-e3aa513b7113)

## CRITÉRIOS DE AVALIAÇÃO (TODOS DEVEM ESTAR CORRETOS):
1) Nomes de classes, atributos, métodos e argumentos respeitando o projeto, bem como as convenções
de nome para Java (classe com primeira letra maiúscula, e padrão "camel case" para atributos, variáveis
e métodos.
2) Implementação correta da classe abstrata e das heranças com sobreposição do método abstrato.
3) Programa principal contento apenas uma lista do tipo List<Lesson> para armazenar todas aulas.
4) Comportamento do programa e resultado dos cálculos corretos.

## Realização

[DevSuperior - Escola de programação](https://devsuperior.com.br/)

[![DevSuperior no Instagram](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/ig-icon.png)](https://instagram.com/devsuperior.ig) ![DevSuperior no Youtube](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/yt-icon.png)

