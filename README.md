# 📱 STA Mobile — Automacao de Testes Mobile 🇧🇷

![Java](https://img.shields.io/badge/Java-8-009C3B?style=flat&logo=openjdk&logoColor=white)
![Appium](https://img.shields.io/badge/Appium-7.0-FFDF00?style=flat&logo=appium&logoColor=black)
![Cucumber](https://img.shields.io/badge/Cucumber-BDD-002776?style=flat&logo=cucumber&logoColor=white)

Framework modelo para automacao de testes de aplicativos mobile (Sistema de Testes Automatizados — STA).

## Visao geral

Projeto-modelo Maven (Java 8) para testes automatizados de apps mobile. Usa **Appium 7.0** (java-client) para interacao com dispositivos Android/iOS, **Selenium 3.141** como base WebDriver, **Cucumber** (BDD com Gherkin) para cenarios e **ExtentReports** para relatorios HTML. Inclui suporte a Rest Assured (testes de servico), Apache POI (dados Excel), DBUnit e integracao com Oracle/SQL Server.

Convencao de testes: classes `CucumberRunnerTest*.java`.

## Tecnologias

- **Java 8** / **Maven**
- **Appium 7.0** (java-client)
- **Selenium 3.141** / **WebDriverManager 1.6**
- **Cucumber 1.2.5** (BDD) + **Gherkin**
- **ExtentReports 3.1** + **cucumber-extentsreport**
- **JUnit 4.12** / **Hamcrest**
- **Rest Assured 4.0** (testes de servico)
- **Apache POI 3.15** (leitura de Excel)
- **DBUnit 2.4** / **MongoDB 3.8** / **Oracle/SQL Server** (JDBC)

## Como usar

```bash
mvn test    # executa testes CucumberRunnerTest*.java
```

## Licenca

Uso interno/educacional.

---
*Feito com 💚💛💙 — cores da bandeira do Brasil 🇧🇷*
