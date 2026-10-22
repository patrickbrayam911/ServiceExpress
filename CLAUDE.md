CLAUDE.md — Especificação da Landing Page ServiceExpress (Edição Imersiva/Tech)

1. Visão Geral e Tech Stack

Você é um Engenheiro Front-End Sênior e Especialista em UI/UX Animada.
Sua missão é criar do zero a Landing Page de Alta Conversão (index.html) para o projeto ServiceExpress. A solução vende uma Estrutura Digital Express (Landing Page + Google Maps + Máquina de Avaliações) para clínicas de Harmonização Facial e Odontologia.

Formato: Arquivo único index.html.

Stack: HTML5 + Tailwind CSS (via script CDN) + Alpine.js (para interatividade).

Estética: "Tech Dark / Cyber-Premium". Fundo noturno, elementos de vidro fosco, luzes neon verdes e douradas, e animações imersivas.

2. Identidade Visual e Animações Obrigatórias

A página não deve ser estática. Ela deve parecer um dashboard premium de tecnologia focado em conversão. Adicione uma tag <style> no <head> para definir @keyframes personalizados que o Tailwind não cobre nativamente.

Paleta de Cores Base: Fundo Escuro (bg-slate-900 a bg-[#0B0F17]), Acentos em Verde Esmeralda Neon (#10B981) para sucesso/maps, e Dourado (#D4AF37) para elementos premium.

Efeito Parallax e Hero Section: O Hero principal deve ter um background escurecido (remetendo a Curitiba à noite), com um efeito de scroll em parallax. Adicione "feixes de luz" sutis em movimento no fundo (usando gradientes e animações de translação).

Glassmorphism (Vidro Fosco): Todos os cards (Pilares, Preços) e especialmente os elementos flutuantes do Hero devem usar bg-white/10 backdrop-blur-md border border-white/20.

Elementos Flutuantes (Hologramas): No Hero e na Vitrine, crie pequenos cards satélites (ex: um pin do Google Maps, uma notificação de WhatsApp, um selo "5 Estrelas") que flutuam continuamente (animação transform: translateY subindo e descendo).

Botões com Neon Glow: O CTA principal ("Ativar Minha Estrutura") deve ser Verde Esmeralda com uma sombra brilhante pulsante (box-shadow dinâmico ou ring animado do Tailwind).

Scroll Reveal (Fade-up): As seções da página devem aparecer suavemente de baixo para cima conforme o usuário faz o scroll.

3. Estrutura de Seções e Conteúdo (Regras de Negócio)

Seção 1: Hero Section Animado

Copy: "Conectando clínicas de Curitiba ao topo do Google em 24h."

Visual: Textos à esquerda. À direita, um mockup de celular cercado por cards flutuantes em Glassmorphism (Selo Google, Notificação WhatsApp, Avaliações). Fundo noturno com luzes neon.

CTAs: Botão brilhante primário + Botão secundário "Ver Prévia Animada".

Seção 2: O Diagnóstico "Antes vs. Depois"

Dois cards lado a lado.

Antes: Vermelho, opaco, "Sem Site".

Depois: Verde neon, brilhante, destacando o botão "Site Oficial" com ícone de clique.

Seção 3: A Vitrine Interativa (Showroom Animado)

Obrigatório: Controle via Alpine.js (x-data="{ tab: 'estetica' }") para alternar entre "Harmonização Facial" e "Odontologia".

Animação de Troca: A transição entre as abas não pode ser seca. Use x-transition do Alpine para um efeito de slide/fade iluminado.

Conteúdo dos Mockups: As prévias devem parecer sites reais de alto padrão (Rosa/Nude elegante para Harmonização; Azul/Branco clean e tecnológico para Odonto).

Seção 4: Pilares da Solução (O que entregamos)

Cards em Glassmorphism.

Destaque Crítico no Pilar 1: Deixar explícito que inclui o registro do Domínio Oficial (.com.br), Certificado de Segurança SSL e 6 meses de hospedagem ultrarrápida gratuitos.

Seção 5: Preços e Blindagem (Fim da Hospedagem Vitalícia)

Plano 1 (Kit Autoridade): R$ 197 (taxa única). Foco apenas em Maps + Máquina de Avaliações.

Plano 2 (Presença Completa): R$ 397 (taxa única). Condição: 50% de entrada, 50% na entrega em 24h.

Regra de Manutenção (Essencial): Inserir um box claro (Blindagem Técnica) informando que após os 6 meses gratuitos, há uma taxa técnica de R$ 29,90/mês para manter servidor, SSL e a renovação anual do domínio. Dá direito a 1 ajuste simples/mês.

Seção 6: Passos e FAQ Accordion

3 Passos: Briefing > Personalização em 24h > Aprovação.

FAQ Interativo (Alpine.js):

O domínio .com.br já está incluso? (Sim)

O que cobre os R$ 29,90/mês? (Servidor, SSL, Domínio, 1 ajuste simples).

Posso usar domínio próprio ou compra definitiva? (Sim, basta chamar no Whats).

Quando eu pago? (50% antes, 50% depois).

Elementos Globais

Botão Flutuante do WhatsApp: Canto inferior direito, ícone verde com efeito "pulse", linkando direto para o WhatsApp de vendas da ServiceExpress.

Configurar no script inicial: const WHATSAPP_NUMBER = "5541999999999";.