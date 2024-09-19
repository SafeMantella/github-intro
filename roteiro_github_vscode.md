
# Roteiro para Criar Branch, Commit e Pull Request no GitHub Usando VS Code

## 1. Clonar o Repositório pelo VS Code

No VS Code, você pode clonar diretamente o repositório. Para isso, siga os passos:

1. Abra o **VS Code**.
2. Pressione `Ctrl + Shift + P` para abrir a **paleta de comandos**.
3. Digite "Git: Clone" e selecione a opção **Git: Clone**.
4. Cole a URL do repositório Git que você deseja clonar.
5. Escolha uma pasta onde o repositório será clonado.
6. Quando o processo terminar, o VS Code perguntará se você deseja abrir o repositório clonado. Escolha **Abrir**.

## 2. Criar uma Nova Branch no VS Code

Agora que você está com o repositório aberto, crie uma nova branch:

1. No canto inferior esquerdo, clique no nome da branch atual (geralmente `main` ou `master`).
2. Selecione **Criar Nova Branch**.
3. Dê um nome à nova branch (ex: `minha-nova-branch`).

O VS Code mudará automaticamente para a nova branch.

## 3. Fazer Alterações no Código

Edite o código conforme necessário. O VS Code irá mostrar automaticamente os arquivos que foram modificados na aba de controle de versão (ícone de ramificação no menu lateral).

## 4. Adicionar as Alterações ao Staging

Para adicionar as mudanças ao **staging** (etapa antes do commit):

1. Clique no ícone de controle de versão no menu lateral (um ícone de ramificação).
2. Você verá a lista de arquivos modificados.
3. Ao lado de cada arquivo, há um ícone de **mais (+)**. Clique nele para adicionar o arquivo ao **staging**.
4. Para adicionar todos os arquivos, clique em **+** na seção "Alterações".

## 5. Fazer o Commit no VS Code

Após adicionar os arquivos ao **staging**, faça o commit:

1. Na aba de controle de versão, na barra superior, há um campo de texto.
2. Escreva uma mensagem de commit descritiva (ex: "Corrigido erro na função de login").
3. Clique no ícone de **check (✓)** ou pressione `Ctrl + Enter` para confirmar o commit.

## 6. Enviar as Mudanças para o Repositório Remoto

Agora que você fez o commit, envie suas mudanças para o GitHub:

1. No canto inferior esquerdo do VS Code, clique em **Sincronizar Mudanças** (ícone de setas circulares) ou use a paleta de comandos com `Ctrl + Shift + P` e escolha **Git: Push**.
2. O VS Code irá enviar sua branch para o repositório remoto no GitHub.

## 7. Criar um Pull Request no GitHub

No GitHub, após o **push**, será exibido um aviso para criar um **Pull Request**.

1. No GitHub, vá até o repositório e clique na aba **Pull Requests**.
2. Clique em **New Pull Request**.
3. Escolha sua branch recém-enviada (`minha-nova-branch`) e a branch de destino (geralmente `main` ou `master`).
4. Adicione um título e uma descrição explicando as mudanças feitas.
5. Clique em **Create Pull Request**.

## 8. Aguardar Revisão

Agora, os colaboradores ou responsáveis pelo repositório podem revisar suas alterações. Se aprovado, eles farão o merge do seu Pull Request na branch principal.
