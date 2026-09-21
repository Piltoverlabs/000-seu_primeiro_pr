## ✦ antes de começar:

1. Crie uma conta no GitHub.
2. Instale o git ➔ https://git-scm.com/install/

## ✦ dicas de segurança:
- O nome de usuário não deve ter dados pessoais.
- Ative a autenticação em dois fatores (Settings, Password and authentication).
- Em Settings, Emails, marque "Keep my email addresses private" e "Block command line pushes that expose my email" ➔ https://github.com/settings/emails

## ✦ configurando o git:
> Garanta que o Git esteja instalado

```js
git config --global user.name "seu-usuario"
git config --global user.email "ID+seu-usuario@users.noreply.github.com"
```
Você pode conferir o noreply mail na mesma página que você a configurou.

## ✦ passo a passo

1. Entre no link desse desafio ➔ https://github.com/Piltoverlabs/000-seu_primeiro_pr
1.1 Clique no botão de fork no canto superior da tela.
1.2 Após clicar em "Create a new fork" prossiga com a criação do mesmo.

2. Após criar o fork o github irá te redirecionar para um clone do repositorio na sua conta.
2.1 Clique no botão verde "<> Code" e copie o link de HTTPS

após copia-lo, você pode baixar em sua maquina para poder trabalhar no seu projeto.

recomendações antes de fazer o download do repositorio na sua maquina local.
Crie uma pasta para projetos e armazene-os lá.

```hs
git clone https://github.com/SEU-USUARIO/<REPOSITORIO.git>
cd REPOSITORIO
```

3. Crie uma branch. Não trabalhe na main/master.

- para criar uma branch pode usar
```hs
git branch "feat(desafio)/nome-da-branch"
```
- após criar a branch, entre nela:
```hs
git checkout "feat(desafio)/nome-da-branch"
```
ou, utilizando uma versão mais recente do git:
```hs
git switch "feat(desafio)/nome-da-branch"
```
- você pode verificar em qual branch está utilizando:
```hs
git branch
```
a branch atual estará marcada com um `*`.

4. Histórico

4.1 Criando commits

- para adicionar um arquivo específico:
```hs
git add <nome_do_arquivo.ext>
```
- para adicionar um diretório:
```hs
git add <nome_do_diretorio>/
```
- para adicionar todas as alterações:
```hs
git add .
```
- após adicionar os arquivos, crie o commit:
```hs
git commit -m "mensagem do commit"
```
4.2 Visualizando o histórico

- para visualizar o histórico de commits:
```hs
git log
```
- para visualizar o histórico de forma resumida:
```hs
git log --oneline
```

caso tenha alguma dúvida https://discord.gg/2AmQV7X7ZY
