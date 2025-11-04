 🔴 selenium-bdd-qa

![Java](https://img.shields.io/badge/Java-21-blue)
![Maven](https://img.shields.io/badge/Maven-3.9.11-blueviolet)
![Selenium](https://img.shields.io/badge/Selenium-4.38.0-green)

Forked from: [marcoslimaqa/bootcamp-bdd-everis-dio](https://github.com/marcoslimaqa/bootcamp-bdd-everis-dio)  
Meu fork: Este repositório é um fork pessoal do Bootcamp do Bradesco, adaptado para automação de navegador usando Selenium, ChromeDriver e Java, com foco em BDD, QA e testes automatizados.  



 🚀 Sobre o projeto

Este projeto tem como objetivo demonstrar, de forma prática e intuitiva, como automatizar testes em páginas web utilizando Selenium WebDriver com Java, integrado ao Google Chrome através do ChromeDriver.  

Seguindo conceitos de BDD (Behavior Driven Development) e QA (Quality Assurance), este projeto é um exemplo didático de automação de testes e organização de projetos Java com Maven.



⚙️ Tecnologias utilizadas

- Java 21 – Linguagem de programação utilizada.  
- Maven – Gerenciamento de dependências e construção do projeto.  
- Selenium 4.38.0 – Framework de automação de navegador.  
- ChromeDriver – Para controlar o Google Chrome via Selenium.  
- Apache Commons IO – Manipulação de arquivos e screenshots.  
- Conceitos de BDD, QA e Automação de Testes.  



📂 Estrutura do projeto

selenium-bdd-qa/
├─ pom.xml # Configuração do Maven e dependências
├─ README.md # Este arquivo
└─ src/
└─ main/
└─ java/
└─ org/
└─ example/
└─ chromedriver/
└─ TestChromeDriver.java # Classe que realiza o teste automatizado

markdown
Copiar código

Detalhes da classe `TestChromeDriver.java`: 

- Abre o navegador Google Chrome.  
- Navega até o Google.  
- Pesquisa por `"OpenAI GPT-5"`.  
- Imprime o título da página no console.  
- Salva um **screenshot** (`google_search.png`) na pasta do projeto.  



 📝 Funcionalidades do teste

1. Controle do navegador via Selenium WebDriver.  
2. Integração com ChromeDriver para abrir o Google Chrome.  
3. Automatização de pesquisa no Google.  
4. Captura de informações da página e impressão do título.  
5. Geração de screenshot como registro visual do teste.  



 🚀 Como rodar

1. Configurar o ChromeDriver: 
   Certifique-se que o ChromeDriver está no PATH do Windows ou configure diretamente no código:

```java
System.setProperty("webdriver.chrome.driver", "C:\\WebDrivers\\chromedriver.exe");
