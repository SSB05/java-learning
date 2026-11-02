# Comandos Git

## Fluxo do dia a dia

### Verificar alterações

```bash
git status
```

Mostra quais arquivos foram criados, alterados ou removidos.

---

### Adicionar alterações para o commit

```bash
git add .
```

Adiciona todas as alterações da pasta atual.

---

### Criar um commit

```bash
git commit -m "mensagem"
```

Exemplo:

```bash
git commit -m "Estudo sobre variaveis"
```

Salva uma nova versão do projeto.

---

### Enviar para o GitHub

```bash
git push
```

Publica os commits locais no GitHub.

---

## Consultas úteis

### Ver histórico de commits

```bash
git log
```

Mostra todos os commits realizados.

---

### Histórico resumido

```bash
git log --oneline
```

Mostra os commits em uma linha.

---

### Ver conexão com GitHub

```bash
git remote -v
```

Mostra qual repositório do GitHub está conectado.

---

### Ver branch atual

```bash
git branch
```

Mostra em qual branch estou trabalhando.

---

## Primeiro fluxo para um novo estudo

```bash
git status
git add .
git commit -m "O que eu aprendi"
git push
```

---

## Exemplos de commits

```bash
git commit -m "Estudo sobre variaveis"
```

```bash
git commit -m "Exercicios de operadores matematicos"
```

```bash
git commit -m "Primeiros exemplos com if else"
```

```bash
git commit -m "Exercicios com loops"
```

```bash
git commit -m "Criado projeto calculadora"
```

---

## Glossário

### Repositório

Pasta controlada pelo Git.

---

### Commit

Fotografia do projeto em um determinado momento.

---

### Push

Enviar alterações para o GitHub.

---

### Pull

Baixar alterações do GitHub.

```bash
git pull
```

---

### Branch

Linha paralela de desenvolvimento.

```bash
git branch
```

---

## Regra de Ouro

Sempre que terminar um estudo:

```bash
git status
git add .
git commit -m "Descrição do que aprendi"
git push
```

Exemplo:

```bash
git status
git add .
git commit -m "Conclusao da aula de variaveis"
git push
```

