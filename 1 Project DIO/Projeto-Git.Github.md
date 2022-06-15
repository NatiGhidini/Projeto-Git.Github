 #  <sub><cite> Introdução ao Git e GitHub </cite></sub> 











![Git logo](C:\Users\Natiele\Documents\GitHub\Projeto-Git.Github\1 Project DIO\Imagens do Projeto\logo.png)

Ferramenta que gerencia diferentes versões de um arquivo e projetos de desenvolvimento de software.

*Pontos Positivos do Git*

- Controle de versão 
- Melhoramento de código
- Armazenamento em nuvem
- Reconhecimento 

---------------------------------------------------------------------------

## Instalação do Git 

Através do link a baixo, opite pelo sistema operacional da sua máquina, e execulte conforme os passos.

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

Comandos básicos para navegação para determinado sistema.

[Windows](https://www.digitalhouse.com/br/blog/principais-comandos-git/)

[Linux](https://www.hostinger.com.br/tutoriais/comandos-linux)

[Mac](https://www.apptuts.net/tutorial/mac/comandos-uteis-terminal-do-mac/)

---------------------------------------------------------------------------

### O que é um repositório Git?

  Um repositório do Git é um armazenamento virtual para projetos. Ele permite que você salve versões do código, que você pode acessar quando precisar.

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

   Criar uma pasta de modo costumeiro, para que seja armazenado e organizado os projetos          desenvolvidos.

![Pasta do Projeto](C:\Users\Natiele\Documents\GitHub\Projeto-Git.Github\1 Project DIO\Imagens do Projeto\Imagem 1.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 2: Subdiretório no Git

   Através do aplicativo Git Bash será execultado os comandos a seguir:

![Abrindo Git Bash ](C:\Users\Natiele\Documents\GitHub\Projeto-Git.Github\1 Project DIO\Imagens do Projeto\Imagem 2.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 3: Criação

-  Criando um subdiretório:

~~~~git init "nome da  pasta"
Comando criar
~~~~

![Exemplo](C:\Users\Natiele\Documents\GitHub\Projeto-Git.Github\1 Project DIO\Imagens do Projeto\Imagem 3.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 3: Abrindo Subdiretório no Git

- Entrar no subdiretório:

~~~ cd "nome da pasta"
Comando entrar
~~~

![Exemplo](C:\Users\Natiele\Documents\GitHub\Projeto-Git.Github\1 Project DIO\Imagens do Projeto\Imagem 4.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 4: Formando um Documento 

- Criação de um arquivo de texto:

~~~echo "nome do arquivo" > "nome do arquivo" .txt
Comando criar        
~~~

~~~dir + enter
Comando para mostar onde o arquivo esta armazenado
~~~



![Exemplo](C:\Users\Natiele\Documents\GitHub\Projeto-Git.Github\1 Project DIO\Imagens do Projeto\Imagem 5.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 5: Abrindo o Arquivo com o Typora

- Iniciando o desenvolvimento do Projeto.

  Abrindo o documento de texto com o <kbd>Typora</kbd>

![Exemplo](C:\Users\Natiele\Documents\GitHub\Projeto-Git.Github\1 Project DIO\Imagens do Projeto\Imagem 6.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 6: Cofiguração Inicial 

- Configurações que o Git nos solicita 

  ~~~~ git config --global user.email "e-mail" / git config --global user.name adicionar o seu nome
  Comando Config
  ~~~~

  ![Exemplo](C:\Users\Natiele\Documents\GitHub\Projeto-Git.Github\1 Project DIO\Imagens do Projeto\Imagem 7.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 7: Fixando o Projeto no GitHub

- Abrindo o Projeto no Git.

  ~~~~git add *
  Comando Fixação 
  ~~~~

  ![Exemplo](C:\Users\Natiele\Documents\GitHub\Projeto-Git.Github\1 Project DIO\Imagens do Projeto\Imagem 8.jpg)


##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 8: Consolidando o Projeto 

- Capturando o estado do projeto naquele momento.

 ~~~git commit -m "Primeiro Commint"
 Comando Commint
 ~~~

![Exemplo](C:\Users\Natiele\Documents\GitHub\Projeto-Git.Github\1 Project DIO\Imagens do Projeto\Imagem 9.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 9: Projeto Original 

- clRegistrando o projeto original no GitHub

~~~git remote add origin https://github.com/usuario/rails-girls.git
Comando do Projeto
~~~

![Exemplo](C:\Users\Natiele\Documents\GitHub\Projeto-Git.Github\1 Project DIO\Imagens do Projeto\Imagem 10.jpg)

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 10: Criando repositório diretamente no GitHUb

  Perfil -> Seus repositórios (Your repositories) -> Novo (New) -> Nome do repositório (Repository    name) -> Criar repositório (Create Repository)

 *Após a finalização o GitHub lhe dará uma https*

##### --------------------------------------------------------------------------------------------------------------------------------------------

#### Passo 11: Enviando o Conteúdo ao GitHub

- Adicionando o conteúdo do repositório local (Git) para o repositório remoto (GitHub).

  ~~~~git remote add origin https://github.com/Exemplo/Exemplo.git/ git branch -M main/ git push -u origin main
  Comando Push

![Exemplo](C:\Users\Natiele\Documents\GitHub\Projeto-Git.Github\1 Project DIO\Imagens do Projeto\Imagem 11.jpg)

<mark>Atenção o GitHub solicitará a senha pessoal do seu acesso, para Authentication</mark>.



