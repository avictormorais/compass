# Objetivo
Este arquivo serve como uma "legenda" aos commits realizados nesta branch, que terão como inspiração o conventional commits, mas com um toque diferente por se tratar apenas de documentação.

## Lista de comandos

| Comando | Descrição | Inspiração (CC) |
| :---: | --- | :---: |
| add | Usado quando adicionado um novo documento ou conteúdo. | feat |
| fix | Usado quando for preciso corrigir conteúdo, seja por erro ortográfico ou semântico. | fix |
| update | Usado para atualizar alguma parte do documento, qualquer seja o motivo da atualização. | update |
| remove | Usado quando for preciso remover parte do documento. | remove |

*CC: [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/)*, especificação mencionada anteriormente tomada como exemplo.

## Padrões

Inspirado também no Conventional Commits, os commits realizados aqui seguirão a seguinte estrutura:

> tipo(escopo opcional): descrição

Onde o tipo deve ser um dos tipos de commits descritos anteriormente, o escopo podendo referenciar alguma parte específica do documento e a descrição um breve resumo das alterações feitas naquele commit.
#### Exemplos
> add: add kanban section.
> 
> fix(kanban): fix de word "bord" to "board".
> 
> update: change the example in the document.
> 
> remove(kanban): remove the image example.