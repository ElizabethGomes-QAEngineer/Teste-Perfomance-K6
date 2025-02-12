# Teste Perfomance K6

![Texto alternativo](OrangeHRM.png)

# Testes de Desempenho, Carga, Smoke e Stress
Este repositório contém um conjunto de testes abrangentes projetados para avaliar o desempenho e a confiabilidade do sistema em diferentes cenários. Os testes implementados incluem:

**Teste de Desempenho**
Este teste tem como objetivo medir o tempo de resposta, a taxa de transferência e a utilização de recursos do sistema sob condições normais de operação. Os resultados fornecem insights sobre a capacidade do sistema de lidar com a carga esperada de usuários e transações, além de identificar possíveis gargalos e áreas de otimização.

**Teste de Carga**
Simula um número crescente de usuários acessando o sistema simultaneamente para determinar o ponto em que o desempenho começa a degradar ou o sistema falha. Os resultados ajudam a identificar os limites de capacidade do sistema e a entender como ele se comporta sob condições de carga máxima.

**Teste de Fumaça (Smoke Test)**
Rápido e superficial verifica as funcionalidades básicas do sistema para garantir que ele esteja funcionando corretamente após uma nova versão ou alteração. O teste de fumaça é executado em um ambiente de teste para identificar problemas críticos precocemente e evitar que sejam propagados para ambientes de produção.

**Teste de Stress**
Submete o sistema a condições extremas de carga, como um número muito alto de usuários ou transações, para identificar seus pontos fracos e determinar como ele se recupera de falhas. Os resultados ajudam a garantir que o sistema seja resiliente e capaz de lidar com situações inesperadas.



## ⚙️ Installar

O comando npm install chance instala a biblioteca Chance.js, que é uma ferramenta simples e poderosa para gerar dados aleatórios em JavaScript. Ele foi utilizado neste projeto e será necessário.

```bash
npm install chance
```
## ✅ Pre Requisitos

> **💡 NOTA:**
> 
> È necessário ter o [Node.js](https://nodejs.org)  instalado



## 📝 Passo a Passo para Instalação




**1.** **Clone o repositório na sua maquina 🖥️**

```bash
git clone https://github.com/ElizabethGomes-QAEngineer/Automacao-Cypress-Java-Script-Orange-HRM.git
```

**2.** **Navegue até o diretório do projeto 📂**

```bash
cd cypress-hrm
````


**3.** **Instale as dependências do projeto 📦**

```bash
npm install 
```

**4.** **Execute o Cypress para rodar os testes 🚀**

abrir o Cypress com interface gráfica (GUI - Graphical User Interface)

```bash
npx cypress open
````

executar no modo headless (sem interface gráfica)

```bash
npx cypress run 
```



>
>**📜 ** **Nota** Este Projeto possui **CI***:
>Acessando CI através da branch **"ci-last"**
>clicar em ***github/workflows**
>clicar em git hub **"action**
