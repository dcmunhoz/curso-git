## Curso Git e Github

Este repositorio é apenas uma acompanhamento do curso de Git e Github

## Configuração do Git
Para configurar o git, usa-se o comando:
-- git config --global [campo.valor] "valor do campo"

## Inicializar um repositorio Git
Para inicializar o repositorio devemor entrar na raiz do projeto e executar o comando:
-- git init

## Verificar o status do repositorio
Para verificar o status do repositorio, utilizamos o comando:
-- git status
Esse comando mostra toda a situação do repositorio, é exibido os arquivos que não então fazendo parte do git, os que foram alterados e os que já estão prontos para serem commitados

## Adicionar arquivos
para adicionar os arquivos untrackeds na area de modificações para commits, utiliza-se:
-- git add [nome-arquivo]
-- git add [.] (adiciona todos os arquivos)

## Criar um Commit
Para isso, basta utilizar o seguinte comando:
-- git commit -m "Add Readme"

## Visualizar logs
Podemos visualizar os logs de 2 formas, a primeira é uma visão completa e a segunda uma versão simplificada:
-- git log (Visão completa)
-- git log --oneline (Versão simplificada)
-- git log --graph (Exibe a arvore de branches)

## Exibir modificações
Para exibir as modificações de um arquivo antes de fazer um commit, utilizamos o comando:
-- git diff