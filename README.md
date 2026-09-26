## 📌 antes de começar

1. Crie uma conta no GitHub.
2. Instale o Git ➔ https://git-scm.com/install/

## 📌 dicas de segurança

* O nome de usuário não deve ter dados pessoais.
* Ative a autenticação em dois fatores (Settings, Password and authentication).
* Em Settings ➔ Emails, marque:

  * "Keep my email addresses private"
  * "Block command line pushes that expose my email"

➔ https://github.com/settings/emails

## 📌 configurando o Git

> Garanta que o Git esteja instalado.

```bash
git config --global user.name "seu-usuario"
git config --global user.email "ID+seu-usuario@users.noreply.github.com"
```

Você pode conferir o noreply mail na mesma página em que você o configurou.

## 📌 passo a passo

### 1. Faça o fork do repositório

Entre no link desse desafio:

➔ https://github.com/Piltoverlabs/000-seu_primeiro_pr

#### 1.1

Clique no botão **Fork** no canto superior da tela.

#### 1.2

Após clicar em **Create a new fork**, prossiga com a criação do mesmo.

### 2. Clone o repositório

Após criar o fork, o GitHub irá te redirecionar para um clone do repositório na sua conta.

Clique no botão verde **<> Code** e copie o link de HTTPS.

Após copiá-lo, você pode baixar o repositório na sua máquina para poder trabalhar no seu projeto.

**Recomendações antes de fazer o download do repositório na sua máquina local:**

Crie uma pasta para projetos e armazene-os lá.

```bash
git clone https://github.com/SEU-USUARIO/REPOSITORIO.git
cd REPOSITORIO
```

### 3. Crie uma branch

Não trabalhe na `main`/`master`.

Para criar uma branch, você pode usar:

```bash
git branch "feat(desafio)/nome-da-branch"
```

Após criar a branch, entre nela:

```bash
git switch "feat(desafio)/nome-da-branch"
```

Você pode verificar em qual branch está utilizando:

```bash
git branch
```

A branch actual estará marcada com um `*`.

### 4. Histórico

#### 4.1 Criando commits

Para adicionar um arquivo específico:

```bash
git add <nome_do_arquivo.ext>
```

Para adicionar um diretório:

```bash
git add <nome_do_diretorio>/
```

Para adicionar todas as alterações:

```bash
git add .
```

Após adicionar os arquivos, crie o commit:

```bash
git commit -m "mensagem do commit"
```

#### 4.2 Visualizando o histórico

Para visualizar o histórico de commits:

```bash
git log
```

Caso tenha alguma dúvida:

https://discord.gg/2AmQV7X7ZY

<!-- pipeline-trigger: 2026-09-26T21:03:00Z -->
