# 🏫 Sistema Escolar - Herança e Polimorfismo

Projeto simples para praticar **herança** e **encapsulamento** em Java, simulando um sistema de uma escola com diferentes tipos de pessoas.

## O que o sistema faz?

- Cadastra **Alunos**, **Bolsistas** e **Visitantes**
- Aluno pode pagar mensalidade
- Bolsista renova bolsa e paga mensalidade com desconto (sobrescrita de método)
- Visitante é apenas uma pessoa, sem ações extras
- Lista todas as pessoas com seus dados

## Como executar


## Conceitos praticados

- **Herança**: `Aluno` e `Visitante` herdam de `Pessoa`; `Bolsista` herda de `Aluno`
- **Polimorfismo**: tratamos diferentes tipos de pessoa como `Pessoa`
- **Sobrescrita**: `Bolsista` sobrescreve `pagarMensalidade()`
- **Encapsulamento**: atributos privados com getters/setters

---
**Autor:** Kayke Vieira 
