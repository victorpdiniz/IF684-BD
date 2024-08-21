# Projeto de Banco de Dados para Clínica Médica

Este repositório contém o projeto de banco de dados desenvolvido como parte da disciplina **IF685 - Gestão de Dados e Informação** do curso de Engenharia da Computação. O objetivo deste projeto é modelar e implementar um banco de dados para uma clínica médica, seguindo um processo dividido em três unidades: modelagem conceitual, modelagem lógica e implementação em SQL.

## Estrutura do Projeto

O projeto está dividido em três etapas principais, cada uma correspondendo a uma unidade da disciplina:

### 1. Modelagem Conceitual
Nesta etapa, desenvolvemos o **Modelo Entidade-Relacionamento (MER)** para a clínica médica, identificando:
- **Entidades:** Pacientes, Médicos, Consultas, Receitas, Exames, etc.
- **Relacionamentos:** Consultas realizadas por médicos, Exames solicitados nas consultas, Receitas prescritas, etc.
- **Atributos:** Nome do paciente, Data da consulta, Especialidade do médico, Resultados de exames, etc.

O diagrama ER foi construído utilizando a ferramenta EERCASE, e está disponível na pasta `proj_conceitual/`.

### 2. Modelagem Lógica Relacional
Com base no MER, elaboramos o **Modelo Lógico** utilizando as regras de normalização de Codd. Nesta fase, definimos:
- **Tabelas:** Pacientes, Médicos, Consultas, Exames, Receitas, etc.
- **Atributos:** Detalhamento das colunas.
- **Chaves Primárias e Estrangeiras:** Identificação dos relacionamentos entre as tabelas.

O PDF correspondente à modelagem lógica pode ser encontrado na pasta `proj_logico/`.

### 3. Implementação em SQL
Finalmente, implementamos o banco de dados utilizando **SQL**. Nesta etapa, realizamos:
- **Criação das Tabelas:** Scripts para criar as tabelas no banco de dados.
- **Inserção de Dados:** Scripts para popular as tabelas com dados fictícios.
- **Consultas SQL:** Exemplos de consultas que podem ser realizadas, como listar consultas de um paciente, receitas prescritas por um médico, etc.

Os scripts SQL estão disponíveis na pasta `proj_fisico/`.

## Referências
- Clone este repositório:
   ```bash
   git clone https://github.com/victorpdiniz/IF685-BD.git
- Download da ferramenta EERCASE: https://sites.google.com/a/cin.ufpe.br/eercase/home