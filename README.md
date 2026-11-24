# Olá, eu sou o Mike Araujo Costa 👋

Desenvolvo **apps e automações que tiram trabalho repetitivo das pessoas**. Hoje faço isso como estagiário de tecnologia no **Tayah Advogados** (Rio de Janeiro). Lá, transformei tarefas que tomavam horas da equipe em ferramentas que rodam sozinhas, sempre cuidando da segurança dos dados dos clientes (LGPD).

- 📱 Criei do zero um **app Android e web** para os clientes acompanharem os próprios processos.
- ⚙️ Faço **automações em Python e JavaScript** para o dia a dia de um escritório jurídico.
- 🔒 Trabalho com **segurança desde o começo**: regras de acesso no banco, verificação em duas etapas, nada de dado real em teste.
- 🤖 Uso **IA (Claude Code e Gemini)** como ferramenta de trabalho, com revisão e teste de cada entrega.

---

## ⭐ Projeto em destaque

### [Tayah Associado: app de acompanhamento de processos](https://github.com/mikecosta2704-code/tayah-associado-portfolio)

App Android e web para associados militares verem em que etapa está cada processo, com a explicação de cada andamento em linguagem simples, aviso no celular e documentos em PDF.

- Banco **Supabase/PostgreSQL** com **Row Level Security**: cada associado vê só os próprios dados, com teste automático que comprova isso.
- **Robô diário** que busca novidades nas APIs públicas do CNJ (DJEN e DataJud) e retém sentenças por 3 dias úteis, com calendário de feriados, para a equipe explicar antes.
- **Painel da equipe** com verificação em duas etapas, **notificações push** com Firebase e build assinado pronto para a Play Store.

`Capacitor` · `JavaScript` · `Supabase` · `PostgreSQL` · `Edge Functions (TypeScript)` · `Firebase` · `pg_cron`

**[Ver telas e detalhes →](https://github.com/mikecosta2704-code/tayah-associado-portfolio)**

---

## 🛠️ Outras ferramentas que criei no estágio

| Projeto | O que resolve | Como |
|---|---|---|
| **Compressor de PDF para o PJe** | O PJe recusa arquivos pesados, e a equipe perdia tempo comprimindo e dividindo PDFs na mão. | Programa `.exe` que roda sozinho em cada computador e vigia uma pasta: é só arrastar o PDF que ele comprime e, se precisar, fatia em partes de até 3 MB. Funciona offline e sem instalar nada. `Python` `PyInstaller` |
| **Portal interno + gerador de documentos** | Procurações e declarações eram preenchidas à mão, com risco de erro em nome e CPF. | Página que gera o Word pronto a partir de um formulário, com validação de CPF, data por extenso e concordância de gênero (portador/portadora). Roda no navegador, sem servidor. `JavaScript` `docxtemplater` |
| **Planilha de contatos completada com IA** | Uma planilha com mais de mil clientes tinha centenas de cadastros incompletos. | Script que lê os documentos de cada cliente com o **Gemini**, preenche só as células vazias, confere se o documento é da pessoa certa e gera um relatório em PDF do que foi feito. Roda sozinho duas vezes por dia. `Python` `Gemini API` `SharePoint` |

Também estudei integrações com o Astrea, a Suri (chatbot de WhatsApp) e o Slack para avisos automáticos de prazos e atendimento.

> O código dessas ferramentas é do escritório e fica privado. Aqui descrevo o que fiz e como. Nenhum dado de cliente é publicado.

---

## 🧰 Ferramentas que uso

**Linguagens:** Python · JavaScript · TypeScript · SQL · HTML/CSS
**Back-end e dados:** Supabase · PostgreSQL · Row Level Security · Edge Functions · pg_cron
**Mobile:** Capacitor · Android · Firebase Cloud Messaging
**Automação e IA:** Gemini API · Claude Code · PyInstaller · Agendador do Windows · Make/n8n
**Boas práticas:** Git · testes automáticos · LGPD e privacidade desde o projeto

---

## 💡 Como eu trabalho

1. **Entendo o problema de quem usa**, não só o pedido.
2. **Entrego em etapas pequenas**, cada uma com teste e um critério claro de "pronto".
3. **Escrevo o porquê de cada decisão** para quem vier depois.
4. **Segurança não é opcional:** se o teste de segurança não pode falhar, ele não prova nada.
