# 📊 Base de Dados - Desafio Xbox Game Pass

Este arquivo foi criado para organizar e analisar informações relacionadas a assinaturas do Xbox Game Pass, além de incluir cálculos e materiais de apoio para um dashboard visual.

## 📁 Estrutura do Arquivo

### Planilha "Assets"
Contém elementos de design usados na construção do dashboard:
- Paleta de cores utilizadas
- Códigos hexadecimais das cores principais
- Indicações de tons de destaque e áreas negativas

*Esta aba serve como guia visual para manter a identidade do painel consistente.*

### Planilha "Bases"
Reúne os dados brutos das assinaturas. Cada linha representa um assinante.

**Campos identificados:**
- `Subscriber ID`: código único do cliente
- `Name`: nome do assinante
- `Plan`: tipo de plano (Ultimate, Core, Standard)
- `Start Date`: data de início da assinatura
- `Auto Renewal`: indica se a renovação automática está ativada
- `Subscription Price`: preço base do plano
- `Subscription Type`: periodicidade (mensal, anual, quadrimestral)
- `EA Play Season Pass`: indica se o cliente possui passes adicionais
- `Minecraft Season Pass`: indica se o cliente possui passes adicionais
- `Coupon Value`: descontos aplicados
- `Total Value`: valor total pago considerando passes e cupons

*Esta é a principal base usada para os cálculos e visualizações.*

### Planilha "Cálculos"
Inclui perguntas de negócio e direcionamentos para análises:
- Faturamento total por tipo de plano
- Comparação entre assinaturas com e sem passes adicionais
- Impacto dos cupons de desconto
- Outras métricas que ajudam a medir o desempenho das assinaturas

### Planilha "Dashboard"
Serve como base de referência para a construção do painel de visualização dos resultados.

Concentra títulos e rótulos que serão utilizados na apresentação gráfica dos dados (como "XBOX GAME PASS SUBSCRIPTION SALES").

## 🎯 Objetivo do Projeto

A base de dados foi criada como parte de um desafio analítico voltado a praticar conceitos de:
- Limpeza e tratamento de dados
- Estruturação de dashboards
- Análise de métricas de assinatura
- Aplicação de perguntas de negócio em contexto real

## ⚠️ Observações

- Algumas células contêm informações visuais ou fórmulas que não aparecem no formato de texto
- O arquivo é compatível com Power BI, Excel e outras ferramentas de BI
- Recomenda-se preservar o layout original das abas "Assets" e "Dashboard" para manter a identidade visual do projeto

## 🛠️ Ferramentas Compatíveis

- Microsoft Excel
- Microsoft Power BI
- Google Sheets
- Outras ferramentas de Business Intelligence

---

*Documentação criada para organizar e documentar o projeto de análise de assinaturas do Xbox Game Pass.*
