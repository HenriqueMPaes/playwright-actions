
# ⚡ Automação de Testes E2E com Playwright + CI (GitHub Actions)

Projeto de automação de testes end-to-end (E2E) utilizando **Playwright**, com execução automatizada via **GitHub Actions**, simulando um pipeline real de CI/CD.

----------

## 🎯 Objetivo

Este projeto tem como objetivo demonstrar habilidades em:

-   Automação de testes E2E modernos
    
-   Integração com pipelines de CI/CD
    
-   Execução automatizada de testes a cada alteração no código
    
-   Garantia de qualidade contínua (Continuous Testing)
    

----------

## 🚀 Tecnologias utilizadas

-   🟨 JavaScript / TypeScript
    
-   🎭 Playwright
    
-   ⚙️ GitHub Actions
    
-   🌐 Node.js
    
-   📄 HTML Reports (Playwright)
    

----------

## 🧱 Arquitetura do projeto

O projeto segue boas práticas de automação E2E com Playwright:

```
playwright-actions/
├── tests/                 # Casos de teste E2E
├── playwright.config.ts   # Configuração do Playwright
├── .github/
│   └── workflows/
│       └── playwright.yml # Pipeline CI
├── package.json           # Dependências do projeto
└── README.md

```

----------

## 🔄 Pipeline CI/CD (GitHub Actions)

Os testes são executados automaticamente através do GitHub Actions:

### 📌 Quando o pipeline roda:

-   A cada `push`
    
-   A cada `pull request`
    

### ⚙️ Etapas do pipeline:

1.  Checkout do código
    
2.  Instalação do Node.js
    
3.  Instalação das dependências (`npm ci`)
    
4.  Instalação dos browsers do Playwright
    
5.  Execução dos testes (`npx playwright test`)
    
6.  Geração de relatórios
    

💡 Esse fluxo garante que os testes rodem automaticamente em um ambiente limpo e padronizado.

----------

## 🧪 Cenários de teste

Os testes automatizados cobrem:

-   ✅ Fluxos completos do usuário (E2E)
    
-   ✅ Navegação entre páginas
    
-   ✅ Interações com elementos da UI
    
-   ✅ Validação de comportamento da aplicação
    
-   ✅ Testes cross-browser (quando configurado)
    

----------

## ⚙️ Como executar localmente

### Pré-requisitos

-   Node.js instalado
    
-   NPM ou Yarn
    

----------

### Passos

```bash
git clone https://github.com/HenriqueMPaes/playwright-actions.git
cd playwright-actions
npm install

```

### Instalar browsers:

```bash
npx playwright install --with-deps

```

### Rodar os testes:

```bash
npx playwright test

```

----------

## 📊 Relatórios de teste

O Playwright gera relatórios HTML com:

-   Resultados dos testes
    
-   Screenshots
    
-   Vídeos (quando habilitado)
    
-   Logs detalhados
    

----------

## 📊 Boas práticas aplicadas

-   Automação E2E com Playwright
    
-   Execução em CI/CD
    
-   Ambiente isolado e reproduzível
    
-   Testes organizados e escaláveis
    
-   Pipeline automatizado
    

----------

## 💼 Valor para o portfólio QA

Este projeto demonstra:

-   ✔️ Automação E2E moderna com Playwright
    
-   ✔️ Integração com GitHub Actions (CI/CD)
    
-   ✔️ Execução automática de testes
    
-   ✔️ Conhecimento em pipelines de qualidade
    
-   ✔️ Mentalidade DevOps aplicada a QA
    

----------

## 🔮 Possíveis melhorias

-   Execução paralela de testes
    
-   Integração com Allure Reports
    
-   Deploy automático com validação de testes
    
-   Testes em múltiplos ambientes
    
-   Integração com cloud (BrowserStack)
----------

## 🤝 Contato

Caso queira trocar ideias sobre QA, automação ou oportunidades:

-   LinkedIn: https://www.linkedin.com/in/henriquepaesprofissional/
    
-   Email: henrique.mpaes@outlook.com
    

----------

## 📄 Licença

