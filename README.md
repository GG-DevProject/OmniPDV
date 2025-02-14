# OmniPDV

### Um **único sistema de PDV** com versões diferentes:  

- **PDV Lite** → Para pequenos negócios, focado em simplicidade e custo baixo  
- **PDV Pro** → Para empresas maiores, com funcionalidades avançadas  

---

## 🎯 **Estrutura do Projeto**  

### 🏗 **Tech Stack**  
✅ **Front-end**: React.js / Vue.js (para web) + React Native (para mobile)  
✅ **Back-end**: Node.js + Express / NestJS (com APIs REST)  
✅ **Banco de Dados**:  
  - **Lite**: SQLite ou Firebase (para facilitar)  
  - **Pro**: PostgreSQL / MySQL (com estrutura robusta)  
✅ **Armazenamento Offline**: IndexedDB ou LocalStorage  
✅ **Pagamentos**: OpenPix API / Mercado Pago / PagSeguro  
✅ **Impressoras Fiscais & SAT**: Comunicação via Node.js (Bibliotecas como **escpos** para impressoras térmicas)  
✅ **Sincronização de Dados**: Firebase Firestore / WebSockets para manter PDV online e offline  

---

## 🏷️ **PDV Lite – Para Pequenos Negócios**  
🔹 Cadastro básico de produtos e categorias  
🔹 Registro de vendas e emissão de recibo (PDF)  
🔹 Controle de estoque simples  
🔹 Geração de QR Code para pagamento via Pix  
🔹 Funciona offline com sincronização automática quando conectado  

---

## 🏢 **PDV Pro – Para Negócios Maiores**  
🔥 **Tudo do PDV Lite + funcionalidades avançadas:**  
🔹 Integração com impressoras fiscais (Epson, Bematech)  
🔹 Emissão de Nota Fiscal (NF-e / NFC-e)  
🔹 Suporte a pagamentos com cartão (TEF integrado)  
🔹 Módulo de relatórios detalhados de vendas e estoque  
🔹 Dashboard avançado com gráficos de faturamento  
🔹 Controle multi-loja e multi-caixa  
🔹 Gestão de funcionários com níveis de permissão  

---

## 📱 **Extra: Aplicativo Mobile para Vendedores**  
📌 Um app para vendedores registrarem pedidos no celular/tablet  
📌 Integração com NFC e Google Pay / Apple Pay  
📌 Consulta rápida de preços via scanner de código de barras  

---

## 🚀 **Monetização da Plataforma**  
💰 **Plano Grátis (PDV Lite)** → Para pequenos negócios, monetizando via taxa de transação  
💰 **Plano Pro** → Cobrança mensal com recursos premium  
💰 **Marketplace de Plugins** → Cobrança por módulos extras (Ex: SAT Fiscal, Integração com ERPs, Dashboards avançados)  

---
