
# Como Criar uma Branch, Commit e Pull Request no GitHub

Este documento explica como criar uma branch, fazer commits e criar um pull request no GitHub para contribuir com um repositório.

## Passos

### 1. Clonar o Repositório
Antes de começar, você precisa clonar o repositório para sua máquina local:
```bash
git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_REPOSITORIO>
```
Se for usar o VSCode para editar seu código, use o comando a seguir para abrir o projeto diretamente no editor:
```bash
code .
```

### 2. Criar uma Nova Branch
Crie uma nova branch para isolar o trabalho que será feito:
```bash
git checkout -b minha-nova-branch
```

### 3. Fazer Alterações no Código
Edite os arquivos conforme necessário. Você pode verificar as alterações feitas com o comando:
```bash
git status
```

### 4. Adicionar as Alterações ao Staging
Adicione os arquivos modificados ao estágio para preparar o commit:
```bash
git add .
```

### 5. Fazer o Commit
Agora faça o commit das suas alterações com uma mensagem descritiva:
```bash
git commit -m "Descrição das mudanças feitas"
```

### 6. Enviar as Alterações para o Repositório Remoto
Envie sua branch para o repositório remoto:
OBS: certifique-se de que está fazendo commit na branch certa (evita retrabalho depois)
```bash
git push origin minha-nova-branch
```

### 7. Criar um Pull Request no GitHub
Após fazer o push, vá até o GitHub e crie um Pull Request:
- Na aba **Pull Requests**, clique em **New Pull Request**.
- Selecione sua branch e a branch de destino.
- Escreva uma descrição e clique em **Create Pull Request**.

### 8. Revisão e Merge
Agora é só aguardar a revisão da equipe e, se aprovado, o merge será feito na branch principal.

---

Este processo é essencial para uma colaboração eficiente em projetos de software, permitindo o controle de versões e revisões de código.
Você pode checar o guia para usuários de VSCode também neste repositório. Sinta-se à vontade para fazer um commit propondo alguma correção ou adendo.