Projeto com fins educacionais e de demonstração de portfólio.
# ⚡ Automação de Testes E2E com Playwright + CI (GitHub Actions)

Projeto de automação de testes end-to-end (E2E) utilizando **Playwright**, com execução automatizada via **GitHub Actions**, simulando um pipeline real de CI/CD.

----------

## 🎯 Objetivo

Este projeto tem como objetivo demonstrar habilidades em:

-   Automação de testes E2E modernos
    
-   Integração com pipelines de CI/CD
    
-   Execução automatizada de testes a cada alteração no código
    
-   Garantia de qualidade contínua (Continuous Testing)
    

----------

## 🚀 Tecnologias utilizadas

-   🟨 JavaScript / TypeScript
    
-   🎭 Playwright
    
-   ⚙️ GitHub Actions
    
-   🌐 Node.js
    
-   📄 HTML Reports (Playwright)
    

----------

## 🧱 Arquitetura do projeto

O projeto segue boas práticas de automação E2E com Playwright:

```
playwright-actions/
├── tests/                 # Casos de teste E2E
├── playwright.config.ts   # Configuração do Playwright
├── .github/
│   └── workflows/
│       └── playwright.yml # Pipeline CI
├── package.json           # Dependências do projeto
└── README.md

```

----------

## 🔄 Pipeline CI/CD (GitHub Actions)

Os testes são executados automaticamente através do GitHub Actions:

### 📌 Quando o pipeline roda:

-   A cada `push`
    
-   A cada `pull request`
    

### ⚙️ Etapas do pipeline:

1.  Checkout do código
    
2.  Instalação do Node.js
    
3.  Instalação das dependências (`npm ci`)
    
4.  Instalação dos browsers do Playwright
    
5.  Execução dos testes (`npx playwright test`)
    
6.  Geração de relatórios
    

💡 Esse fluxo garante que os testes rodem automaticamente em um ambiente limpo e padronizado.

----------

## 🧪 Cenários de teste

Os testes automatizados cobrem:

-   ✅ Fluxos completos do usuário (E2E)
    
-   ✅ Navegação entre páginas
    
-   ✅ Interações com elementos da UI
    
-   ✅ Validação de comportamento da aplicação
    
-   ✅ Testes cross-browser (quando configurado)
    

----------

## ⚙️ Como executar localmente

### Pré-requisitos

-   Node.js instalado
    
-   NPM ou Yarn
    

----------

### Passos

```bash
git clone https://github.com/HenriqueMPaes/playwright-actions.git
cd playwright-actions
npm install

```

### Instalar browsers:

```bash
npx playwright install --with-deps

```

### Rodar os testes:

```bash
npx playwright test

```

----------

## 📊 Relatórios de teste

O Playwright gera relatórios HTML com:

-   Resultados dos testes
    
-   Screenshots
    
-   Vídeos (quando habilitado)
    
-   Logs detalhados
    

----------

## 📊 Boas práticas aplicadas

-   Automação E2E com Playwright
    
-   Execução em CI/CD
    
-   Ambiente isolado e reproduzível
    
-   Testes organizados e escaláveis
    
-   Pipeline automatizado
    

----------

## 💼 Valor para o portfólio QA

Este projeto demonstra:

-   ✔️ Automação E2E moderna com Playwright
    
-   ✔️ Integração com GitHub Actions (CI/CD)
    
-   ✔️ Execução automática de testes
    
-   ✔️ Conhecimento em pipelines de qualidade
    
-   ✔️ Mentalidade DevOps aplicada a QA
    

----------

## 🔮 Possíveis melhorias

-   Execução paralela de testes
    
-   Integração com Allure Reports
    
-   Deploy automático com validação de testes
    
-   Testes em múltiplos ambientes
    
-   Integração com cloud (BrowserStack)
----------

## 🤝 Contato

Caso queira trocar ideias sobre QA, automação ou oportunidades:

-   LinkedIn: https://www.linkedin.com/in/henriquepaesprofissional/
    
-   Email: henrique.mpaes@outlook.com
    

----------

## 📄 Licença

Projeto com fins educacionais e de demonstração de portfólio.
