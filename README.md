# Programando com Python
Esse repositório é uma tradução livre [do material oficial](https://github.com/swcarpentry/python-novice-inflammation).
A tradução ainda está nos estágios iniciais e contribuições são bem-vindas.

[![GitHub release][shields_release]][swc_py_releases]
[![Create a Slack Account with us][create_slack_svg]][slack_heroku_invite]
[![Slack Status][slack_channel_status]][slack_channel_url]

Uma introdução ao Python para não-programadores usando dados de inflamação.

## Sobre a aula

Essa aula ensina programadores iniciantes a escrever código modular para executar análise
de dados usando Python. A ênfase, no entanto, em ensinar princípios de programação independente
de linguagem, como automação com loops e encapsulamento com funções, vide
[Melhores práticas para computação científica][best-practices] e
[Práticas suficientes em computação científica][good-practices] para ler mais.

O exemplo usado nessa aula analisa um conjunto de 12 arquivos com dados simulatos de inflamação,
coletados de um estudo de um novo tratamento para artrite. É demonstrada uma forma de melhorar a análise,
automatizando-a com funções invés de repetir os passos da análise manualmente.

\*\* O preview dessa tradução, antes da publicação, está disponível em [aqui.][index]

Essa aula também está disponível em [R][R] e [MATLAB][MATLAB] (somente em inglês).

## Episódios

| # |  Episódio | Tempo | Pergunta(s) |
|--:|:---------|:----:|:------------|
| 1 | [Fundamentos de Python][episode01] | 30 | O que são tipos básicos de dados no Python<br>Como posso criar uma nova variável em Python?<br>Consigo mudar o valor associado a uma variável depois de cria-la? |
| 2 | [Analisando Dados de Pacientes][episode02] | 90 | How can I process tabular data files in Python? |
| 3 | [Visualizando Dados Tabulares][episode03] | 90 | Como eu posso processar arquivos de dados tabulares em Python? |
| 4 | [Repetindo Ações com Laços][episode04] | 30 | Como eu posso fazer as mesmas operações em muitos valores diferentes? |
| 5 | [Armazenando Muitos Valores em Listas][episode05] | 30 | Como eu posso armazenar muitos valores juntos? |
| 6 | [Analisando Dados em Muitos Arquivos][episode06] | 20 | Como eu posso fazer as mesmas operações em muitos arquivos diferentes? |
| 7 | [Fazendo Escolhas][episode07] | 30 | Como meus programas podem fazer coisas diferentes baseados em valores de dados? |
| 8 | [Criando Funções][episode08] | 30 | Como eu posso definir novas funções?<br>Qual é a diferença entre definir e chamar uma função?<br>O que acontece depois que eu chamo uma função? |
| 9 | [Erros e Exceções][episode09] | 30 | Como o Python reporta erros?<br>Como eu posso lidar com erros em programas Python? |
|10 | [Programação Defensiva][episode10] | 30 | Como eu posso tornar meus programas mais confiáveis? |
|11 | [Debuggando][episode11] | 30 | Como eu posso debuggar meu programa? |
|12 | [Programas de Linha de Comando][episode12] | 30 | Como eu posso contribuir para escrever programas Python que funcionem como linhas de comando Unix? |


## Contribuindo

Nós apreciamos todas as contribuições para melhorar a aula!
Responsáveis farão seu melhor para ajudar se você tiver qualquer pergunta,
preocupação, ou sentir alguma dificuldade com isso.

Gostaríamos que você se familiarizasse com nosso [Guia de Contribuição](CONTRIBUTING.md)
e deem uma olhada nas [orientações mais detalhadas][lesson-example] para formatação adequada,
formas de renderizar a aula localmente, e até como escrever novos episódios!

**Nota do tradutor**: Essa é uma tradução livre do material original, porém as regras de contribuição
são as mesmas.

## Responsáveis

Responsáveis pela aula são [Trevor Bekolay][trevor_bekolay], [Maxim Belkin][maxim_belkin],
[Anne Fouilloux][anne_fouilloux], [Lauren Ko][lauren_ko], [Valentina Staneva][valentina_staneva],
[Mike Trizna][mike_trizna], e o [criador][swc_history] of Software Carpentry:
[Greg Wilson][greg_wilson]

Responsável pela tradução para português é [Vini Salazar][vini_salazar].

## Autores
Uma lista de contribuidores para a aula pode ser encontrada em [AUTHORS](AUTHORS)

## License
Instructional material from this lesson is made available under the
[Creative Commons Attribution][cc-by-human] ([CC BY 4.0][cc-by-legal]) license. Except where
otherwise noted, example programs and software included as part of this lesson are made available
under the [MIT license][mit-license]. For more information, see [LICENSE.md](LICENSE.md).

## Citation
To cite this lesson, please consult with [CITATION](CITATION).

## About Software Carpentry

Software Carpentry is a volunteer project that teaches basic computing skills to researchers since
1998. More information about Software Carpentry can be found [here][swc-about].

## About The Carpentries

The Carpentries is a fiscally sponsored project of [Community Initiatives][community-initiatives], a
registered 501(c)3 non-profit organisation based in California, USA. We are a global community
teaching foundational computational and data science skills to researchers in academia, industry and
government. More information can be found [here][cp-about].

[lesson-example]: https://carpentries.github.io/lesson-example
[anne_fouilloux]: https://github.com/annefou
[lauren_ko]: https://github.com/ldko
[maxim_belkin]: https://github.com/maxim-belkin
[mike_trizna]: https://github.com/MikeTrizna
[trevor_bekolay]: http://software-carpentry.org/team/#bekolay_trevor
[valentina_staneva]: http://software-carpentry.org/team/#staneva_valentina
[greg_wilson]: https://github.com/gvwilson
[vini_salazar]: https://github.com/vinisalazar
[swc_history]: https://software-carpentry.org/scf/history/
[best-practices]: http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1001745
[good-practices]: http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510
[R]: https://github.com/swcarpentry/r-novice-inflammation
[MATLAB]: https://github.com/swcarpentry/matlab-novice-inflammation
[shields_release]: https://img.shields.io/github/release/swcarpentry/python-novice-inflammation.svg
[swc_py_releases]: https://github.com/swcarpentry/python-novice-inflammation/releases
[create_slack_svg]: https://img.shields.io/badge/Create_Slack_Account-The_Carpentries-071159.svg
[slack_heroku_invite]: https://swc-slack-invite.herokuapp.com
[slack_channel_status]: https://img.shields.io/badge/Slack_Channel-swc--py--inflammation-E01563.svg
[slack_channel_url]: https://swcarpentry.slack.com/messages/C9Y0L6MF0
[travis_svg]: https://travis-ci.org/swcarpentry/python-novice-inflammation.svg?branch=gh-pages
[travis_url]: https://travis-ci.org/swcarpentry/python-novice-inflammation
[episode01]: https://vinisalazar.github.io/python-iniciante-inflamacao/01-intro/index.html
[episode02]: https://vinisalazar.github.io/python-iniciante-inflamacao/02-numpy/index.html
[episode03]: https://vinisalazar.github.io/python-iniciante-inflamacao/03-matplotlib/index.html
[episode04]: https://vinisalazar.github.io/python-iniciante-inflamacao/04-loop/index.html
[episode05]: https://vinisalazar.github.io/python-iniciante-inflamacao/05-lists/index.html
[episode06]: https://vinisalazar.github.io/python-iniciante-inflamacao/06-files/index.html
[episode07]: https://vinisalazar.github.io/python-iniciante-inflamacao/07-cond/index.html
[episode08]: https://vinisalazar.github.io/python-iniciante-inflamacao/08-func/index.html
[episode09]: https://vinisalazar.github.io/python-iniciante-inflamacao/09-errors/index.html
[episode10]: https://vinisalazar.github.io/python-iniciante-inflamacao/10-defensive/index.html
[episode11]: https://vinisalazar.github.io/python-iniciante-inflamacao/11-debugging/index.html
[episode12]: https://vinisalazar.github.io/python-iniciante-inflamacao/12-cmdline/index.html
[community-initiatives]: https://communityin.org
[cp-about]: https://carpentries.org/about
[swc-about]: https://software-carpentry.org/about/
[mit-license]: https://opensource.org/licenses/mit-license.html
[cc-by-human]: https://creativecommons.org/licenses/by/4.0/
[cc-by-legal]: https://creativecommons.org/licenses/by/4.0/legalcode
[index]: http://vinisalazar.github.io/python-iniciante-inflamacao/

