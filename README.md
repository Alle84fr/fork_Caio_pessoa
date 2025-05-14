&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp;  [Arquitetura](#arquitetura)
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp; [Tecnologias](#tecnologias)
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; [Passo a passo](#passo-a-passo)
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Endpoints ](#endpoints)
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; [Estrutura do projeto](#estrutura-do-projeto)
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Autores](#autores)

&nbsp;
&nbsp;

# 🛫Flask-microservice-mvc🛬

Repositório fork - projeto Flask-microservice-mvc - Caio-ireno.
Este repositório possui infromações sobre professores, alunos e disciplinas.
&nbsp;

## 🧰Arquitetura

Esta api gerencia sitemas de uma faculdade tendo as entidades professores, alunos e turmas/disciplina.
Este microsserviço faz parte de outro sistema que devem ser executados simultaneamente:

[fork_Caio_servico | Alle84fr](https://github.com/Alle84fr/fork_Caio_servico.git)
&nbsp;

## 🔌Tecnologias
&nbsp;
&nbsp;&nbsp;&nbsp;<img src="imagens\image-5.png" alt="alt text" width="70"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="imagens\image-9.png" alt="alt text" width="80" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="imagens\image-7.png" alt="alt text" width="150" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="C:\Users\arfur\fork_caio_pessoa\imagens\image-8.png" alt="alt text" width="150" />
&nbsp;

## 🥾Passo a passo

#### 1° No Github copiar o url e o https 

https://github.com/Alle84fr/fork_caio_pessoa.git
&nbsp;
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
&nbsp;

## 🌐Endpoints 

todos médoto get

- ttp://localhost:5001/professores
- ttp://localhost:5001/alunos
- ttp://localhost:5001/leciona
&nbsp;

## 🧱Estrutura do projeto

fork_caio_pessoa/
|
|-- imagens/
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- imagem-5.png
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- imagem-7.png
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- imagem-8.png
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- imagem-9.png
|     
|-- pessoa_service/
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- controllers
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- pessoa_controller.py
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- models/
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- pessoa_model.py
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- services/
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- pessoa_service_client.py
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- app.py
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- config.py
|
|__README.md
&nbsp;

## 📝Autores

Caio Ireno – Projeto educativo de arquitetura com Flask e microsserviços.
Alessandra FR - Readme.md - Objetivo é ler e ver como o projeto funciona e escrever um README  mais detalhado possível.