# data_engineering-robocar
Projeto proposto pelo curso [Udemy - Formação Engenheiro de Dados](https://www.udemy.com/course/engenheiro-de-dados/).

## Introdução
A Robocar trata-se de uma locadora fictícia de veículos autônomos, que precisa de um projeto de Engenharia de Dados para:
1. Controlar a locação de veículos,
2. Fornecer dados analíticos para os gestores,
3. Ter contratos eletrônicos,
4. Gerenciar diariamente o número de contratos de risco.

## Levantamento de Requisitos

### 1. Controlar a Locação de Veículos
O Engenheiro de Dados deverá entregar:
  * Modelo Entidade-Relacionamento (__Entity Relationship Diagram - ERD__),
  * Scripts para criação das tabelas,
  * Dados para teste e desenvolvimento do software com scripts.
  ##### Cadastro de Veículos:
   * Identificador,
   * Data de Aquisição,
   * Ano,
   * Modelo,
   * Placa,
   * Status ("Disponível", "Indisponível", "Locado"),
   * Preço da Diária
  ##### Cadastro de Clientes:
   *  Identificador,
   *  CPF,
   *  Número da CNH,
   *  Data de Validade da CNH,
   *  Nome,
   *  Data de Cadastro,
   *  Data de Nascimento,
   *  Telefone,
   *  Status ("Ativo", "Inativo")
  ##### Cadastro de Despachantes
   * Identificador,
   * Nome,
   * Status ("Ativo", "Inativo"),
   * Filial
  ##### Locação
   * Veículo,
   * Data locação,
   * Valor total,
   * Cliente,
   * Despachante
### 2. Fornecer Dados Analíticos para os Gestores
Criar armazem de dados dimensional, que possa responder as perguntas:
    * Quais e quantos veículos foram locados com grão mensal?
    * Quais despachantes locaram quais veículos com grão mensal?
    * Qual o faturamento por veículo com grão mensal?
    * Qual o faturamento por despachante com grão mensal?

