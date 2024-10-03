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
