# Documentação do Projeto: GreenTea

---

## 1. Visão Geral do Projeto

O **GreenTea** é um projeto de aplicação web desenvolvido em C# utilizando o .NET, com foco na gestão de informações relacionadas ao tema "Green Tea". A aplicação permite interagir com um banco de dados, e tem como objetivo armazenar, gerenciar e exibir dados relativos ao tema. O front-end é feito em HTML, CSS e JavaScript.

---

## 2. Tecnologias Utilizadas

- **C#**: Linguagem principal para o back-end, utilizando o framework .NET.
- **ASP.NET**: Para desenvolvimento web e manipulação de rotas e páginas.
- **SQL Server / T-SQL**: Banco de dados para armazenar informações, sendo configurado através do script SQL fornecido.
- **HTML/CSS/JavaScript**: Tecnologias utilizadas para o front-end.
- **Visual Studio**: IDE recomendada para abrir e executar o projeto.
- **NuGet**: Para gerenciamento de pacotes e dependências.

---

## 3. Estrutura do Repositório

O repositório contém os seguintes arquivos e pastas:

- **greenTea.sln**: Arquivo de solução do Visual Studio, usado para abrir o projeto na IDE.
- **greenTeaDb.sql**: Script SQL para criação do banco de dados necessário para o funcionamento do projeto.
- **README.md**: Arquivo de documentação. (Atualmente sem informações adicionais, mas pode ser expandido com detalhes do projeto.)
- **.gitignore**: Arquivo de configuração do Git para ignorar arquivos desnecessários no controle de versão.
- **LICENSE**: Arquivo de licença, indicando que o projeto está sob a licença MIT.
- **Pasta "Controllers"**: Contém os controladores para a lógica de negócios da aplicação.
- **Pasta "Views"**: Contém os arquivos de visualização (páginas HTML).
- **Pasta "Models"**: Contém as classes do modelo de dados.

---

## 4. Como Rodar o Projeto

1. **Clonar o Repositório**
   - Abra um terminal ou Git Bash e execute:
     ```bash
     git clone https://github.com/pmarlon/greenTea.git
     ```

2. **Configurar o Banco de Dados**
   - Execute o script `greenTeaDb.sql` no seu servidor SQL para criar o banco de dados necessário.
   - Certifique-se de que o banco de dados está configurado corretamente para se comunicar com o back-end da aplicação.

3. **Abrir no Visual Studio**
   - Abra o arquivo `greenTea.sln` no Visual Studio.
   - Certifique-se de que os pacotes NuGet estão restaurados.

4. **Rodar a Aplicação**
   - Após restaurar os pacotes NuGet e garantir que o banco de dados está configurado, inicie a aplicação clicando em **Start** no Visual Studio.

---

## 5. Funcionalidades Principais

- **Cadastro e Armazenamento de Dados**: A aplicação pode cadastrar e armazenar informações relacionadas ao tema Green Tea.
- **Consultas ao Banco de Dados**: Utiliza SQL para consultar e recuperar informações salvas no banco.
- **Interface Web**: A interface é simples, feita em HTML/CSS/JavaScript, permitindo que o usuário interaja com o sistema.

---

## 6. Como Contribuir

1. Faça um fork deste repositório.
2. Crie uma branch para a sua feature (`git checkout -b feature/nova-feature`).
3. Faça commit das suas mudanças (`git commit -m 'Adiciona nova feature'`).
4. Envie para o repositório remoto (`git push origin feature/nova-feature`).
5. Abra um pull request para que suas mudanças sejam avaliadas.

---

## 7. Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
