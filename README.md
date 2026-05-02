# Conta Bancaria

![Status](https://img.shields.io/badge/status-projeto%20de%20estudo-2563eb)
![Java](https://img.shields.io/badge/Java-POO-f97316)
![CI](https://github.com/Widineii/contabancaria/actions/workflows/ci.yml/badge.svg)

Projeto simples em Java criado para praticar os primeiros conceitos de **programacao orientada a objetos**.

## O que o projeto demonstra

- Criacao de classe Java
- Atributos privados
- Encapsulamento com getters e setters
- Instanciacao de objeto
- Alteracao e exibicao de dados no console

## Estrutura

```text
src
|-- ContaBancaria.java
`-- Principal.java
```

## Como executar

Compile os arquivos:

```bash
javac -encoding UTF-8 -d out src/*.java
```

Execute:

```bash
java -cp out Principal
```

## Saida esperada

```text
Numero da Conta: 123
Saldo: 1000.0
Titular: Joao
Novo Saldo: 1500.0
```

## Proximas melhorias

- Criar metodos `depositar` e `sacar`
- Validar saldo antes de saque
- Criar construtor para inicializar a conta
- Adicionar menu interativo no console
- Separar exemplos em mais classes de estudo

## Autor

Desenvolvido por **Widinei Martins**.

- GitHub: [github.com/Widineii](https://github.com/Widineii)
- LinkedIn: [linkedin.com/in/widineimartinsdev](https://www.linkedin.com/in/widineimartinsdev)
