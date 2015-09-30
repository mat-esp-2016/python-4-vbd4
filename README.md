# Prática de Introdução ao Python II

Parte do curso
[Matemática Especial I](http://www.leouieda.com/matematica-especial/)
da [UERJ](http://www.uerj.br/).

Ministrado por [Leonardo Uieda](http://www.leouieda.com/).

## Objetivos

* Apresentar o Jupyter notebook
* Praticar os conceitos de programação com Python aprendidos nas aulas anteriores
* Aprender a carregar dados de arquivos

## Preparação

Nessa prática vamos utilizar o [Jupyter notebook](http://jupyter.org/)
para programar em Python. Vocês não precisarão utilizar editores de texto
(como Notepad++) e arquivos `.py`.

**Primeiro**, verifique que o Jupyter está instalado junto com
seu Anaconda. Para isso, rode o comando abaixo no bash:

    $ conda install jupyter

**Segundo**, clique no link abaixo para criar um repositório para seu grupo.
Você precisará logar em sua conta do Github.
O repositório não ficará mais em sua conta, e sim na conta compartilhada do
LAGEX [github.com/lagex](https://github.com/lagex/).
Você também precisará escolher um nome para o seu grupo (minísculo,
sem espaço ou caracter especial).
Pode colocar o que quiser (recomendo ser conservador para não se
atrapalhar depois).

**Terceiro**, os outros membros do grupo devem clicar no link acima também.
Cada um deve logar com sua própria conta do Github. Coloquem o nome do grupo
que foi criado pelo colega. Isso dará acesso *push* ao repositório para todos
vocês.

**Quarto**, peguem clones do respotório criado acima para cada membro do grupo.

**ATENÇÂO**: Todas as práticas serão feitas em repositórios e manejadas pelo git.
Prestem atenção se estão fazendo **commits e push com frequência**.
Isso pode evitar muita dor de cabeça no futuro.
Também é importante lembrar de **trocar de clones** quando trocar o membro
que está trabalhando. Caso contrário, os commits não sairão no seu nome.
Quando trocar o membro **deixe o outro amigo digitar**.
Não deixe que uma única pessoa faça commits por todos.
Professor não é tão cego quanto vocês pensam.

**Quinto**, coloque um arquivo no repositório chamado `alunos.txt` com o
**nome completo** de cada aluno do grupo.

## Jupyter notebooks

Os notebooks rodam dentro de um navegador de internet (Firefox, Chrome, Safari, etc).
Mas eles **não rodam via internet**. Eles rodam em seu computador.
Para utilizar o Jupyter, você precisa iniciar um servidor de notebook
no seu computador.
Isso soa mais complicado do que realmente é.

Para iniciar um servidor, abra o bash e digite:

    $ jupyter notebook

Espere um pouco até aparecer algo como:

    [I 10:50:47.370 NotebookApp] Serving notebooks from local directory: /home/leo
    [I 10:50:47.370 NotebookApp] 0 active kernels
    [I 10:50:47.370 NotebookApp] The IPython Notebook is running at: http://localhost:8888/
    [I 10:50:47.370 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).

Isso deve abrir o seu navegador padrão também em uma página no endereço
[http://127.0.0.1:8888](http://127.0.0.1:8888).
Essa página irá te mostrar as pastas que estão em seu computador
(a partir da pasta onde você rodou `$ jupyter notebook`).

Para abrir um notebook, navegue até seu clone do repositório
e abra um dos arquivos `.ipynb`.
Comece com o `jupyter-notebook-tour.ipynb`.
**Siga as instruções no notebook e fique a vontade para explorar**.
Lembre-se que não tem como "estragar de vez para todo o sempre"
algo que está sob controle de versão com o git.
Qualquer coisa, é só pegar outro clone.

## Tarefas

Após explorar o conteúdo de `jupyter-notebook-tour.ipynb`,
siga as instruções em `tarefa-intro-python-2.ipynb`.
As tarefas e **suas soluções devem estar contidas nesse notebook**.
Por isso, faça commits de suas mudanças ao notebook.

## Dicas

* Façam muitos **commits**. Quanto mais melhor.
* Não se esqueça do **push**.
* Utilize **mensagens de commit** descritivas. "Completei a tarefa 1" é melhor que
  "mudança".
* Escolha nomes descritivos para **variáveis**. "temperatura" é melhor que "a".
* **Descreva o que (e por que) você fez** em comentários e células de texto.
  Isso será muito útil quando você voltar a essa tarefa depois.
* Preste atenção aos **detalhes**. Leia as instruções com atenção.

## Entrega

Crie uma Issue em https://github.com/leouieda/matematica-especial/ com:

* Título: "Prática Python 2: Aluno 1, Aluno 2, Aluno 3"
* Indique a qual turma pertece
* Link para seu repositório
