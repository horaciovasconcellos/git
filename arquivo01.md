git init - Inicializa repositório
git commit -m "Initial commit" - Commit inicial no main
git remote add origin https://github.com/horaciovasconcellos/git.git
git checkout -b feat-branch-01
git checkout -b feat-branch-02
git checkout -b feat-branch-03
git checkout -b feat-branch-04
---
Branch-01 : Migração
Branch-02 : Backend
Branch-03 : Frontend com feature-flag
Branch-04 : Frontend removendo feature-flag

```mermaid
gitGraph
    commit
    branch feat-branch-01
    checkout feat-branch-01
    commit
    checkout main
    branch feat-branch-02
    checkout feat-branch-02
    commit
    checkout main
    branch feat-branch-03
    checkout feat-branch-03
    commit
````
