# Desafio Git/GitHub da DIO
Criando seu Primeiro Repositório no GitHub Para Compartilhar Seu Progresso.

## Links Uteis
- [HTML](https://www.w3schools.com/html/default.asp)
- [CSS](https://www.w3schools.com/css/default.asp)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/javascript)
- [Git](https://git-scm.com/)
- [React](https://reactjs.org/)
- [Node.js](nodejs.org)
- [MySQL](https://www.mysql.com/)


OBS: repositório criado para entrega do desafio.

## GUIA PRÁTICO
 Apenas um guia prático para quem está começar com git.

### Instalação
- Baixe o git para Linux/Unix (https://git-scm.com/download/linux)
- Baixe o git para Windows (https://git-scm.com/download/win)
- Baixe o git para MacOS (https://git-scm.com/download/mac)

## Configurações básicas
É importante nos identificarmos para o Git, informando nosso nome e
e-mail. no seu terminal, execute os comandos:
> git config --global user.name "Seu Nome"

> git config --global user.email seuemail@gmail.com

## Criando um novo repositório
Crie uma pasta ou abra o terminal no diretório e execute o comando:

                          git init

## Rastreando os arquivos
Podemos ver a situação dos arquivos no repositório Git com o comando:

                         git status

Você para adicionar arquivos no repositório devemos executar o seguinte comando:
                                                          
                         git add "nome do arquivo"

Para fazer adicionar todos os ficheiros de uma só vez executamos o seguinte comando:

                         git add *

## Enviando alterações
Para gravarmos as mudanças no repositório (fazer o commit), devemos executar o comando:

                        git commit -m "comentários das alterações que fizeste"

## Preparando seu projeto para o GitHub
Devemos agora apontar o repositório da nossa máquina para o repositório do GitHub.
                                                 
                        git remote add origin https://github.com/seunome/repositorio.git

## Enviando as alterações para o GitHub
Com o repositório remoto configurado, podemos enviar nossas mudanças para o GitHub basta executar o comando git push, da seguinte forma:

                         git push origin master


Com o comando anterior, enviamos as alterações para o repositório remoto configurado com o nome origin.
Forneça seu usuário e senha do GitHub quando solicitado. Deverá aparecer algo semelhante à seguinte saída:

Username for ’https://github.com’: username
Password for ’https://fulanodasilva@github.com’ 

## Obtendo um repositório
Para obter o código do projeto lá do GitHub, execute o comando <code>git clone</code> da seguinte forma:

                    git clone https://github.com/Edlavio/Edlavio.git

##### Não esqueça de alterar esse link para o do repositório que pretendes clonar.
  
## Criando uma branch
Para criarmos uma branch chamada <code>repo</code> basta executar:
 
                     git branch repo
##### Não será exibida nenhuma resposta. Se listarmos as branches com o comando <code>git branch</code>, aparecerá as nossas branches.

## Trocando de branch
Já criamos nossa branch <code>repo</code> mas ainda estamos na <code?>master</code>. Para trocarmos para a branch recentemente criada, devemos executar:

                      git checkout repo

## Deletando uma branch
Como não vamos usar a branch <code>master</code> se nós querer removê-la. Assim evitamos confusões e desperdício no nosso repositório.
Para deletar uma branch, devemos utilizar a opção <code>-d</code> do <code>git branch</code> executando comando:
                                                                       
                     git branch -d master

##### Não é possível remover uma branch enquanto estivermos nela. Por isso, devemos ir para outra branch. Para ir para a branch, devemos executar:

                     git checkout nomedobranch

