# ServiceExpress 🚀
*Estrutura Digital Express (Landing Page + Google Maps + Máquina de Avaliações)*

O **ServiceExpress** é uma solução de alta conversão desenvolvida sob medida para clínicas de **Harmonização Facial** e **Odontologia**. O objetivo é conectar profissionais locais ao topo do mercado digital com entregas rápidas, design imersivo em tecnologia e automação de avaliações.

---

## 🛠️ Stack Tecnológica & Padrões

A solução foi projetada como um produto digital de alta performance, contido em arquitetura limpa e moderna:
* **Formato:** Arquivo único otimizado (`index.html`).
* **Front-End:** HTML5 puro integrado com **Tailwind CSS** (via CDN) para estilização ágil e responsiva.
* **Interatividade:** **Alpine.js** para gerenciamento de estados, abas dinâmicas e acordeons de FAQ.
* **Estética:** *Tech Dark / Cyber-Premium* (fundo noturno escuro, efeitos de vidro fosco - *Glassmorphism*, acentos em Verde Esmeralda Neon e Dourado).

---

## ✨ Identidade Visual e Experiência (UI/UX)

* **Efeito Parallax e Hero Dinâmico:** Fundo escuro imersivo (inspirado no visual noturno de Curitiba) com animações sutis de feixes de luz e rolagem em paralaxe.
* **Hologramas Flutuantes:** Cards satélites interativos (pins do Google Maps, notificações de WhatsApp e selos "5 Estrelas") em movimento contínuo (`translateY`).
* **Botões com Neon Glow:** Chamadas para ação (CTAs) em destaque com sombras e anéis pulsantes para elevar a taxa de conversão.
* **Scroll Reveal:** Transições suaves de elementos conforme a navegação do usuário.

---

## 📐 Estrutura e Regras de Negócio da Landing Page

### 1. Hero Section (Início)
* **Copy Principal:** *"Conectando clínicas de Curitiba ao topo do Google em 24h."*
* **Visual:** Layout dividido contendo mockups de celulares cercados por elementos flutuantes e botões de alta conversão.

### 2. O Diagnóstico ("Antes vs. Depois")
* Comparativo visual interativo entre o cenário estagnado ("Sem Site" em tom opaco/vermelho) versus a presença digital de autoridade ("Site Oficial" em verde neon pulsante).

### 3. Vitrine Interativa (Showroom Animado)
* Controlada via **Alpine.js** (`x-data`), permitindo alternar de forma fluida entre os nichos de **Harmonização Facial** (tons rosa/nude elegantes) e **Odontologia** (tons azul/branco limpos e tecnológicos).

### 4. Pilares da Solução (O que entregamos)
* Cards em *Glassmorphism* detalhando as entregas principais.
* **Destaque Crítico:** Inclusão do registro do **Domínio Oficial (.com.br)**, **Certificado SSL** e **6 meses de hospedagem ultrarrápida** totalmente inclusos.

### 5. Planos, Preços e Blindagem Técnica
* **Kit Autoridade (R$ 197 - Taxa única):** Foco exclusivo em Google Maps + Máquina de Avaliações.
* **Presença Completa (R$ 397 - Taxa única):** Condição comercial de 50% de entrada e 50% restantes na entrega em até 24h.
* **Blindagem Técnica (Manutenção):** Após o período de cortesia de 6 meses, aplica-se a taxa de **R$ 29,90/mês** para custódia de servidor, SSL, renovação do domínio e direito a 1 ajuste simples mensal.

### 6. FAQ Interativo
* Seção de perguntas frequentes estruturada em acordeon (via Alpine.js) respondendo às principais objeções sobre domínios, prazos, formas de pagamento e custos de manutenção.

---

## 🌐 Elementos Globais
* **Botão Flutuante do WhatsApp:** Posicionado no canto inferior direito com animação de pulso para contato direto com a equipe de vendas.
* *Configuração rápida:* `const WHATSAPP_NUMBER = "5541999999999";`

---

## 📂 Organização do Repositório
* `index.html` — Arquivo principal contendo toda a estrutura visual, scripts e regras da interface.
* `CLAUDE.md` — Especificações técnicas e diretrizes de desenvolvimento do agente.

---
*Desenvolvido por ServiceExpress.*