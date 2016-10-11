# Prática de Introdução ao Python II

Parte do curso
[Matemática Especial I](http://www.leouieda.com/matematica-especial/)
da [UERJ](http://www.uerj.br/).

Ministrado por [Leonardo Uieda](http://www.leouieda.com/).

## Objetivos

* Praticar os conceitos de programação com Python aprendidos nas aulas anteriores
* Aprender a explorar e filtrar dados de arquivos de texto
* Manipulação de variáveis do tipo string
* Utilizar operadores condicionais

## Leitura recomendada

Vamos seguir de perto o material
[Programming with Python](http://swcarpentry.github.io/python-novice-inflammation/)
(ver as aulas "Creating Functions" e "Defensive Programming")
e
[Plotting and programming in Python](http://swcarpentry.github.io/python-novice-gapminder/)
do Software Carpentry.
Farei algumas modificações para ser mais voltado para o tipo de dados que
costumamos encontrar nas geociências.

Uma ótima referência para aprender a usar o numpy e matplotlib é o
[Scipy Lectures](http://www.scipy-lectures.org/).


## Tarefa

Utilize o link enviado para a [lista de
emails](https://github.com/mat-esp/about#informa%C3%A7%C3%B5es) para criar um
repositório para seu grupo ou se juntar a um grupo já criado.
Anote o link para o repositório criado para seu grupo. Vocês precisarão desse
link.

Clone o repositório do seu grupo para seu computador. Não se esqueça de
configurar o git para um dos membros do grupo (`git config --global user.name
"Fulado de Tal"` e `git config --global user.email fulado@gmail.com`).

Essa prática continua com os mesmo dados de temperatura que utilizamos na
prática [Python 2](https://github.com/mat-esp/python-2).

**IMPORTANTE**: tenha em mente o [checklist de
correção](https://github.com/mat-esp/about/blob/master/ISSUE_TEMPLATE.md#checklist-de-avalia%C3%A7%C3%A3o-do-professor)
quando fizer a tarefa. Não perca pontos de bobeira.
O site [pep8.org](http://pep8.org/) é uma boa referência para como escrever
código Python bem formatado.

Siga as instruções abaixo. Não se esqueça de fazer os commits e roda `git push`
para salvar seu trabalho.

1. Adicione no repositório um arquivo `alunos.txt` com os nomes completos de
   cada membro do grupo e seus nomes de usuário no github.com
2. Crie um Jupyter notebook chamado `python4.ipynb`. Todos os passos abaixo
   devem ser feitos nesse notebook. Use as células de texto do notebook para
   descrever o que você quis fazer com cada bloco de código.
3. Criar uma função que recebe o nome do arquivo de dado como argumento e retorne: a latitude e longitude da
   estação; o nome da primeira cidade mais próxima da estação de medida (`nearby cities`).
4. Criar uma função que recebe o nome do arquivo de dado como argumento e retorne:
   um numpy array da temperatura anual estimada, que será a soma da temperatura absoluta estimada (retirar do cabeçalho do arquivo) com
   a anomalia anual.
5. Faça gráficos da temperatura anual estimada para cada estação da pasta
   `dados` referente a uma cidade (não o do Brasil todo), com o título de cada gráfico contendo a latitude e longitude. 
   Os gráficos devem ser salvos com o nome da cidade extraída no item **3** em formato 
   `png`(caso o nome seja composto, substitua os espaços por `_`): ex.`Porto_Alegre.png`.

**BÔNUS**: Repetir o item **5** substituindo a temperatura absoluta estimada pela mensal absoluta estimada. 
Atenção: nesse caso é preciso usar a anomalia mensal respectiva de cada mês (`Month 1 = Jan`,`Month 2 = Fev` etc).
Para realizar essa tarefa será preciso usar condicionais (`if`) e loops (`for`).


## Entrega das soluções

A solução de cada prática será um repositório no [Github](http://github.com/)
com o código feito pelos alunos.

A entrega das soluções será feita criando uma
[Issue](https://guides.github.com/features/issues/)
no repositório da disciplina
[mat-esp/about](https://github.com/mat-esp/about).
Utilize o link abaixo para ir direto para as Issues:

https://github.com/mat-esp/about/issues

Cada grupo deve criar uma Issue para entregar cada prática.
A issue deverá seguir o padrão abaixo:

* Título: Deve conter o nome da prática seguido dos nomes dos integrantes do
  grupo e a qual turma pertencem (caso haja mais de uma). Ex: "Prática
  Integração: Bilbo, John, Arthur - Turma 1"
* Corpo: Deve conter o link para o repositório do grupo (ex:
  `https://github.com/mat-esp-2016/integracao-sociedade-42`) e qualquer
  comentário que achar necessário (ex: problemas com os commits, erros que foram
  arrumados depois, dificuldades, etc).


## License

All content can be freely used and adapted under the terms of the
[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

