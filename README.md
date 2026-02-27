# curso-frontend
### EBAC

#GIT
## Versionamento
	-Histórico
	-Controle de versão
	-Quem alterou
        - Todos os arquivos
	-Evolução Continua


Arquivo A | Versão 1 | versão 2

Arquivo B | Versão 1 | versão 2

## Instalação do Git
https://git-scm.com/

Windows: https://git-scm.com/dowload/win
Linux (apt-get): sudo apt-get install git
Mac (brew): brew install git

## Criar conta no GitHub

## Clonar o Projecto
$ git clone https://github.com/Carlitos1995/curso-frontend.git

## Commits
Informações de alteração
 - após testando todo seu código
 -git  add *
 -git commit -m "com uma mensagem"
 -git push (utilizo para enviar informações para o Repositório)
 -git pull(puxar / trazer alterações do GitHub para minha máquina)

## GitFlow
Fluxo do Git


### Branchs
 São ramificações do codigo / versões paralelas

 -main / master (vai para produção, quando o projecto é publicado)
 - develop
 -DDD Definition of Done: critérios de aceite 
 -versionamento  (0.1.10, 0.2.11, 1.0.0)

 git ckeckout -b dev (cria uma branch)
  git ckeckout master (mudar de branch)

### Merge
Mescala de branchs

git merge main

### Pull Requests
Mescala de branchs no repositório
Permite Code Review
