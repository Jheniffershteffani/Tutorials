### passo 1 - (git init)

```bash
git init
```
### passo 2 - (substitua a branch de master para main)

```bash
git branch -M main
```

### passo 3 - (Adicione o repositório remoto)

- substitua `github.com` por `jheniffer`
```bash
# git remote add origin git@github.com:Jheniffershteffani/<nome do repositório>.git
git remote add origin git@jheniffer:Jheniffershteffani/<nome do repositório>.git
```
```bash
git config user.name "jheniffer"
```
```bash
git config user.email jheniffer.aleatorio@gmail.com 
```

### passo 4 - (junte/acumule às alterações)

- substitua `github.com` por `jheniffer`
```bash
git add .
```


### passo 5 - (commit às alterações)

```bash
git commit -m "first commit"
```

### passo 6 - (Suba para o github)
```bash
git push -u origin main
```

# Resumo
### Primeira parte

```bash
git init
git branch -M main
git config user.name "jheniffer"
git config user.email jheniffer.aleatorio@gmail.com 
git remote add origin git@jheniffer:Jheniffershteffani/<nome do repositório>.git
```

### Segunda parte


```bash
git add .
git commit -m "first commit"
git push -u origin main
```

# Possiveis erros

## Se der erro no passo 1
- Verifique se vc consegue logar usando o camando abaixo:
```bash
ssh -T git@jheniffer
```
- Verifique se o seu usuário aparece na lista usando o camando abaixo:
## Se der erro no passo 2
```bash
git config --list
```

O resultado deve conter as seguintes credenciais:
```bash
user.email=jheniffer.aleatorio@gmail.com
user.name=Jheniffer
```
