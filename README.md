# ✈️ Sistema de Concessão de Diárias e Prestação de Contas

Este repositório apresenta a arquitetura de processos, modelagem analítica em notação BPMN e a especificação técnica de requisitos para um sistema de gestão de viagens corporativas e governamentais.

---

## 💾 Downloads e Acesso Rápido

Acesse e baixe os artefatos do projeto diretamente nos botões ou na tabela abaixo:

[![Baixar Documentação Completa (PDF)](https://img.shields.io/badge/Download-Especificação_Técnica_(PDF)-2ea44f?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](./especificacao-tecnica-scadp.pdf)
[![Baixar BPMN Editável](https://img.shields.io/badge/Download-Arquivo_BPMN_Editável-0052cc?style=for-the-badge&logo=bizagi&logoColor=white)](./bpmn-scadp-v1.0.bpmn)

<br/>

| Recurso / Artefato | Descrição | Link de Download / Visualização |
| :--- | :--- | :---: |
| 📄 **Documentação do Projeto** | Especificação completa em PDF (18 RFs, RNFs, LGPD, Histórias de Usuário e Gherkin) | [⬇️ Baixar PDF](./especificacao-tecnica-scadp.pdf) |
| ⚙️ **Modelagem Original (.bpmn)** | Arquivo XML nativo para importação no Camunda / BPMN.io | [⬇️ Baixar .BPMN](./bpmn-scadp-v1.0.bpmn) |
| 🖼️ **Diagrama do Processo (PNG)** | Imagem em alta resolução da modelagem de processos | [🖼️ Baixar PNG](./diagrama-scadp-v1.0.png) |

---

## 🎯 O Problema Resolvido

O fluxo foi projetado com foco em governança e integridade de dados, eliminando o problema clássico de "loops infinitos" em prestações de contas rejeitadas. Foram implementadas regras de negócio automatizadas para controle estrito de reincidências e desvios automáticos para tratamento de irregularidades pela área de Recursos Humanos.

---

## 🗺️ Modelagem do Processo (BPMN)

Abaixo está a representação visual do ecossistema de validação sequencial após a auditoria do processo:

<p align="center">
  <a href="./diagrama-scadp-v1.0.png" target="_blank">
    <img src="diagrama-scadp-v1.0.png" alt="Fluxograma do Processo BPMN" width="100%" style="border-radius: 8px; border: 1px solid #e1e4e8;"/>
  </a>
  <br/>
  <small><i>Clique na imagem para abrir em alta resolução ou <a href="./diagrama-scadp-v1.0.png" download>faça o download aqui</a>.</i></small>
</p>

---

## 📑 Documentação Técnica Completa (PDFs)

Devido à alta densidade e profundidade da especificação de Engenharia de Software, os artefatos foram organizados em documentos dedicados para leitura detalhada:

* 📄 **[Baixar Documentação Completa do Projeto (PDF)](./especificacao-tecnica-scadp.pdf)**  
  *Contém os 18 Requisitos Funcionais mapeados nas atividades, os Requisitos Não Funcionais correspondentes focados em LGPD, User Stories no padrão ágil, os critérios de aceite mapeados em formato Gherkin (Dado/Quando/Então) para validação dos cenários de teste, segurança de back-end e performance.*

* ⚙️ **[Baixar Arquivo de Modelagem Original (.bpmn)](./bpmn-scadp-v1.0.bpmn)**  
  *Arquivo XML nativo para importação direta na ferramenta BPMN.io ou Camunda.*

---

## 🛠️ Ferramentas e Metodologias

![BPMN 2.0](https://img.shields.io/badge/BPMN-2.0-0052cc?style=flat-square)
![Camunda / BPMN.io](https://img.shields.io/badge/Camunda-BPMN.io-orange?style=flat-square)
![Engenharia de Requisitos](https://img.shields.io/badge/Engenharia-Requisitos-2ea44f?style=flat-square)
![LGPD & Governança](https://img.shields.io/badge/LGPD-Governança-blueviolet?style=flat-square)
![Gherkin](https://img.shields.io/badge/BDD-Gherkin-23d160?style=flat-square)

---

## 👨‍💻 Autor

**Álvaro Costa**  
*Analista de Sistemas | Analista de Negócios e Requisitos*

Especializado em:
- Engenharia de Requisitos
- BPMN
- Business Analysis
- Modelagem de Processos
- Levantamento e Especificação de Requisitos
