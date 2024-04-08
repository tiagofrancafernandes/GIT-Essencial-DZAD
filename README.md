### GIT é um Sistema de versionamento de código fonte

```sh
## Fonte  -> Resultado
RECEITA   -> BOLO
```

#### Etapas de um commit

1. Cria, modifica, deleta item(ns)
2. Adicione o(s) item(ns) ao `stage`
3. Identifique a(a) ação(ões) feita(s) por meio de uma mensagem (commit)

#### Branches

São ramificações (`branches`) de alguma `branch`.

######

**GIT Básico - Comandos Essenciais:**

> **Local (offline):**
1. **git init:** Inicia um repositório Git em um diretório. [OK]
2. **git add [arquivo]:** Adiciona alterações ao próximo commit. [OK]
3. **git commit:** Registra as alterações no repositório com uma mensagem descritiva. [OK]
    - Em linha (direto do terminal) [OK]
    - Em um editor [OK]
4. **git status:** Exibe o estado das alterações como não rastreadas, modificadas ou prontas para commit. [OK]
5. **git log:** Mostra o histórico de commits. [OK]

> **Adicionais:**
> - **git branch:** Lista, cria ou deleta branches.
> - **git merge [branch]:** Combina alterações de uma branch à branch atual.
> - **git diff:** Mostra as diferenças entre as alterações antes do commit.
> Esses comandos formam a base essencial para trabalhar com Git no desenvolvimento web, desde a criação de repositórios até a colaboração em projetos.

> **Remoto:**
6. **git remote -v:** Mostra os repositórios remotos configurados.
7. **git clone [url]:** Clona um repositório remoto para o diretório local.
8. **git pull:** Atualiza o repositório local com as alterações do repositório remoto.
9. **git push:** Envia os commits locais para o repositório remoto.
10. **git fetch:** Busca as alterações do repositório remoto, mas não as aplica.

Esses são os tópicos essenciais para cada módulo, cobrindo desde o básico até aspectos mais avançados, proporcionando uma base sólida para o desenvolvimento web.
