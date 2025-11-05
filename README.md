# 🌡️ Conversor de Temperaturas

[![Java](https://img.shields.io/badge/Java-8+-green)](https://www.oracle.com/java/technologies/javase-jdk8-downloads.html)
[![Maven](https://img.shields.io/badge/Maven-3.6+-C71A36)](https://maven.apache.org/)
[![JUnit5](https://img.shields.io/badge/JUnit-5-blue)](https://junit.org/junit5/)

Este é um projeto simples de **conversão de temperaturas** desenvolvido com **Java** (versão 8) e **JUnit 5** para testes automatizados. O projeto implementa a conversão entre diferentes escalas de temperatura, com foco em **Celsius**, **Fahrenheit** e **Kelvin**.

## ⚙️ Funcionalidades

O projeto contém a classe `TemperatureConverter` com os seguintes métodos de conversão:

- Celsius para Fahrenheit
- Fahrenheit para Celsius
- Celsius para Kelvin
- Kelvin para Celsius

## 🚀 Como Rodar

### Requisitos

Antes de começar, você precisa ter os seguintes requisitos instalados:

- **Java 8+**: [Baixe o JDK 8 aqui](https://www.oracle.com/java/technologies/javase-jdk8-downloads.html)
- **Maven 3.6+**: [Baixe o Maven aqui](https://maven.apache.org/download.cgi)

### Passos para Rodar o Projeto

1. Clone este repositório para a sua máquina:

   ```bash
   git clone https://seu-repositorio-url.git

   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd tdd_poo
   ```
3. Compile e execute os testes com Maven:
   ```bash
   mvn teste
   ```

# 📦 Estrutura do Projeto

O projeto segue a seguinte estrutura de diretórios:

```bash
tdd_poo/
│
├── src/
│   ├── main/
│   │   └── java/
│   │       └── converter/
│   │           └── TemperatureConverter.java
│   │
│   └── test/
│       └── java/
│           └── converter/
│               └── TemperatureConverterTest.java
│
└── pom.xml
```
• **src/main/java**: Contém a implementação da classe `TemperatureConverter`.
• **src/test/java**: Contém a classe de testes `TemperatureConverterTest`.
• **pom.xml**: Arquivo de configuração do Maven.

