# ScreenSound 🎵

**ScreenSound** é uma aplicação de gerenciamento de músicas desenvolvida em Java utilizando o framework Spring Boot. O projeto permite o cadastro e a busca de artistas e suas músicas, oferecendo uma interface de linha de comando para interação do usuário.

## 📋 Funcionalidades

- **Cadastrar Artistas**: Permite o registro de novos artistas no banco de dados.
- **Cadastrar Músicas**: Adiciona músicas para artistas já cadastrados.
- **Listar Músicas**: Exibe todas as músicas cadastradas no sistema.
- **Buscar Músicas por Artista**: Realiza uma busca de músicas de um determinado artista.
- **Interface de Linha de Comando (CLI)**: Navegação através de um menu interativo.

## 🛠️ Tecnologias Utilizadas

- **Java 17+**: Linguagem de programação principal.
- **Spring Boot**: Framework utilizado para desenvolvimento da aplicação.
- **Spring Data JPA**: Abstração para persistência de dados.
- **PostgreSQL**: Banco de dados relacional utilizado para armazenamento de dados.

## 📂 Estrutura do Projeto

O projeto está organizado nos seguintes pacotes:

- **br.com.alura.screensound**: Contém a classe principal `ScreensoundApplication`.
- **br.com.alura.screensound.principal**: Contém a classe `Principal` que gerencia o menu principal da aplicação.
- **br.com.alura.screensound.model**: Contém as classes de modelo `Artista`, `Musica` e `TipoArtista`.
- **br.com.alura.screensound.repository**: Contém o repositório `ArtistaRepository` para a comunicação com o banco de dados.

### 📌 Detalhes Técnicos

- **Classe `Principal`**: Responsável pela lógica de navegação do menu e pelas operações de cadastro e busca de artistas e músicas.
- **Classe `Artista`**: Representa os artistas cadastrados no sistema, incluindo informações como nome e tipo (solo, dupla ou banda).
- **Classe `Musica`**: Representa as músicas associadas aos artistas cadastrados.
- **Repositório `ArtistaRepository`**: Gerencia a persistência e consulta de dados no banco de dados PostgreSQL.

## 🚀 Executando o Projeto

Para executar o projeto, siga os seguintes passos:

1. Clone o repositório em sua máquina.
2. Configure o banco de dados PostgreSQL e atualize as credenciais no arquivo `application.properties`.
3. Execute a aplicação através do comando:

   ```shell
   mvn spring-boot:run

## Menu de uso

![Captura de tela 2024-08-31 035355](https://github.com/user-attachments/assets/6771c79a-ea84-4aac-9ca6-169d028e18be)

## Contribuições
**Contribuições são bem-vindas! Se você tiver sugestões, correções ou melhorias, sinta-se à vontade para abrir uma issue ou um pull request.**

## Autor

Kaio Vitor - [GitHub](https://github.com/Kaio-0708)


