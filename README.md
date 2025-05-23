# Desafio Validação de Segurança
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/MarcusViniciusGodoy/Desafio_Validacao_Seguranca/blob/main/LICENSE)

# Sobre o projeto

Quinto desafio do curso Java Spring Professional, cursos organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

Este projeto possui uma estrutura de dados baseada no diagrama UML abaixo, que representa o modelo de domínio de um sistema de gerenciamento de eventos.

## UML Validação
![Validacao](https://github.com/MarcusViniciusGodoy/assets/blob/main/Validacao.PNG)

## Testes segurança
![testes](https://github.com/MarcusViniciusGodoy/assets/blob/main/testeSeguranca.PNG)

## 📊 Entidades e Relacionamentos
- User: Representa os usuários do sistema. Cada usuário possui um e-mail, senha e pode ter múltiplos papéis (roles) associados.

- Role: Define as permissões ou autoridades de um usuário. Um usuário pode ter uma ou mais roles.

- Event: Representa um evento que será realizado. Contém informações como nome, data e URL do evento.

- City: Cada evento está associado a uma cidade. Uma cidade pode conter vários eventos, mas um evento pertence a apenas uma cidade.

## 🔗 Relacionamentos
- User ↔ Role: Relação many-to-many — um usuário pode ter múltiplos papéis e um papel pode ser associado a múltiplos usuários.

- Event → City: Relação many-to-one — vários eventos podem ocorrer em uma única cidade, mas cada evento pertence a apenas uma cidade.

### Pré-requisitos
 Para executar este projeto, é necessário ter:
 - [Java](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) (versão 11 ou superior)
 - [Visual Studio Code](https://code.visualstudio.com/)
 - [Pacote de Extensão Java para VS Code](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)

### Instalação
 
 1. Clone o repositório:
    ```bash
    git clone https://github.com/MarcusViniciusGodoy/Desafio_Validacao_Seguranca.git
    ```
 
 2. Acesse o diretório do projeto:
    ```bash
    cd Desafio_Validacao_Seguranca
    ```
 
 3. Abra o projeto no Visual Studio Code:
    ```bash
    code .
    ```
 
 4. Compile e execute o projeto com seu compilador Java de preferência.

# Tecnologias Utilizadas
## Back end
- Java
- Spring Boot

## Testes 
- JUnit 5

# Autor
Marcus Vinícius de Godoy 

https://www.linkedin.com/in/marcus-vin%C3%ADcius-godoy-15b5461a0/
