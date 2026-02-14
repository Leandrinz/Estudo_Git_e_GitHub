# 📚 Guia Rápido de Comandos Git

## ⚙️ Configuração Inicial
- `git init`  
  Inicia um novo repositório Git na pasta atual.

- `git clone [url]`  
  Faz o download de um repositório remoto já existente.

- `git remote add origin [url]`  
  Conecta seu repositório local ao GitHub.

---

## 🔄 Ciclo de Trabalho Diário
- `git status`  
  Mostra quais arquivos foram alterados ou adicionados.

- `git add [arquivo]`  
  Prepara um arquivo específico para o commit.

- `git add .`  
  Prepara todos os arquivos alterados de uma vez.

- `git commit -m "[mensagem]"`  
  Salva as alterações com uma mensagem curta.

- `git commit -m "[título]" -m "[descrição]"`  
  Salva com um título e uma explicação detalhada.

---

## ☁️ Sincronização com o Servidor
- `git push origin [branch]`  
  Envia seus commits locais para o GitHub.

- `git pull origin [branch]`  
  Traz as novidades do servidor para o seu PC.

---

## 🌿 Gerenciamento de Branches
- `git branch`  
  Lista as branches locais (a atual terá um `*`).

- `git branch -a`  
  Mostra todas as branches, incluindo as remotas.

- `git branch [nome]`  
  Cria uma nova branch.

- `git checkout [nome]`  
  Muda para a branch selecionada.

- `git checkout -b [nome]`  
  Cria e já muda para a nova branch ao mesmo tempo.

- `git merge [nome]`  
  Une as alterações da branch especificada na sua branch atual.

---

## 🕒 Histórico
- `git log`  
  Lista todos os commits realizados.

- `git log --oneline`  
  Exibe o histórico de forma resumida (uma linha por commit).
