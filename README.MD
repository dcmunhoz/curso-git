## Curso Git e Github

Este repositorio é apenas uma acompanhamento do curso de Git e Github

## Configuração do Git
Para configurar o git, usa-se o comando:
```
git config --global [campo.valor] "valor do campo"
```

## Inicializar um repositorio Git
Para inicializar o repositorio devemor entrar na raiz do projeto e executar o comando:
```
git init
```

## Verificar o status do repositorio
Para verificar o status do repositorio, utilizamos o comando:
```
git status
```
Esse comando mostra toda a situação do repositorio, é exibido os arquivos que não então fazendo parte do git, os que foram alterados e os que já estão prontos para serem commitados

## Adicionar arquivos
para adicionar os arquivos untrackeds na area de modificações para commits, utiliza-se:
```
git add [nome-arquivo]
git add [.] (adiciona todos os arquivos)
```

## Criar um Commit
Para isso, basta utilizar o seguinte comando:
```
git commit -m "Add Readme"
```

## Visualizar logs
Podemos visualizar os logs de 2 formas, a primeira é uma visão completa e a segunda uma versão simplificada:
```
git log (Visão completa)
git log --oneline (Versão simplificada)
git log --graph (Exibe a arvore de branches)
```

## Exibir modificações
Para exibir as modificações de um arquivo antes de fazer um commit, utilizamos o comando:
```
git diff
```

## Desfazendo as coisas
Para desfazer algo utilizamos alguns comandos dependendo da situação.
Caso eu edite o arquivo porem não tenha adiciona ele para commit, posso utilizar o comando:
```
git checkout [nome-arquivo]
```

Caso eu tenha adicionado um arquivo para commit e queira desfazer, basta usar:
```
git reset HEAD
```

Ou então, caso eu já tenha feito um commit, porem preciso desfazer o commit, utiliza-se o comando:
```
git reset --soft [HASH] (Volta o arquivo em staged, pronto para ser comitado)
git reset --mixed [HASH] (Volta o arquivo antes do staged, somente com a modificação feita)
git reset --hard [HASH] (Apaga todas as edições feita)
```

## Relacionando Repositório Remoto
Para adicionar um repositório remodo, apos crialo, copie o link de clone e utilize o seguinte comando:
```
git remote add [nome-referencia-repositorio] [link-repositório]
ex: git remote add github https://github.com/dcmunhoz/curso-git.git
```