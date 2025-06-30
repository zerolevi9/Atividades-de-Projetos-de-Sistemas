# 🌐 API de Cadastro de Pessoas e Endereços - Projeto de Sistemas (PS)

Bem-vindo ao repositório da atividade de **API REST para Cadastro de Pessoas e Endereços** da disciplina *Projeto de Sistemas*! 🚀  
Aqui você encontrará uma API simples, criada com o objetivo de praticar conceitos de modelagem de dados, relacionamentos e rotas REST.

---

## 📋 Descrição da Atividade

A proposta da atividade é:  

> **"Crie uma API para cadastrar uma pessoa (Nome, Idade e Email) e seus endereços (Logradouro, Número, Estado (UF), Cidade e Bairro). Uma pessoa pode ter mais de um endereço.**  
> A API deve ter uma rota para cadastrar Pessoa e outra para Endereço.  
> Ao cadastrar o endereço, deve ser enviado o ID da pessoa.  
> Ao listar uma pessoa, a API deve trazer os dados da pessoa e a lista de seus endereços."**

Essa atividade tem como foco a construção de relacionamentos entre entidades e a criação de rotas RESTful com retorno em JSON.

---

## 🧱 Estrutura do Projeto

- `Pessoa.java` ➡️ Classe modelo da pessoa.
- `Endereco.java` ➡️ Classe modelo do endereço.
- `PessoaController.java` ➡️ Controlador responsável pelas rotas da Pessoa.
- `EnderecoController.java` ➡️ Controlador responsável pelas rotas de Endereço.
- `PessoaService.java` / `EnderecoService.java` ➡️ Regras de negócio.
- `PessoaRepository.java` / `EnderecoRepository.java` ➡️ Acesso ao banco (JPA).
- `application.properties` ➡️ Configurações do banco de dados.
- `README.md` ➡️ Este arquivo com todas as instruções do projeto.

---

## 🚀 Como Executar

1. **Clone o repositório**  
   ```bash
   git clone https://github.com/seu-usuario/api-cadastro-pessoas.git](https://github.com/zerolevi9/Atividades-de-Projetos-de-Sistemas.git
