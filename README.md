# Olá, eu sou o Wagner 👋

**Desenvolvedor Full Stack** em São José do Rio Preto, SP. Construo sistemas web, automações e integrações de IA que resolvem problemas reais de operação.

- 💼 Desenvolvedor Full Stack na **Zurich Administradora de Crédito e Cobrança**. Comecei no suporte de TI, automatizei as tarefas repetitivas do setor e migrei para o desenvolvimento. Hoje respondo por boa parte do ecossistema de software da empresa: autoatendimento, CRMs internos, dashboards e integrações de dados em alto volume.
- 🤖 Estudo e construo **IA aplicada**: agentes autônomos e servidores **MCP (Model Context Protocol)** conectando LLMs a sistemas de verdade.
- 🌐 Em paralelo, desenvolvo sites e sistemas para pequenos negócios na **[WGL Software](https://wglsoftware.com)**.

## 🛠️ Stack

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

## 🚀 Sistemas em destaque

### [Pactua · CRM de cobrança](https://github.com/wagnerglongo/crm-cobranca)

<a href="https://github.com/wagnerglongo/crm-cobranca"><img src="https://raw.githubusercontent.com/wagnerglongo/crm-cobranca/main/docs/img/financeiro.webp" alt="Ficha do contrato no Pactua, com acordo e parcelas" width="100%"></a>

CRM de call center que escrevi e mantenho em produção numa operação real de cobrança, publicado aqui com o credor trocado por um fictício e um simulador da API dele. Cargas diárias do credor com staging e validação linha a linha, filas de operadores, acordos e boletos fechados pela API do credor, API REST própria com OpenAPI, Bearer token e `Idempotency-Key`, CDC com Debezium para busca no OpenSearch e analítico no ClickHouse. **511 testes** rodando no GitHub Actions.

`PHP 8` `MySQL` `Redis` `Debezium` `Redpanda` `OpenSearch` `ClickHouse` `Docker Compose` `PHPUnit`

### [Cardápio digital com pedido no WhatsApp](https://github.com/wagnerglongo/cardapio-digital)

<a href="https://github.com/wagnerglongo/cardapio-digital"><img src="https://raw.githubusercontent.com/wagnerglongo/cardapio-digital/main/docs/cardapio-celular.png" alt="Cardápio no celular, com carrinho e pedido" width="100%"></a>

O cliente monta o pedido no celular e envia pronto no WhatsApp da loja; o dono cuida de produtos, fotos e horários num painel com login. Dinheiro em centavos inteiros, CSRF, rate limit no login, CSP sem scripts inline e uploads regravados em WebP. Testes em PHPUnit e `node --test`, imagem Docker e CI.

`PHP 8` `SQLite/MySQL` `JavaScript` `Docker` `GitHub Actions`

### [Gestão de confeitaria](https://github.com/wagnerglongo/gestao-confeitaria)

<a href="https://github.com/wagnerglongo/gestao-confeitaria"><img src="https://raw.githubusercontent.com/wagnerglongo/gestao-confeitaria/main/docs/painel.png" alt="Painel com faturamento, lucro e estoque baixo" width="100%"></a>

Ficha técnica com custo real por receita (inclusive receitas dentro de receitas, com detecção de ciclo), baixa de estoque na produção, vendas, despesas e fluxo de caixa com lucro por produto. Regras de negócio isoladas em classes de domínio, todas cobertas por testes.

`PHP 8` `SQLite/MySQL` `PHPUnit` `Docker` `GitHub Actions`

## 🧩 Front-end e ferramentas

| Projeto | O que é | No ar |
|---|---|---|
| [**Site da Chácara**](https://github.com/wagnerglongo/site-chacara) | Site de chácara para eventos, com galeria e pedido de reserva montado direto no WhatsApp. | [site-chacara-tau.vercel.app](https://site-chacara-tau.vercel.app) |
| [**Institutional Web**](https://github.com/wagnerglongo/Institutional_web_example) | Gerador de sites institucionais: os dados da empresa num JSON viram um site pronto, com SEO e as cores da marca. | [Exemplo](https://institutional-web-example.vercel.app) |
| [**Dev Notes**](https://github.com/wagnerglongo/Dev-notes) | Bloco de notas em Markdown para desenvolvedores, offline e instalável (PWA), com notas salvas no IndexedDB. | |
| [**Gerador de Box Shadow**](https://github.com/wagnerglongo/Box-shadow) | Cria sombras CSS com pré-visualização em tempo real. | [box-shadow.vercel.app](https://box-shadow.vercel.app) |
| [**Gerador de QR Code**](https://github.com/wagnerglongo/gerador-de-QRCode) | Gera QR Codes a partir de qualquer texto ou URL. | [Demo](https://gerador-de-qr-code-one.vercel.app) |

## 📫 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wagner-gon%C3%A7alves-longo-filho-a29419252/)
[![WGL Software](https://img.shields.io/badge/WGL%20Software-site-1b74c9?style=flat-square)](https://wglsoftware.com)
[![Modelos de site](https://img.shields.io/badge/Modelos%20de%20site-galeria-f35a2c?style=flat-square)](https://modelos.wglsoftware.com)
