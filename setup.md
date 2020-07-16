---
layout: page
title: Setup
permalink: /setup/index.html
root: ..
---

### Install Python

Nessa lição usaremos Python 3 com algumas de suas bibliotecas científicas.
Apesar de ser possível instalar apenas o Python 3 e instalar as bibliotecas necessárias "manualmente",
nós recomendamos instalar o [Anaconda][workshop-template-python-instructions], uma distribuição de Python
que possui tudo que iremos utilizar.

&nbsp; <!-- vertical spacer -->

### Obtain lesson materials

1. Baixe [python-novice-inflammation-data.zip][zipfile1]
        e [python-novice-inflammation-code.zip][zipfile2].
2. Crie uma pasta chamada `swc-python` no seu Desktop.
3. Transfira os arquivos baixados para esta nova pasta.
4. Descompacte os arquivos.

Agora você verá duas novas pastas, chamadas `data` e `code` no diretório `swc-python` do seu 
Desktop.

&nbsp; <!-- vertical spacer -->

### Navegue até a pasta `data`

Se você estiver usando alguma aplicação com um shell Unix, como o Terminal no macOS, o console ou o terminal no
Linux ou [Git Bash](https://gitforwindows.org/) no Windows, execute o seguinte o comando:

~~~
$ cd ~/Desktop/swc-python/data
~~~
{: .source}

No Windows, você pode usar o Prompt de Comando. A maneira mais simples de inicializá-lo é apertando
<kbd>Windows Logo Key</kbd>+<kbd>R</kbd>, digitando `cmd` e apertando <kbd>Enter</kbd>. No Prompt de
Comando, execute o seguinte comando para navegar até a pasta `data`:

~~~
$ cd /D %userprofile%\Desktop\swc-python\data
~~~
{: .source}

&nbsp; <!-- vertical spacer -->

### Opção 1: Launch Plain Vanilla Python interpreter

To start working with Python, we need to launch a program that will interpret and execute our Python
commands. To launch a "plain vanilla" Python interpreter, execute:
~~~
$ python
~~~
{: .source}

If you are using Git Bash on Windows, you have to call Python _via_ `winpty`:
~~~
$ winpty python
~~~
{: .source}

&nbsp; <!-- vertical spacer -->

### Opção 2: Start Jupyter notebook

Jupyter notebooks provide a browser-based interface for working with Python.  If you would like to
use a notebook during the lesson, make sure to install [Anaconda
Distribution](http://carpentries.github.io/workshop-template/#python).

To start a Jupyter server, execute:
~~~
$ jupyter notebook
~~~
{: .source}

Then create a new notebook by clicking "New" button on the right and selecting "Python 3" from the
drop-down menu:

![](../fig/new-notebook.png)

&nbsp; <!-- vertical spacer -->

### Opção 3: Start IPython interpreter

IPython is an alternative solution situated somewhere in between the plain vanilla Python
interpreter and Jupyter notebooks.  It provides an interactive command-line based interpreter with
various convenience features and commands.  You should have IPython on your system if you installed
[Anaconda Distribution](http://carpentries.github.io/workshop-template/#python).

To start using IPython, execute:
~~~
$ ipython
~~~
{: .source}

[zipfile1]: {{ page.root }}/data/python-novice-inflammation-data.zip
[zipfile2]: {{ page.root }}/code/python-novice-inflammation-code.zip
[workshop-template-python-instructions]: https://carpentries.github.io/workshop-template/#python
