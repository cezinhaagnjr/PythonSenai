# Git e GitHub: Guia Rápido

## Funções Principais do Git

- **Controle de Versão**: Registra o histórico completo das alterações no código.
- **Branching e Merging**: Cria ramificações para trabalhar de forma isolada e depois mescla as alterações.
- **Commits**: Registra mudanças feitas nos arquivos.
- **Área de Preparação (Staging Area)**: Seleciona quais alterações incluir no próximo commit.
- **Repositórios Remotos**: Trabalha com repositórios locais e remotos (como no GitHub).

## Funções Principais do GitHub

- **Hospedagem de Código**: Armazena o código na web.
- **Colaboração**: Facilita o trabalho em equipe através de pull requests.
- **Issues e Projects**: Gerencia tarefas e bugs do projeto.
- **GitHub Actions**: Automatiza testes e deploys do código.
- **GitHub Pages**: Hospeda sites estáticos diretamente do repositório.

## Passos para Postar Seu Projeto no GitHub

1. **Instalar o Git**
   - Baixe e instale o Git a partir de [git-scm.com](https://git-scm.com/).

2. **Criar um Repositório no GitHub**
   - Acesse [GitHub](https://github.com/), faça login ou crie uma conta.
   - Clique em "New" para criar um novo repositório e forneça as informações necessárias.

3. **Inicializar o Git no Projeto Local**
   - No terminal, navegue até a pasta do seu projeto:
     ```bash
     cd /caminho/do/seu/projeto
     ```
   - Inicialize o repositório Git:
     ```bash
     git init
     ```

4. **Adicionar os Arquivos ao Repositório**
   - Adicione os arquivos ao repositório com:
     ```bash
     git add .
     ```

5. **Fazer o Commit**
   - Registre as alterações com uma mensagem explicativa:
     ```bash
     git commit -m "Primeiro commit"
     ```

6. **Conectar o Repositório Local ao GitHub**
   - No GitHub, copie o link do seu repositório (ex: `https://github.com/usuario/nome-do-repositorio.git`).
   - No terminal, conecte seu repositório local ao remoto:
     ```bash
     git remote add origin https://github.com/usuario/nome-do-repositorio.git
     ```

7. **Enviar os Arquivos para o GitHub**
   - Envie os arquivos para o GitHub:
     ```bash
     git push -u origin main
     ```


