# 🚀 [NOME DO PRODUTO]

> **Template Base para Engenharia de Software Moderna e Desenvolvimento Orientado por Especificação (SDD).**

![License](https://img.shields.io/badge/license-MIT-green)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Python Version](https://img.shields.io/badge/python-3.11+-blue)
![Framework](https://img.shields.io/badge/framework-Flask-lightgrey)
![Architecture](https://img.shields.io/badge/architecture-Clean_Architecture-orange)
![Methodology](https://img.shields.io/badge/methodology-Lean_Inception_%2F_PBB-blueviolet)

Este repositório serve como alicerce para o desenvolvimento de soluções robustas, priorizando a compreensão do domínio de negócio antes da implementação técnica. Nesta versão, a stack de referência é **Python com Flask**, utilizando a Inteligência Artificial como uma ferramenta de **geração de código** e **orquestração arquitetural**.

---

## 👥 Equipe
Identifique abaixo os integrantes responsáveis pelo desenvolvimento deste projeto:

* **Integrante 1** - [Nome Completo] - [GitHub/LinkedIn]
* **Integrante 2** - [Nome Completo] - [GitHub/LinkedIn]
* **Integrante 3** - [Nome Completo] - [GitHub/LinkedIn]
* **Integrante 4** - [Nome Completo] - [GitHub/LinkedIn]
* **Integrante 5** - [Nome Completo] - [GitHub/LinkedIn]

---

## 🗺️ Ciclo de Vida do Projeto

O desenvolvimento está estruturado em quatro etapas fundamentais, garantindo a rastreabilidade desde a concepção até a entrega contínua:

### 1. Etapa 1: Concepção do Produto
Foco em Descoberta (*Discovery*) utilizando o framework **Lean Inception** para alinhar objetivos e definir o MVP.
* Artefatos: [`/docs/01_lean_inception/`](./docs/01_lean_inception/)

### 2. Etapa 2: Construção do Backlog
Refinamento das funcionalidades e criação de itens do backlog via **Product Backlog Building (PBB)**, conectando o Canvas à lista de prioridades.
* Artefatos: [`/docs/02_pbb/`](./docs/02_pbb/)

### 3. Etapa 3: Prototipação e Desenvolvimento
Execução técnica focada na entrega da Sprint 1 utilizando **Python/Flask**.
* Código-fonte: [`/src/`](./src/) | Testes: [`/tests/`](./tests/)

### 4. Etapa 4: Implantação e DevOps
Automação de processos de integração e entrega contínua (CI/CD) via GitHub Actions.
* Configurações: [`.github/workflows/`](./.github/workflows/)

---

## 🛡️ Governança e Constituição da IA (`.cursorrules`)

Este projeto é regido por uma **Constituição Sistêmica** detalhada no arquivo `.cursorrules`. Estas diretrizes são inegociáveis para qualquer agente de IA utilizado no desenvolvimento:

* **Segurança de Dados (LGPD):** É mandatória a criptografia de dados sensíveis em trânsito e em repouso.
* **Qualidade de Código:** Proibição estrita de padrões de código acoplado (*spaghetti code*). Prioriza-se a separação de responsabilidades (SoC) e Clean Architecture.
* **TDD:** A IA deve obrigatoriamente garantir a cobertura de testes para cada regra de negócio implementada.

---

## ⚙️ Customização da Stack Tecnológica

Caso opte por migrar este template para outra tecnologia (ex: Node.js, .NET, Ruby on Rails), os seguintes arquivos **devem** ser ajustados para garantir a integridade da automação e governança:

1.  **`Dockerfile`**: Atualize a imagem base e os comandos de build/instalação.
2.  **`.github/workflows/ci-cd.yml`**: Ajuste as Actions de setup e os comandos de execução de testes.
3.  **Arquivo de dependências**: Substitua o `requirements.txt` pelo equivalente da nova stack (ex: `package.json`, `Gemfile` ou `.csproj`).
4.  **`.cursorrules`**: Revise as instruções específicas de sintaxe e padrões de projeto da nova linguagem para orientar a IA corretamente.
5.  **`README.md`**: Atualize os badges iniciais e as instruções de instalação.

---

## 🚀 Como Iniciar (Ambiente Python/Flask)

1.  **Clonar o repositório:**
    ```bash
    git clone [https://github.com/usuario/nome-do-produto.git](https://github.com/usuario/nome-do-produto.git)
    ```
2.  **Configurar o Ambiente Virtual (VENV):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/macOS
    # ou
    .\venv\Scripts\activate  # Windows
    ```
3.  **Instalar dependências:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Executar a suíte de testes:**
    ```bash
    pytest
    ```

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License**. Consulte o arquivo `LICENSE` para mais detalhes.