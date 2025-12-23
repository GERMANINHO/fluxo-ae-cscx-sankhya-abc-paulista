# Fluxo AE — CS/CX Sankhya ABC Paulista

Fluxograma interativo (HTML + SVG + CSS + JS puro) do processo de **Acompanhamento Evolutivo (AE)** do time de **CS/CX Sankhya ABC Paulista**.

O projeto é **autocontido** (um único `index.html`) e pode ser publicado via **GitHub Pages**, servindo como guia operacional do time com **pop-ups (modais)** e **links diretos** (ex.: SenseData).

---

## 🔎 Visão geral

- **Objetivo**
  Padronizar a execução do AE, do diagnóstico até o plano de evolução e governança (Sintonia do Projeto), garantindo rastreabilidade no **SenseData** e uso das telas de análise no **Sankhya**.

- **Tecnologia**
  - HTML5 + SVG (desenho do fluxo)
  - CSS (tema, animações, “pulse”)
  - JavaScript (modais, teclado, acessibilidade)

- **Acessibilidade**
  - Etapas focáveis via teclado (`tabindex="0"`)
  - **Enter/Espaço** abre modal; **Esc** fecha
  - Ao fechar, o foco retorna para o elemento acionador

---

## 🧭 Como usar (fluxo operacional)

O fluxo está dividido em 8 etapas:

1. **Sankhya — CS - Acompanhamento Visita**
   - Identifica clientes em atraso e define qual cliente fará AE.
   - Caminho: Dashboards » Customer Success » CS - Acompanhamento Visita  
   - ID: `br.com.sankhya.menu.adicional.nuDsb.1003.1`

2. **SenseData — Agendamento do AE**
   - Adiciona playbook AE e registra o agendamento.

3. **SenseData — Apresentação do Plano de Trabalho**
   - Define agenda e alinhamento do dia.

4. **SenseData — Diagnóstico do AE**
   - Aplica diagnóstico com usuários/áreas envolvidas.

5. **Sankhya — CS - Acompanhamento Evolutivo (Novo)**
   - Consolida informações do cliente e visão de uso.
   - Avalia processos, define foco e gera **Plano de Ação** (Excel/PDF).
   - Caminho: Analytics AI » SankhyaMitraBI 04-04-2024 » CX » CS - Acompanhamento Evolutivo (Novo)
   - ID: `br.com.sankhya.analytics2.new.sc.t_4312.5.2265`

   **Extra obrigatório:**
   - Enviar o **Excel por e-mail** ao cliente
   - Salvar/gerar o **PDF do e-mail**
   - Anexar no SenseData: **Excel + PDF**

6. **SenseData — Montagem do Plano de Evolução**
   - Registra a montagem e anexa os arquivos.

7. **SenseData — Apresentação do Plano de Evolução**
   - Registra a apresentação ao cliente (principais melhorias, status, horas, atribuição).

8. **SenseData — Sintonia do Projeto**
   - Rotina de governança, status e próximos passos.

---

## 🔗 Links úteis

- **SenseData (Portfolio):**
  https://sankhya.sensedata.io/portfolio

---

## 🗂 Estrutura do projeto

```text
/ (raiz)
└── index.html
└── README.md
