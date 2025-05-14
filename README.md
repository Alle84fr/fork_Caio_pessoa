[Arquitetura](#arquitetura)
&nbsp;&nbsp;
[Tecnologias](#tecnologias)
&nbsp;&nbsp;
[Passo a passo](#passo-a-passo)
<br>
[Endpoints ](#endpoints)
&nbsp;&nbsp;
[Estrutura do projeto](#estrutura-do-projeto)
&nbsp;&nbsp;
[Autores](#autores)

&nbsp;
&nbsp;

# 🛫Flask-microservice-mvc🛬

Repositório fork - projeto Flask-microservice-mvc - Caio-ireno.
Este repositório possui infromações sobre professores, alunos e disciplinas.
<br>
<br>
## 🧰Arquitetura

Esta api gerencia sitemas de uma faculdade tendo as entidades professores, alunos e turmas/disciplina.
Este microsserviço faz parte de outro sistema que devem ser executados simultaneamente:

<br>[Projeto original | Caio-ireno](https://github.com/caio-ireno/Flask-microservice-mvc.git)
<br>[fork_Caio_servico | Alle84fr](https://github.com/Alle84fr/fork_Caio_servico.git)
<br>
<br>

## 🔌Tecnologias
<br>
<img src="imagens\image-5.png" alt="alt text" width="70"/> 
<img src="imagens\image-9.png" alt="alt text" width="80" />
<img src="imagens\image-7.png" alt="alt text" width="150" />
<img src="imagens\image-8.png" alt="alt text" width="150"/>
<br>
<br>

## 🥾Passo a passo

#### 1° No Github copiar o url e o https 

https://github.com/Alle84fr/fork_caio_pessoa.git
<br>
#### 2° No editor de código desejado clonar o repositório

No terminal 
- criar uma pasta - mkdir nomeDaPasta
- cd nomeDaPasta
- code .
- ctrl + j para abrir terminal
- git clone url
&nbsp;
#### 3° Instalar as dependências

No terminal
- pip install -r requirements.txt
&nbsp;
#### 4° Executar API

No terminal
- python pessoa_service/app.py
    retorno será http://localhost:5001
<br>
<br>

## 🌐Endpoints 

Todos médoto get

- ttp://localhost:5001/professores
- ttp://localhost:5001/alunos
- ttp://localhost:5001/leciona
<br>
<br>

## 🧱Estrutura do projeto

<br>fork_caio_pessoa/
<br>|
<br>|-- imagens/
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- imagem-5.png
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- imagem-7.png
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- imagem-8.png
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- imagem-9.png
<br>|     
<br>|-- pessoa_service/
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- controllers
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- pessoa_controller.py
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- models/
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- pessoa_model.py
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- services/
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- pessoa_service_client.py
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- app.py
<br>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- config.py
<br>|
<br>|__README.md
<br>
<br>

## 📝Autores

Caio Ireno – Projeto educativo de arquitetura com Flask e microsserviços.
Alessandra FR - Readme.md - Objetivo é ler e ver como o projeto funciona e escrever um README  mais detalhado possível.
