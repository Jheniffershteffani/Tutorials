### passo 1 - (Clonar o repositório)
- substitua `github.com` por `jheniffer`
```bash
# git clone git@github.com:Jheniffershteffani/<nome do repositório>.git
git clone git@jheniffer:Jheniffershteffani/<nome do repositório>.git
```
### passo 2 - (Setar suas credenciais)

```bash
git config user.name "jheniffer"
```
```bash
git config user.email jheniffer.aleatorio@gmail.com 
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
