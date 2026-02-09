--- Anotações de Aula: Git e GitHub Desktop ---

Nesta aula, aprendemos a integrar um repositório local com o GitHub utilizando o GitHub Desktop. Abaixo estão os conceitos fundamentais e o passo a passo do fluxo de trabalho.

- 1) Conceitos Fundamentais:

    . No dia a dia com Git, o trabalho resume-se em sincronizar o que está no seu computador com o que está na nuvem (GitHub).

    - 1. Repositório (Repository):
        É a pasta do seu projeto que o Git está “vigiando”. Tudo o que acontece ali dentro pode ser versionado, ou seja, salvo no histórico.

    - 2. Push (Empurrar):
        O comando Push serve para enviar as alterações locais (os commits feitos no seu computador) para o servidor do GitHub.
        
        Analogia: é como fazer o upload de uma foto para uma rede social.

    - 3. Pull (Puxar):
        O comando Pull traz as alterações que estão no GitHub para o seu computador. Isso é essencial quando se trabalha em equipe ou em computadores diferentes.

        Analogia: é como baixar as atualizações de um aplicativo no celular.

- 2) Fluxo de Trabalho no GitHub Desktop:

    . Este é o ciclo básico de trabalho:

        Alteração: você cria ou edita arquivos na pasta do projeto.

        Commit: no GitHub Desktop, os arquivos alterados aparecem na aba Changes.

        Escreva um título curto para o commit.

        Clique em “Commit to main”.

        Publish/Push: após o commit, o botão azul no topo mudará para “Publish repository” (na primeira vez) ou “Push origin”. Clique nele para enviar os arquivos para a nuvem.

        Fetch/Pull: sempre que abrir o projeto, clique em “Fetch origin” para verificar se há mudanças no GitHub. Se houver, o botão mudará para “Pull”.

