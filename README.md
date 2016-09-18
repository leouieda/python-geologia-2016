# ![Python para Geólogos](https://raw.githubusercontent.com/leouieda/python-geologia-2016/master/images/banner.png)

Curso da VII Semana Acadêmica de Geologia da UERJ (SAGEO).

**Professor:** [Leonardo Uieda](http://www.leouieda.com)


## Sobre o curso

O curso de computação será na forma de exemplos guiados, ao vivo, sem slides,
interativo e com desafios para os alunos.

Tópicos que serão abordados durante o curso:

* Como se comunicar com um computador (na linguagem Python)
* Carregando e visualizando dados
* Automatizando tarefas repetitivas
* Sobrevivência através de programação defensiva

O objetivo final é que o aluno saiba o que é possível através da programação e
que tenha uma ideia de como aplicá-los para tornar sua vida profissional mais
eficiente e menos frustrante e tediosa. Com a base do curso, o aluno deverá ser
capaz de saber o que deve procurar no Google quando se deparar com um desafio.
Espero que todos os alunos terminem o curso com ideias de como aplicar esses
conhecimentos em seu trabalho.


## Conduta

Eu espero uma conduta civil e amigável durante o curso. Não tolero
comportamento ofensivo durante as aulas, falta de respeito e nem a
ridicularização dos colegas.

Eu encorajo todos a perguntarem e engajarem com os colegas ao lado. Não existem
perguntas "bestas", "irrelevantes", "óbvias", etc. Não levem dúvidas para casa.


## O que instalar

Existem várias distribuições do Python disponíveis. Algumas vem somente com o
básico, outras vem com várias bibliotecas já instaladas. Eu uso e recomendo a
distribuição chamada Anaconda que vem com o Python e todas as bibliotecas
científicas que iremos usar (e muito mais).

Baixe e instale o [Anaconda](http://continuum.io/downloads).  Selecione o
instalador que reflete o seu sistema (Windows, Linux, Mac, 32 ou 64bits).
Tenha certeza de que está baixando a versão do **Python 3.5**, não a 2.7.


## Leitura recomendada

Existem diversos materiais para aprender Python na Internet. O melhor que eu já
encontrei que é voltado para cientistas é o
[Software Carpentry](http://software-carpentry.org/). Vale a pena aprender tudo
que eles tem a ensinar.

Outra excelente referência é o site
[Scipy Lectures](http://www.scipy-lectures.org/).

Os livros
[Effective Computation in Physics](http://shop.oreilly.com/product/0636920033424.do)
e [Think Python](http://shop.oreilly.com/product/0636920045267.do) são muito
bem recomendados.

Para os que gostam de jogos, [CheckIO](https://checkio.org/) é um jogo online
de programação em Python e JavaScript. Aprendizado com diversão, mais nerd do
que isso é difícil.

Se você é dos que são mais nerds do que isso (ou tem interesse em se tornar),
o [Python Challenge](http://www.pythonchallenge.com/) é um excelente jeito de
aprender recursos extremamente úteis do Python.


## Conteúdo

Vou seguir mais ou menos o material dos cursos
[Programming with Python](http://swcarpentry.github.io/python-novice-inflammation/)
e [Plotting and Programming in Python](http://swcarpentry.github.io/python-novice-gapminder/)
do Software Carpentry.
Farei uma mistura dos dois e usando dados de temperatura do Brasil ao invés dos
dados que eles utilizam.

Baixe um arquivo zip com os dados e todo o material desse curso:
[python-geologia-2016.zip](https://github.com/leouieda/python-geologia-2016/archive/master.zip)

Os dados foram baixados do site [Berkeley Earth](http://berkeleyearth.org/).
Cada arquivo corresponde a séria temporal de temperatura média mensal para uma
capital. O arquivo `brazil-TAVG-Trend.txt` corresponde aos dados médios para
todo Brazil.

O objetivo é que no final do curso vocês consigam:

* Carregar os dados no Python
* Fazer um gráfico parecido com o do Berkeley Earth (por exemplo
  http://berkeleyearth.lbl.gov/regions/brazil)
* Calcular médias e determinar uma tendência linear
* Repetir a análise para diversos arquivos diferentes de maneira automática

Para isso, vamos seguir o seguinte cronograma de atividades:

| **DIA 1** |
| Introdução |
| Primeiros passos: abrindo e fechando |
| Variáveis: números, texto e listas de coisas |
| Funções |
| *Intervalo de 15 min* |
| Bibliotecas |
| Lendo e manipulando dados com o numpy |
| Fazendo gráficos com o matplotlib |
| **DIA 2** |
| Recapitulando |
| Repetindo ações com `for` |
| Condicionais |
| *Intervalo de 15 min* |
| Leitura de dados de forma artesanal |
| Analisando nossos com numpy e scipy |
| *Encerramento* |


## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This content is licensed under a
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
