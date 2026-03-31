# 🌊 Brisa de Iracema: Inteligência de Dados para Microgestão

Sistema de automação financeira e de estoque que transforma entradas não estruturadas (voz, texto e fotos de notas fiscais) em indicadores gerenciais de alto impacto.

## 🚀 O Problema
Microempreendedores do setor de serviços e alimentação sofrem com a "cegueira financeira" devido à informalidade dos registros. O **Brisa de Iracema** resolve isso automatizando a coleta de dados e o cálculo de metas de sobrevivência (*break-even*).

## 🛠️ Stack Tecnológica
* **Interface:** Telegram Bot (Ingestão de dados)
* **Orquestração:** [n8n](https://n8n.io/) (Workflow de automação)
* **IA & Processamento:** Gemini (Vision/OCR) & LLaMA 3 via Groq (NLP)
* **Banco de Dados:** Google Sheets (Arquitetura de Data Mart)
* **BI & Visualização:** Looker Studio (Dashboards de KPIs)

## 🏗️ Arquitetura da Solução
1.  **Ingestão:** Usuário envia foto da nota fiscal ou áudio de venda via Telegram.
2.  **Processamento:** n8n aciona agentes de IA para extrair itens, quantidades e valores.
3.  **Armazenamento:** Dados higienizados são inseridos no Sheets e as fórmulas de matriz calculam a meta diária.
4.  **Decisão:** O empreendedor consulta o Dashboard para ver se já atingiu o lucro do dia.



## 📊 Principais Funcionalidades
- **OCR de Notas Fiscais:** Desmembramento automático de compras complexas.
- **Cálculo Automático de Meta:** Baseado no custo real do estoque da semana.
- **Mix de Produtos:** Visão visual de onde o capital está imobilizado.
- **Saúde Financeira:** Indicador de recuperação de investimento em tempo real.

## 👨‍💻 Autor
**Rodrigo** - Estudante de Análise e Desenvolvimento de Sistemas (ADS)
