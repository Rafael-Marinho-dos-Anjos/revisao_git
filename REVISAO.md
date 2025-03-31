### 1. Criar repositório localmente

```bash
git init
```

### 2. Criando uma nova branch (o nome da branch criada é 'main')

```bash
git checkout -b main
```

ou

```bash
git branch -M main
```

### 3. Adicionar alterações para a área de preparação

```bash
git add nome_do_arquivo
```

ou

```bash
git add .
```

### 4. Mandar todas as alterações preparadas para dentro do repositório local

```bash
git commit -m "mensagem do commit"
```

- OBS.: Isso cria um ponto no histórico do projeto, ou seja, uma nova versão.

### 5. Retornando para a branch main

```bash
git checkout main
```

### 6. Puxando as alterações da nova branch para a main

´´´bash
# executando com a branch main ativa

git merge nova_branch
´´´
