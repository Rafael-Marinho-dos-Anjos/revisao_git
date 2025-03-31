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

### 5. Foi criada uma nova branch

```bash
git checkout -b nova_branch
```

### 6. Enviando novas alterações para dentro do repositório

```bash
git add .
git commit -m "Nova branch criada"
```

### 7. Retornando para a branch main

```bash
git checkout main
```

### 8. Puxando as alterações da nova branch para a main

´´´bash
# executando com a branch main ativa

git merge nova_branch
´´´

### 9. Adicionar link para o repositório remoto

```bash
git remote add origin link
```

### 10. Enviar as alterações locais para o repositório remoto

```bash
git push origin nome_da_branch
```
