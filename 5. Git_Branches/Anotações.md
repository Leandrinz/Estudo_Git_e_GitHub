# Branch

Anotações de Estudo: Git Branches
Comandos de Git Branch

Navegação e Criação

  - git branch: Lista todas as branches locais. A que você está usando terá um asterisco (*).
  
  - git branch [nome]: Cria uma nova branch com o nome especificado.
  
  - git checkout [nome]: Muda para a branch especificada.
  
  - git checkout -b [nome]: Cria uma nova branch e já muda para ela automaticamente.

Sincronização e Envio

  - git push origin [nome]: Envia a branch criada localmente para o GitHub.
  
  - git pull origin [nome]: Traz as atualizações daquela branch que estão no servidor para o seu PC.

Integração (Merge)

  - git merge [nome]: Estando na branch de destino (ex: main), este comando une as alterações da branch especificada.

Dicas de Visualização

  - Status: Olhar o canto inferior esquerdo do VS Code para confirmar a branch ativa.
  
  - Log: git log para ver o histórico de commits e descrições.