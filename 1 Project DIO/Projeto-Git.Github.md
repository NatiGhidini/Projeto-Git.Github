 #  <sub><cite> Introdução ao Git </cite></sub> 



![Git logo](https://user-images.githubusercontent.com/107075512/174316754-3dbfb9fa-7eb7-4667-bf4d-7f857e46d075.png)


Ferramenta que gerencia diferentes versões de um arquivo e projetos de desenvolvimento de software.

*Pontos Positivos do Git:*

- Controle de versão 
- Melhoramento de código
- Armazenamento em nuvem
- Reconhecimento 

---------------------------------------------------------------------------

## Instalação do Git 

Através do link abaixo, opite pelo sistema operacional da sua máquina, e execute conforme os passos.

[Git Install](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git)

---------------------------------------------------------------------------

## Configuração do Git 

​    *Identificação*

   -Definir um nome de usuário e endereço de e-mail.

   Dentro do aplicativo "Git Bash", introduza os seguintes comandos: 

  **git config --global user.name "John Doe"**
  **git config --global user.email johndoe@example.com**

---------------------------------------------------------------------------

## Navegação Via Command  ##

Comandos básicos para navegação para determinado sistema:

[Windows](https://www.digitalhouse.com/br/blog/principais-comandos-git/)

[Linux](https://www.hostinger.com.br/tutoriais/comandos-linux)

[Mac](https://www.apptuts.net/tutorial/mac/comandos-uteis-terminal-do-mac/)

---------------------------------------------------------------------------

### O que é um repositório Git?

  Um repositório do Git é um armazenamento virtual para projetos, ele permite que você salve versões do código que você pode acessar quando precisar.

###  --------------------------------------------------------------------------------------------

  <u>_Importante_</u>

   Aplicativo de edição de texto markdown, simples e convencional.

 <kbd>[Typora Download](https://typora.softonic.com.br/)</kbd>

  Informações sobre essa linguagem de marcação:

 <kbd> [Markdown](https://www.digitalhouse.com/br/blog/markdown/)</kbd>

 <kbd>[Guia Básico](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)</kbd>

### ---------------------------------------------------------------------------------------------

--------------------

## Criando um Repositório e Adicionando Arquivo



#### Passo 1:  Armazenamento  ####

- Criar uma pasta de modo costumeiro, para que seja armazenado e organizado os projetos  desenvolvidos.

![Pasta do Projeto](https://user-images.githubusercontent.com/107075512/174319147-bc8387a3-2afb-4400-87ad-d16836522609.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 2: Subdiretório no Git

- Através do aplicativo Git Bash será execultado os comandos a seguir:

![Abrindo Git Bash ](https://user-images.githubusercontent.com/107075512/174319066-c5eefb52-0961-4b5a-b336-ad4ee391a71c.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 3: Criação

-  Criando um subdiretório:

~~~~git init "nome da  pasta"
Comando criar ---> git init "nome da  pasta"
~~~~

![Exemplo](https://user-images.githubusercontent.com/107075512/174318996-fbe84937-bada-4438-9ced-443e20068688.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 4: Abrindo Subdiretório no Git

- Entrar no subdiretório:

~~~ cd "nome da pasta"
Comando entrar ---> cd "nome da pasta"
~~~

![Exemplo](https://user-images.githubusercontent.com/107075512/174318940-a37d4de0-a0de-4cb1-871f-df0b35d20b67.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 5: Formando um Documento 

- Criação de um arquivo de texto:

~~~echo "nome do arquivo" > "nome do arquivo" .txt
Comando criar ---> echo "nome do arquivo" > "nome do arquivo" .txt        
~~~

~~~dir + enter
Comando para mostar onde o arquivo esta armazenado ---> dir + enter
~~~

![Exemplo](https://user-images.githubusercontent.com/107075512/174318851-a6b64455-e077-48b5-b2c7-73c5ec67b4e2.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 6: Abrindo o Arquivo com o Typora

- Iniciando o desenvolvimento do Projeto.

  Abrindo o documento de texto com o <kbd>Typora</kbd>

![Exemplo](https://user-images.githubusercontent.com/107075512/174318764-4e4fd08c-7eb7-4797-b4b6-66d376bc0899.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 7: Cofiguração Inicial 

- Configurações que o Git nos solicita.

  ~~~~ git config --global user.email "e-mail" / git config --global user.name adicionar o seu nome
  Comando Config ---> git config --global user.email "e-mail" / git config --global user.name adicionar o seu nome
  ~~~~

  ![Exemplo](https://user-images.githubusercontent.com/107075512/174318650-cf399a5f-8f20-4316-8536-f95648ac8f3b.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 8: Fixando o Projeto no GitHub

- Abrindo o Projeto no Git.

  ~~~~git add *
  Comando Fixação ---> git add *
  ~~~~

  ![Exemplo](https://user-images.githubusercontent.com/107075512/174318546-912187c1-273a-439a-b70b-f265670c5cf3.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 9: Consolidando o Projeto 

- Capturando o estado do projeto naquele momento.

 ~~~git commit -m "Primeiro Commint"
 Comando Commit ---> git commit -m "Primeiro Commint"
 ~~~

![Exemplo](https://user-images.githubusercontent.com/107075512/174318481-768f5eb1-c0e3-4b89-9755-83cc21b0c113.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 10: Projeto Original 

- Registrando o projeto original no GitHub.

~~~git remote add origin https://github.com/usuario/rails-girls.git
Comando do Projeto ---> git remote add origin https://github.com/usuario/rails-girls.git
~~~

![Exemplo](https://user-images.githubusercontent.com/107075512/174318365-87aabac5-a183-4ca9-a2fb-f5e37af47f20.jpg)
##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 11: Criando repositório diretamente no GitHUb

  ~~~
  Perfil -> Seus repositórios (Your repositories) -> Novo (New) -> Nome do repositório (Repository    name) -> Criar repositório (Create Repository) 
  ~~~



 *Após a finalização o GitHub lhe dará uma https*

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 12: Enviando o Conteúdo ao GitHub

- Adicionando o conteúdo do repositório local (Git) para o repositório remoto (GitHub).

  ~~~~git remote add origin https://github.com/Exemplo/Exemplo.git/ git branch -M main/ git push -u origin main
  Comando Push ---> git remote add origin https://github.com/Exemplo/Exemplo.git/ git branch -M main/ git push -u origin main

![Exemplo](https://user-images.githubusercontent.com/107075512/174317762-177610ad-6bee-491b-95b5-d69c91983451.jpg)

<mark>Atenção o GitHub solicitará a senha pessoal do seu acesso, para Authentication</mark>.



