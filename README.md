# 🚀 Git Playground

![Repo Size](https://img.shields.io/github/repo-size/WallanDavid/git-playground)
![Last Commit](https://img.shields.io/github/last-commit/WallanDavid/git-playground)
![Top Language](https://img.shields.io/github/languages/top/WallanDavid/git-playground)
![License](https://img.shields.io/github/license/WallanDavid/git-playground)

> Projeto didático e prático com exemplos reais de Git: comandos, fluxo de branches, stash, logs, reset e rebase.

---

## 📚 Sumário

- [📦 Estrutura](#-estrutura)
- [🧠 Roteiro de Estudo](#-roteiro-de-estudo)
- [💡 Exemplos práticos](#-exemplos-práticos)
- [🚀 Como usar localmente](#-como-usar-localmente)
- [📄 Licença](#-licença)

---

## 📦 Estrutura

```
.
├── .gitignore
├── README.md
├── commands.md
└── examples/
    ├── branching-merge.md
    ├── logs-diff.md
    └── stash.md
```

---

## 🧠 Roteiro de Estudo

> Um guia simples pra explorar e praticar os comandos Git de forma ordenada.

1. [Staging & Commit](commands.md)
2. [Branching & Merge](examples/branching-merge.md)
3. [Stash](examples/stash.md)
4. [Logs/Diff](examples/logs-diff.md)
5. [Remoto (push, pull, remote)](commands.md)

---

## 💡 Exemplos práticos

| Tema               | Exemplo                                  |
|--------------------|-------------------------------------------|
| Criar branch       | `git branch nome-da-branch`               |
| Mudar de branch    | `git checkout nome-da-branch`             |
| Fazer merge        | `git merge branch-desejada`               |
| Stash de alterações| `git stash`, `git stash pop`              |
| Ver histórico      | `git log --oneline --graph --decorate`    |
| Rebase             | `git rebase branch-alvo`                  |
| Reset              | `git reset --hard HEAD~1`                 |

---

## 🚀 Como usar localmente

```bash
git clone https://github.com/WallanDavid/git-playground.git
cd git-playground

# Agora é só explorar os arquivos .md
```

Ou crie suas próprias branches pra treinar comandos Git de forma prática 💪

---

## 📄 Licença

Distribuído sob licença MIT. Veja o arquivo [`LICENSE`](LICENSE) para mais detalhes.
