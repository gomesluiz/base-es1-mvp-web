# 2. Guia de Preenchimento das Histórias (GitHub Issues)

> **Atenção:** Neste projeto, nós utilizamos o GitHub Issues como a fonte da verdade para o nosso Backlog. Este documento serve apenas como um guia de referência de qualidade.

## Como registrar um novo PBI (Product Backlog Item)
1. Acesse a aba **Issues** do repositório deste projeto no GitHub.
2. Clique no botão verde **New Issue**.
3. Selecione o template **Item do PBB (História + BDD)**.
4. Preencha o formulário seguindo rigorosamente o padrão de exemplo abaixo.

---

## Exemplo de Preenchimento Ideal

### História
* **Como um** Analista Financeiro
* **eu devo** emitir o relatório de inadimplência em PDF
* **para** notificar os condôminos em atraso.

### Critérios de Aceite (BDD)
**Cenário 1: Geração com sucesso**
* **Dado que** existam faturas vencidas no mês atual
* **Quando** eu clico em "Gerar Relatório de Inadimplência"
* **Então** o sistema deve fazer o download de um arquivo .pdf
* **E** o arquivo deve conter o valor exato dos juros calculados.

### Habilitadores
* [Técnico] 1: Configurar a biblioteca de geração de PDF (ex: puppeteer ou pdfkit) no backend.

### Tarefas
- [ ] Criar a rota GET `/api/relatorios/inadimplencia`
- [ ] Implementar a query de busca de faturas no banco de dados.
- [ ] Escrever o teste unitário cobrindo o Cenário 1 de sucesso.
- [ ] Integrar o botão de download no painel financeiro do front-end.

### Interface
* A interface deve ser composta por um botão com o rótulo "Gerar Relatório", posicionado no canto superior direito da listagem de faturas.
* O botão deve exibir um ícone de "loading" (spinner) durante o tempo de processamento do PDF.
* **Protótipo no Figma:** [Cole aqui o link direto para a tela no Figma]