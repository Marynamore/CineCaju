![cc](assets/cc_logo.png)
# CineCaju 🎥🎬

Este projeto visa criar um site de críticas construtivas de filmes em cartaz. A ideia é ajudar os telespectadores a escolherem filmes com base em diversos critérios como roteiro, personagens, duração, trilha sonora e efeitos visuais.

## 📝 Objetivo e Funcionalidades

Abaixo estão as principais funcionalidades do projeto, organizadas como um checklist:

- [ ] Permitir que os usuários publiquem críticas de filmes.
- [ ] Permitir que os usuários alterem e excluam suas próprias críticas.
- [ ] Avaliar filmes com base em critérios específicos (roteiro, personagens, trilha sonora, etc.).
- [ ] Permitir que os usuários pesquisem filmes em cartaz, lançamentos futuros e filmes antigos.
- [ ] Exibir um ranking de filmes com base nas avaliações dos usuários.
- [ ] Possibilitar o cadastro e login de novos usuários.
- [ ] Permitir que os usuários favoritem filmes e acessem suas listas de favoritos.
- [ ] Recuperar senhas via e-mail.
- [ ] Permitir a comparação entre diferentes críticas de um mesmo filme.
- [ ] Exibir uma página de filmes favoritos para cada usuário.
- [ ] Denunciar críticas que violem as diretrizes da plataforma.

## Tecnologias Utilizadas
- **Frontend**: JavaScript
- **Backend**: Node.js, Express.js
- **Banco de Dados**: PostgreSQL

## 📋 Requisitos Funcionais

1. **[RF001] Publicar Crítica de Filme**: Permitir que usuários publiquem críticas detalhadas de filmes.
   - Prioridade: Essencial

2. **[RF002] Alterar Crítica de Filme**: Permitir que o usuário altere suas críticas.
   - Prioridade: Essencial

3. **[RF003] Excluir Crítica de Filme**: Permitir que o usuário exclua suas críticas.
   - Prioridade: Essencial

4. **[RF004] Pesquisar Filmes**: O sistema deverá permitir a busca por filmes em cartaz e lançamentos.
   - Prioridade: Essencial

5. **[RF005] Ranking de Filmes**: Exibir rankings de filmes baseados nas avaliações.
   - Prioridade: Importante

6. **[RF006] Cadastro de Usuário e Login**: Permitir cadastro de novos usuários e autenticação segura.
   - Prioridade: Essencial

7. **[RF007] Recuperar Senha**: O sistema deve ter um mecanismo de recuperação de senha via e-mail.
   - Prioridade: Essencial

8. **[RF008] Denunciar Crítica**: Os usuários poderão denunciar críticas impróprias.
    - Prioridade: Importante

## 📊 Requisitos Não Funcionais

1. **[RNF001] Usabilidade**: Interface responsiva e intuitiva para desktop e dispositivos móveis, acima de 1 Gb ram.
   - Prioridade: Essencial

2. **[RNF002] Segurança**: Autenticação segura via JWT e criptografia de senhas.
   - Prioridade: Essencial

3. **[RNF003] Desempenho**: Tempo de resposta para busca de filmes e carregamento de críticas não deve exceder 2 segundos.
   - Prioridade: Essencial

4. **[RNF004] Escalabilidade**: Suportar até 1000 usuários simultâneos.
   - Prioridade: Importante

5. **[RNF005] Conformidade LGPD**: O sistema deve seguir as diretrizes da Lei Geral de Proteção de Dados.
   - Prioridade: Essencial

6. **[RNF006] Compatibilidade com Dispositivos Móveis**: Funcionar em smartphones e tablets com resolução mínima de 1280x720.
   - Prioridade: Essencial
  
## 📝 Perfis de acesso: 

- **Administrador:** Acesso total
- **Moderador:** Acesso 
- **Desenvolvedor Teste (Corretor de Bugs)** - privilegiado
- **Gestor de Conteúdo Usuário Final** - privilegiado
- **Usuário**



![cinecaju](assets/cinecaju_logo.jpeg)

## Instalação e Configuração

1. Navegue até o diretório do projeto:

    ```bash
    cd nome-do-projeto
    ```

2. Instale as dependências:

    ```bash
    npm install
    ```

3. Configure o banco de dados PostgreSQL no arquivo `.env` com suas credenciais:

    ```plaintext
    DB_HOST=localhost
    DB_USER=seu-usuario
    DB_PASS=sua-senha
    DB_NAME=nome-do-banco
    ```

4. Inicie o servidor:

    ```bash
    npm start
    ```

5. Acesse o site:

    ```plaintext
    http://localhost:3000
    ```

## 🤝 Contribuição

Contribuir para este projeto é fácil! Siga os passos abaixo para começar:

1. **Fork do Projeto**: 
   - Vá até a página do projeto no GitHub.
   - Clique no botão "Fork" no canto superior direito para criar uma cópia do repositório na sua conta do GitHub.

2. **Clone o Repositório Forkado**:
   - No seu repositório forkado, clique no botão "Code" e copie a URL.
   - Abra o terminal e execute o seguinte comando para clonar o repositório para sua máquina local:
     ```bash
     git clone URL_DO_SEU_REPOSITORIO
     ```
   - Substitua `URL_DO_SEU_REPOSITORIO` pela URL que você copiou.

3. **Crie uma Nova Branch**:
   - Navegue até o diretório do projeto clonado:
     ```bash
     cd nome-do-repositorio
     ```
   - Crie uma nova branch para a sua funcionalidade:
     ```bash
     git checkout -b minha-funcionalidade
     ```
   - Dê um nome descritivo para a sua branch que reflita a funcionalidade que você está implementando.

4. **Faça suas Mudanças**:
   - Edite os arquivos do projeto conforme necessário.
   - Salve suas alterações.

5. **Commit suas Mudanças**:
   - Adicione os arquivos que você modificou ao stage:
     ```bash
     git add .
     ```
   - Faça um commit das suas mudanças com uma mensagem descritiva:
     ```bash
     git commit -m 'Adicionando nova funcionalidade'
     ```

6. **Envie suas Mudanças para o GitHub**:
   - Faça o push da sua branch para o seu repositório forkado no GitHub:
     ```bash
     git push origin minha-funcionalidade
     ```

7. **Abra um Pull Request**:
   - Vá até a página do seu repositório forkado no GitHub.
   - Clique em "Compare & pull request".
   - Descreva as alterações que você fez e clique em "Create pull request".

Após abrir o Pull Request, a equipe revisará suas mudanças. Assim que estiver tudo certo, suas contribuições serão integradas ao projeto!

Se você tiver alguma dúvida durante o processo, não hesite em perguntar!


## 🛠️ Licença
Este projeto está sob a licença Apache. Veja o arquivo LICENSE para mais detalhes.
