# GIT E GITHUB

Guia prático para iniciantes.

### Instalação

Download: https://git-scm.com/download

# Cenários

- [X] Iniciar um repositório
```bash
git init
```

- [X] Você deseja criar pontos na história da produção do seu projeto
Adicionar:
```bash
git add 
```
Comentar alteração:
```bash
git commit -m "alteração"
```


- [X] Você deseja verificar mudanças feitas no seu projeto
Mostrar última alteração feita:
```bash
git show
```

Mostrar última uma alteração especifica
```bash
git show <log>
```

- [X] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feio.
- Criar uma nova ramificação
```bash
git branch feature/nome-da-feature
```
- Usando a nova ramificação
```bash
git checout feature/nome-da-feature
```

- [X] Você adiciona as novas funcionalidades ao seu projeto em produção
```bash
git merge <nome-da-branch>
```
**Obs:** Necessário estar na branch principal

- [X] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto
```bash
git branch -D <nome-da-branch>
```

- [X] Colocar seu projeto na nuvem
```bash
git push -u origin master
```