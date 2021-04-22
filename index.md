---
layout: lesson
root: .
permalink: index.html
---

A melhor forma de aprender a programar é fazer algo útil,
então essa introdução ao Python será construída para realizar uma tarefa científica comum:
**análise de dados**.


### Artrite inflamatória
Estamos estudando **inflamação em pacientes** que receberam um novo tratamento para artrite.

Temos 60 pacientes, que tiveram seus níveis de inflamação registrados por 40 dias.
Queremos analisar esses registros para estudar o efeito de um novo tratamento para artrite.

Para ver como o tratamento afetou os pacientes em geral, gostaríamos de:

1. Calcular a inflamação média por dia entre todos os pacientes.
2. Plotar o resultado para discutir e compartilhar com colegas.

<!-- ### Arthritis Inflammation
We are studying **inflammation in patients** who have been given a new treatment for arthritis. 

There are 60 patients, who had their inflammation levels recorded for 40 days.
We want to analyze these recordings to study the effect of the new arthritis treatment.

To see how the treatment is affecting the patients in general, we would like to:

1. Calculate the average inflammation per day across all patients.
2. Plot the result to discuss and share with colleagues. -->

![3-step flowchart shows inflammation data records for patients moving to the Analysis step
where a heat map of provided data is generated moving to the Conclusion step that asks the
question, How does the medication affect patients?](
fig/lesson-overview.svg "Lesson Overview")

### Formato dos dados
Os conjuntos de dados são armazenados em
[arquivos separados por vírgula]{{ page.root }}/reference/#comma-separated-values), no formato CSV:

<!--### Data Format
The data sets are stored in
[comma-separated values]({{ page.root }}/reference.html#comma-separated-values) (CSV) format:-->

As três primeiras linhas do nosso arquivo parecem com isso:
<!-- The first three rows of our first file look like this: -->
~~~
0,0,1,3,1,2,4,7,8,3,3,3,10,5,7,4,7,7,12,18,6,13,11,11,7,7,4,6,8,8,4,4,5,7,3,4,2,3,0,0
0,1,2,1,2,1,3,2,2,6,10,11,5,9,4,4,7,16,8,6,18,4,12,5,12,7,11,5,11,3,3,5,4,4,5,5,1,1,0,1
0,1,1,3,3,2,6,2,5,9,5,7,4,5,4,15,5,11,9,10,19,14,12,17,7,12,11,7,4,2,10,5,4,2,2,3,2,2,1,1
~~~
Onde cada número representa o número de sensações inflamatórias que um paciente sofreu em um dado dia.
Por exemplos, o valor "6" na linha 3, coluna 7 do conjunto de dados acima significa que o terceiro
paciente estava sofrendo de inflamação seis vezes no sétimo dia do estudo clínico.
<!-- Each number represents the number of inflammation bouts that a particular patient experienced on a
given day. For example, value "6" at row 3 column 7 of the data set above means that the third
patient was experiencing inflammation six times on the seventh day of the clinical study. -->

Então, queremos:
<!-- So, we want to: -->

1. Calcular a média de inflamação por dia entre todos os pacientes.
2. Plotar o resultado e discutir os dados com o colega.
<!-- 1. Calculate the average inflammation per day across all patients.
2. Plot the result to discuss and share with colleagues. -->

Para fazer tudo isso, teremos que aprender um pouco de programação.
<!-- To do all that, we'll have to learn a little bit about programming. -->

> ## Pré requisitos
> Você precisa entender os conceitos de **arquivos** e **diretórios** e como iniciar um interpretador
> Python antes de começar essa aula. Essa aula menciona o Jupyter Notebook, mas você
> pode usar qualquer interpretador Python mencionado no [Setup](setup/).
>
> Os comandos dessa aula são em **Python 3**.
{: .prereq}

### Começando
Para começar, siga as instruções na página de "[Setup](setup/)" para fazer download dos
dados e instalar um interpretador Python.
<!-- ### Getting Started
To get started, follow the directions on the "[Setup](setup/)" page to download data
and install a Python interpreter. -->

{% include links.md %}
