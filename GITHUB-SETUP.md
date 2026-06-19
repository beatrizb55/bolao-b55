# 🚀 Guia de Deploy - GitHub Pages

## Pré-requisitos
- Conta no GitHub (gratuita em https://github.com)
- Git instalado no computador

## Passo 1: Criar Repositório no GitHub

1. Acesse https://github.com/new
2. **Repository name**: `bolao-b55`
3. **Description**: `Bolão Copa do Mundo 2026`
4. Selecione **Public** (para ser acessível)
5. Clique em **Create repository**

## Passo 2: Preparar no Computador

Abra o PowerShell/Terminal e execute:

```powershell
cd "C:\Users\beatr\OneDrive\Documentos\bolao-b55-github"

git init

git config user.name "Seu Nome"
git config user.email "seu.email@example.com"

git add .

git commit -m "Bolão B55 Copa do Mundo 2026"

git branch -M main

git remote add origin https://github.com/SEUUSER/bolao-b55.git

git push -u origin main
```

**Substitua:**
- `SEUUSER` pelo seu usuário do GitHub
- `"Seu Nome"` pelo seu nome real
- `seu.email@example.com` pelo seu email

## Passo 3: Ativar GitHub Pages

1. Acesse seu repositório: https://github.com/SEUUSER/bolao-b55
2. Clique em **Settings**
3. Vá para **Pages** (lado esquerdo)
4. Em "Build and deployment":
   - **Source**: selecione `Deploy from a branch`
   - **Branch**: selecione `main` e `/` (raiz)
5. Clique **Save**
6. Aguarde alguns minutos

## Passo 4: Seu Link!

Sua página estará disponível em:

```
https://SEUUSER.github.io/bolao-b55/
```

## ✅ Testar

1. Acesse o link acima
2. Digite seu nome
3. Escolha os placares
4. Clique em "Colocar Aposta"
5. **Compartilhe O MESMO LINK com outras pessoas**

Pronto! 🎉 Todos que acessarem esse link compartilharão os dados!

---

## 🔧 Se der erro na autenticação

Se pedir senha ao fazer push, use um **Personal Access Token**:

1. GitHub > Settings > Developer settings > Personal access tokens
2. Generate new token (classic)
3. Marque `repo`
4. Copie o token
5. Ao pedir senha, cole o token no lugar da senha

---

## ❓ Dúvidas?

Se tiver problemas, verifique:
- [ ] Git está instalado? (`git --version`)
- [ ] Você fez login no GitHub?
- [ ] O repositório foi criado? (`bolao-b55`)
- [ ] Os arquivos estão na pasta correta?

Sucesso! 🚀
