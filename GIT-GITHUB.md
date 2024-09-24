# Git

Git é um sistema de controle de versão que permite gerenciar alterações de um projeto, facilitando o trabalho colaborativo. Armazenando diferentes versões do projeto, permitindo a recuperação e comparação de históricos de alterações, trazendo segurança e ajudando o trabalho cooperativo.

## Palavras-chave

- **Repositório**: Local onde o histórico de versões do projeto é armazenado.
- **Branch**: "Gaveta" do projeto que permite desenvolver funcionalidades de forma isolada.
- **Commit**: Alteração no repositório.
- **Merge**: Junta as modificações de uma branch com outra.
- **Clone**: Cópia de um repositório remoto para o ambiente local.
- **Push**: Envio dos commits locais para o repositório remoto.
- **Pull**: "Baixa" as alterações do repositório remoto para o local.
- **Checkout**: Comando usado para trocar de branch.
- **Staging**: Área onde arquivos preparados para o commit são armazenados.

## Principais comandos do Git

| Comando | Descrição |
| :---: |---|
| `git init` | Inicializa um repositório Git no diretório atual|
| `git clone <url-do-repositório>` | Clona um repositório remoto |
| `git status` | Mostra o status das modificações no repositório |
| `git add ` | Adiciona o arquivo ao ap staging |
| `git add .` | Adiciona todos os arquivos ao staging |
| `git commit -m "mensagem"` | Cria um commit com a mensagem especificada |
| `git log` | Exibe o histórico de commits |
| `git reset --hard HEAD~1` | Remove o último commit e as alterações |
| `git branch <nome-da-branch>` | Cria uma nova branch |
| `git checkout <nome-da-branch>` | Troca para a branch especificada |
| `git checkout -b <nome-da-branch>`| Cria e troca para uma nova branch |
| `git merge <nome-da-branch>` | Faz merge da branch especificada com a branch atual |
| `git branch -d <nome-da-branch>` | Deleta a branch especificada |

---

