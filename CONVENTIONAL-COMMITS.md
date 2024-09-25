# Conventional Commits

Conventional Commits é uma padronização para mensagens de commit de forma simples e padronizada.

## Formato base

`<tipo>[escopo opcional]: <descrição>`

- O **tipo** corresponde ao tipo de alteração feito durante o commit;
- O **escopo opcional** corresponde a que parte do projeto foi afetado pelo commit;
- A descrição é um breve resumo sobre o commit, com finalidade de dar clareza ao que foi feito.
  
### Tipos comuns

- **feat**: Nova funcionalidade.
- **fix**: Correção de um bug.
- **docs**: Relacionado a documentação.
- **style**: Mudanças de estilo, sem alteração lógica.
- **refactor**: Refatoração de código.
- **test**: Relacionado a testes.
- **chore**: Alterações que não afetam o código.

## Exemplos:
- `feat: adicionar form de login`
- `fix(login): corrigir bug de autenticação`

---

### Breaking Changes

Usado para indicar mudanças que quebram a compatibilidade com versões anteriores. Para usar o breaking changes, usa-se a palavra `BREAKING CHANGE` na mensagem do commit ou na descrição.

### Outros tipos

Apesar da grande parte dos commits serem atendidos pela lista anterior, projetos podem ter seus própios tipos de commit, desde que siga o mesmo padrão de uso dos tipos já usados.

### Versionamento

O conventional commits segue o SemVer (Versionamento Semântico) onde cada tipo de commit reflete em uma nova versão, podendo ser ela `patch`, `minor` ou `major`;

- fix: patch (ex: 1.0.1).
- feat: minor (ex: 1.1.0).
- BREAKING CHANGE: major (ex: 2.0.0).