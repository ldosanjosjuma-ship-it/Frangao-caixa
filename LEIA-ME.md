# 🍗 O Frangão — Gestão de Caixa (App PWA)

## O que é isto?

Uma aplicação web instalável (PWA) para registo diário de caixa do
Restaurante & Bar O Frangão. Depois de instalada, funciona como uma
app normal no telemóvel — com ícone no ecrã inicial — e continua a
funcionar mesmo sem internet.

## Como publicar online (necessário para instalar no telemóvel)

Uma PWA precisa de estar acessível por HTTPS para poder ser instalada.
Tens estas opções gratuitas — escolhe uma:

### Opção A — Netlify Drop (mais simples, 2 minutos)
1. Vai a https://app.netlify.com/drop
2. Arrasta a pasta `frangao-app` completa (com os 5 ficheiros) para a página
3. Vais receber um link (ex: `https://nome-aleatorio.netlify.app`)
4. Abre esse link no telemóvel

### Opção B — GitHub Pages (gratuito, permanente)
1. Cria uma conta em https://github.com (se não tiveres)
2. Cria um novo repositório e faz upload destes ficheiros
3. Vai a Settings → Pages → activa o GitHub Pages
4. Recebes um link tipo `https://teunome.github.io/frangao`

### Opção C — Vercel
1. Vai a https://vercel.com
2. Importa a pasta como novo projecto
3. Deploy automático, recebes um link `.vercel.app`

## Como instalar no telemóvel (depois de ter o link)

**Android (Chrome):**
1. Abre o link no Chrome
2. Toca no menu (⋮) → "Adicionar ao ecrã principal" ou "Instalar app"
3. Confirma — o ícone 🍗 aparece no ecrã inicial

**iPhone (Safari):**
1. Abre o link no Safari
2. Toca no botão de partilhar (□↑)
3. Escolhe "Adicionar à Tela de Início"

## Funcionalidades

- 🏠 **Dashboard** — indicadores e gráficos anuais/mensais
- 📋 **Registo Diário** — POS, Numerário, Saídas por categoria com notas
- 📅 **Vista Mensal** — resumo, gráfico diário, exportação Excel (.csv)
- 📊 **Vista Anual** — resumo anual, distribuição de despesas, exportação Excel
- 💾 Os dados ficam guardados **no próprio telemóvel** (localStorage) —
  funciona 100% offline depois da primeira visita
- 📥 Exportação para Excel (.csv) por mês ou por ano

## Importante sobre os dados

Os registos ficam guardados **localmente no navegador/dispositivo**.
Isto significa:
- Se desinstalares a app ou limpares os dados do navegador, os registos perdem-se
- Os dados **não são partilhados automaticamente** entre telemóveis diferentes
- Recomenda-se exportar regularmente para Excel como cópia de segurança

Se precisares de sincronização entre vários dispositivos (ex: dono +
gerente), terás de adicionar uma base de dados na nuvem — posso ajudar
nesse passo seguinte se for necessário.
