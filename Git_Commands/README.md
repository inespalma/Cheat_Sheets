# Git Commands

## **Basic Git Commands**

| Command                                              | Description                                                   | Example                                    |
| ---------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------ |
| `git init`                                           | Inicializa um novo repositório Git local                       | `git init`                                 |
| `git clone <url>`                                    | Clona um repositório remoto para o diretório atual             | `git clone https://github.com/user/repo.git` |
| `git add <file>`                                     | Adiciona um arquivo ou mudanças ao índice (staging area)       | `git add index.html`                       |
| `git commit -m "<message>"`                           | Faz um commit das mudanças adicionadas ao índice              | `git commit -m "Mensagem do commit"`       |
| `git status`                                         | Exibe o status atual dos arquivos no repositório              | `git status`                               |
| `git log`                                            | Exibe o histórico de commits                                   | `git log`                                  |
| `git diff`                                           | Exibe as diferenças entre as versões de arquivos              | `git diff`                                 |

---

## **Branching & Merging**

| Command                                              | Description                                                   | Example                                    |
| ---------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------ |
| `git branch`                                         | Exibe todas as branches locais no repositório                  | `git branch`                               |
| `git branch <branch_name>`                            | Cria uma nova branch no repositório                            | `git branch feature-x`                     |
| `git checkout <branch_name>`                          | Muda para a branch especificada                               | `git checkout feature-x`                   |
| `git checkout -b <branch_name>`                       | Cria e muda para uma nova branch                               | `git checkout -b new-feature`              |
| `git merge <branch_name>`                             | Mescla a branch especificada na branch atual                   | `git merge feature-x`                      |
| `git branch -d <branch_name>`                         | Deleta a branch especificada localmente                        | `git branch -d feature-x`                  |

---

## **Remote Repositories**

| Command                                              | Description                                                   | Example                                    |
| ---------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------ |
| `git remote add <name> <url>`                         | Adiciona um repositório remoto ao seu repositório local        | `git remote add origin https://github.com/user/repo.git` |
| `git push <remote> <branch>`                          | Envia as alterações locais para o repositório remoto           | `git push origin master`                   |
| `git pull <remote> <branch>`                          | Puxa as alterações do repositório remoto para a branch local   | `git pull origin master`                   |
| `git fetch <remote>`                                  | Baixa as atualizações do repositório remoto sem mesclar       | `git fetch origin`                         |
| `git remote -v`                                       | Exibe os repositórios remotos configurados no repositório     | `git remote -v`                            |

---

## **Stashing**

| Command                                              | Description                                                   | Example                                    |
| ---------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------ |
| `git stash`                                          | Salva as alterações não commitadas temporariamente            | `git stash`                                |
| `git stash apply`                                    | Aplica as mudanças salvas no stash                            | `git stash apply`                          |
| `git stash drop`                                     | Remove a última entrada no stash                              | `git stash drop`                           |
| `git stash pop`                                      | Aplica e remove a última entrada do stash                     | `git stash pop`                            |

---

## **Undo Changes**

| Command                                              | Description                                                   | Example                                    |
| ---------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------ |
| `git reset`                                          | Restaura o repositório para o estado anterior a um commit     | `git reset --hard <commit_hash>`           |
| `git checkout -- <file>`                              | Desfaz alterações em um arquivo (não commitado)               | `git checkout -- index.html`               |
| `git revert <commit>`                                 | Reverte um commit específico criando um novo commit            | `git revert abc123`                        |

---

## **Tagging**

| Command                                              | Description                                                   | Example                                    |
| ---------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------ |
| `git tag`                                            | Exibe todas as tags do repositório                            | `git tag`                                  |
| `git tag <tag_name>`                                  | Cria uma nova tag no repositório                              | `git tag v1.0`                             |
| `git tag -a <tag_name> -m "<message>"`                 | Cria uma nova tag com mensagem de anotação                    | `git tag -a v1.1 -m "Release versão 1.1"`  |
| `git push <remote> <tag_name>`                        | Envia uma tag para o repositório remoto                        | `git push origin v1.0`                     |

---

## **Working with Submodules**

| Command                                              | Description                                                   | Example                                    |
| ---------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------ |
| `git submodule add <url>`                             | Adiciona um submódulo ao repositório                          | `git submodule add https://github.com/user/repo.git` |
| `git submodule init`                                  | Inicializa um submódulo no repositório                        | `git submodule init`                       |
| `git submodule update`                                | Atualiza os submódulos para a versão mais recente             | `git submodule update`                     |
| `git submodule update --remote`                        | Atualiza os submódulos para a versão mais recente remotamente | `git submodule update --remote`            |

---

## **Configuration**

| Command                                              | Description                                                   | Example                                    |
| ---------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------ |
| `git config --global user.name "<name>"`              | Define o nome de usuário global                               | `git config --global user.name "John Doe"` |
| `git config --global user.email "<email>"`            | Define o e-mail de usuário global                             | `git config --global user.email "john@example.com"` |
| `git config --list`                                   | Exibe todas as configurações do Git                           | `git config --list`                        |

---

## **Help Commands**

| Command                                              | Description                                                   | Example                                    |
| ---------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------ |
| `git help`                                           | Exibe a ajuda geral do Git                                    | `git help`                                 |
| `git <command> --help`                                | Exibe a ajuda para um comando específico                      | `git push --help`                          |
