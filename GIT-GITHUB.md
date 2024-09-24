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
| `git clone <repositório>` | Clona um repositório remoto |
| `git status` | Mostra o status das modificações no repositório |
| `git add <arquivo>` | Adiciona o arquivo ao staging |
| `git add .` | Adiciona todos os arquivos ao staging |
| `git commit -m "mensagem"` | Cria um commit com a mensagem especificada |
| `git log` | Exibe o histórico de commits |
| `git reset --hard` | Remove o último commit e as alterações feitas |
| `git branch <branch>` | Cria uma nova branch |
| `git checkout <branch>` | Troca para a branch especificada |
| `git checkout -b <branch>`| Cria e troca para uma nova branch |
| `git merge <branch>` | Faz merge da branch especificada com a branch atual |
| `git branch -d <branch>` | Deleta a branch especificada |

---

## GitHub

GitHub é uma plataforma de hospedagem baseada em Git que permite colaboração entre desenvolvedores. Além de armazenar repositórios, o GitHub possui funcionalidades como issues que ajuda no desenvolvimento de projetos em equipe, é amplamente utilizado por desenvolvedores.

### Principais funções do GitHub

- **Repositórios**: Armazena um projeto na nuvem.
- **Issues**: "Gerenciamento" de problemas, tarefas ou melhorias no projeto.
- **Fork**: Cópia de um repositório de outro usuário, tornando possível a colaboração ampla de repositórios públicos.
- **Suporte a markdown**: Suporte a documentos (como este) em formato Markdown para documentação.
- 
### Comandos Git com GitHub

| Comando | Descrição |
| :---: | --- |
| `git remote add origin <repositorio>` | Conecta um repositório local ao GitHub |
| `git push origin <branch>` | Envia as alterações para o GitHub |
| `git pull origin <branch>` | Baixa as alterações do repositório para o local |
| `git clone <repositório>` | Clona o repositório do GitHub para o local |