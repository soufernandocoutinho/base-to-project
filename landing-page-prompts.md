# 📑 Documentação de Prompts para Criação de Landing Pages com Bootstrap, SEO, AEO e Rastreamento

Este documento reúne todos os prompts criados para auxiliar na geração de landing pages otimizadas para SEO, AEO e integração com ferramentas de rastreamento (Google Analytics, Ads, Facebook Pixel, Search Console).

---

## 🔹 01. Prompt para SEO + Canonical
Crie meta tags de SEO para uma landing page em Bootstrap.
Dados:
- Nome: [NOME DO CLIENTE]
- Serviço/Produto: [SERVIÇO OU PRODUTO]
- Localização: [CIDADE/ESTADO]
- Público-alvo: [DESCREVER]
- URL principal: [URL CANONICAL]

Inclua:
- <title>
- <meta name="description">
- <meta name="keywords">
- <link rel="canonical">

---

## 🔹 02. Prompt para Header com Bootstrap
Crie um header em Bootstrap para a landing page.
Dados:
- Nome do cliente: [NOME]
- Serviço/Produto: [SERVIÇO OU PRODUTO]
- Chamada principal (CTA): [TEXTO]

Inclua:
- Navbar responsiva com logo e links
- Hero section com título, subtítulo e botão CTA

---

## 🔹 03. Prompt para Conteúdo Otimizado (AEO)
Crie uma seção de conteúdo em Bootstrap para a landing page.
Dados:
- Serviço/Produto: [SERVIÇO OU PRODUTO]

Inclua:
- Resposta curta em destaque (ex: <div class="alert alert-info">)
- Detalhamento em parágrafos
- Lista de benefícios em <ul class="list-group">

---

## 🔹 04. Prompt para FAQ (Schema + HTML com Bootstrap)
Crie uma seção FAQ em Bootstrap para a landing page.
Dados:
- Perguntas e respostas fornecidas: [LISTA DE FAQ]

Inclua:
- Accordion do Bootstrap para perguntas e respostas
- Script JSON-LD com schema.org/FAQPage

---

## 🔹 05. Prompt para Dados Estruturados (Schema LocalBusiness ou Product)
Crie dados estruturados em JSON-LD para a landing page.
Dados:
- Nome: [NOME DO CLIENTE]
- Endereço: [ENDEREÇO COMPLETO]
- Telefone: [TELEFONE]
- Redes sociais: [LISTA DE LINKS]

Inclua:
- Schema LocalBusiness ou Product
- Campo "sameAs" com links de redes sociais

---

## 🔹 06. Prompt para Open Graph e Twitter Cards
Crie meta tags Open Graph e Twitter Cards para a landing page.
Dados:
- Título: [TÍTULO]
- Descrição: [DESCRIÇÃO]
- Imagem: [URL DA IMAGEM]
- URL da página: [URL]

Inclua:
- og:title, og:description, og:image, og:url
- twitter:card, twitter:title, twitter:description, twitter:image

---

## 🔹 07. Prompt para Footer com Bootstrap
Crie um footer em Bootstrap para a landing page.
Dados:
- Telefone: [TELEFONE]
- Endereço: [ENDEREÇO]
- Redes sociais: [LISTA DE LINKS]

Inclua:
- <footer> com grid responsivo
- Links clicáveis para redes sociais com ícones (Bootstrap Icons)

---

## 🔹 08. Prompt para Scripts de Rastreamento
Inclua na landing page em Bootstrap os seguintes scripts:
- Facebook Pixel (código fornecido pelo cliente)
- Google Ads Tag (código fornecido pelo cliente)
- Google Analytics GA4 (código fornecido pelo cliente)

Os scripts devem ser posicionados corretamente:
- GA4 e Ads no <head>
- Pixel do Facebook antes do fechamento do <body>

---

## 🔹 09. Prompt para Verificação no Google Search Console
Inclua na landing page em Bootstrap a meta tag de verificação do Google Search Console.
Dados:
- Código de verificação: [CÓDIGO]

Posicione dentro do <head>.

---

## 🔹 10. Prompt para robots.txt
Crie um arquivo robots.txt para o site.
Dados:
- Páginas que devem ser bloqueadas: [LISTA]
- Páginas que devem ser permitidas: [LISTA]

Inclua instruções para User-agent: *.

---

## 🚀 Fluxo de Uso
01. **SEO + Canonical** → sempre incluir.
02. **Header + Hero** → para identidade visual e CTA.
03. **Conteúdo otimizado (AEO)** → para IA e buscadores.
04. **FAQ + Schema** → para aparecer em snippets e respostas diretas.
05. **Dados estruturados (LocalBusiness/Product)** → para credibilidade e indexação.
06. **Open Graph + Twitter Cards** → para redes sociais.
07. **Footer** → contatos e redes sociais.
08. **Scripts de rastreamento** → quando cliente usa Ads/Pixel/Analytics.
09. **Search Console** → apenas na verificação inicial.
10. **robots.txt** → se cliente quiser controlar indexação.

---

# ✅ Checklist Rápido

- [ ] Inserir **meta tags SEO + canonical**
- [ ] Criar **navbar + hero responsivo** em Bootstrap
- [ ] Adicionar **conteúdo otimizado (resposta curta + detalhamento)**
- [ ] Incluir **lista de serviços/benefícios**
- [ ] Criar **FAQ com accordion + Schema FAQ**
- [ ] Adicionar **Schema LocalBusiness/Product**
- [ ] Inserir **Open Graph + Twitter Cards**
- [ ] Criar **footer com contatos e redes sociais**
- [ ] Incluir **scripts de rastreamento (GA4, Ads, Pixel)**
- [ ] Adicionar **meta de verificação Search Console**
- [ ] Configurar **robots.txt** conforme necessidade

---

📌 **Observação:** Este documento serve como guia modular. Você pode executar cada prompt separadamente na IA, juntar os blocos e montar a landing page final em Bootstrap conforme a necessidade do cliente.
