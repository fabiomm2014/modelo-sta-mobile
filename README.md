<h1 align="center">📱 STA Mobile — Automação de Testes Mobile 🇧🇷</h1>

<p align="center">
  <b>Framework modelo para automação de testes de aplicativos mobile.</b><br>
  Sistema de Testes Automatizados (STA) com Appium, Selenium,
  Cucumber BDD e relatórios ExtentReports.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-8-009C3B?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 8">
  <img src="https://img.shields.io/badge/Appium-7.0-FFDF00?style=for-the-badge&logo=appium&logoColor=black" alt="Appium">
  <img src="https://img.shields.io/badge/Cucumber-BDD-002776?style=for-the-badge&logo=cucumber&logoColor=white" alt="Cucumber">
  <img src="https://img.shields.io/badge/Selenium-3.141-009C3B?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium">
  <img src="https://img.shields.io/badge/ExtentReports-3.1-FFDF00?style=for-the-badge&logoColor=black" alt="ExtentReports">
  <img src="https://img.shields.io/badge/Maven-002776?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/-009C3B?style=flat-square&color=009C3B" height="6" width="120" alt="">
  <img src="https://img.shields.io/badge/-FFDF00?style=flat-square&color=FFDF00" height="6" width="120" alt="">
  <img src="https://img.shields.io/badge/-002776?style=flat-square&color=002776" height="6" width="120" alt="">
</p>

---

## 📑 Sumário

- [🔎 Visão geral](#-visão-geral)
- [✨ Funcionalidades](#-funcionalidades)
- [🛠️ Tecnologias](#️-tecnologias)
- [🚀 Como usar](#-como-usar)
- [📄 Licença](#-licença)

---

## 🔎 Visão geral

Projeto-modelo **Maven** (Java 8) para testes automatizados de apps mobile. Usa **Appium 7.0** (java-client) para interação com dispositivos Android/iOS, **Selenium 3.141** como base WebDriver, **Cucumber** (BDD com Gherkin) para cenários e **ExtentReports** para relatórios HTML. Inclui suporte a Rest Assured (testes de serviço), Apache POI (dados Excel), DBUnit e integração com Oracle/SQL Server.

Convenção de testes: classes `CucumberRunnerTest*.java`.

---

## ✨ Funcionalidades

| Módulo | Descrição |
| :----- | :-------- |
| 📱 **Automação mobile** | Appium 7.0 (Android/iOS) |
| 🌐 **WebDriver** | Selenium 3.141 + WebDriverManager |
| 📝 **BDD** | Cenários em Gherkin com Cucumber |
| 📊 **Relatórios** | ExtentReports HTML + cucumber-extentsreport |
| 🔌 **Testes de API** | Rest Assured 4.0 |
| 📑 **Dados Excel** | Apache POI 3.15 |
| 🗄️ **Banco de dados** | DBUnit + Oracle/SQL Server/MongoDB |

---

## 🛠️ Tecnologias

| Camada | Tecnologia |
| :----- | :--------- |
| 💻 **Linguagem** | Java 8 |
| 📱 **Mobile** | Appium 7.0 (java-client) |
| 🌐 **WebDriver** | Selenium 3.141, WebDriverManager 1.6 |
| 📝 **BDD** | Cucumber 1.2.5 + Gherkin |
| 📊 **Relatórios** | ExtentReports 3.1 + cucumber-extentsreport |
| 🧪 **Testes** | JUnit 4.12, Hamcrest |
| 🔌 **API** | Rest Assured 4.0 |
| 📑 **Dados** | Apache POI 3.15 (Excel) |
| 🗄️ **Banco** | DBUnit 2.4, MongoDB 3.8, Oracle, SQL Server |
| 🔧 **Build** | Maven |

---

## 🚀 Como usar

<details open>
<summary><b>▶️ Executar testes</b></summary>

```bash
mvn test    # executa testes CucumberRunnerTest*.java
```

</details>

---

## 📄 Licença

Projeto de uso interno/educacional.

<p align="center">
  <img src="https://img.shields.io/badge/-009C3B?style=flat-square&color=009C3B" height="6" width="120" alt="">
  <img src="https://img.shields.io/badge/-FFDF00?style=flat-square&color=FFDF00" height="6" width="120" alt="">
  <img src="https://img.shields.io/badge/-002776?style=flat-square&color=002776" height="6" width="120" alt="">
</p>

<p align="center"><sub>Feito com 💚💛💙 — cores da bandeira do Brasil 🇧🇷</sub></p>
