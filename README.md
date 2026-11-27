# Carlos Mudas de Seringueira

Landing page institucional para comercialização de mudas de seringueira de alta qualidade. Apresenta os clones disponíveis (RRIM, RIM e IAC), os benefícios, o processo de compra e a entrega especializada, centralizando a solicitação de orçamentos pelo WhatsApp.

## Funcionalidades

- Página única com seções de apresentação, benefícios, processo, chamada para ação, perguntas frequentes e rodapé.
- Navegação responsiva: menu desktop e menu lateral no mobile.
- Solicitação de orçamento por link direto para o WhatsApp.
- Perguntas frequentes em accordion.
- Rastreamento de conversões com Google Ads (gtag.js).
- Build estático (`out/`), pronto para hospedagem em servidor de arquivos estáticos.

## Tecnologias

- Next.js 16 (App Router) e React 19
- TypeScript
- Tailwind CSS 4 e tw-animate-css
- shadcn/ui e Radix UI
- lucide-react
- Fonte Montserrat via `next/font`

## Como executar

```bash
npm install
npm run dev
```

Acesse `http://localhost:3000`.

Para gerar a versão de produção estática em `out/`:

```bash
npm run build
```

Para verificar o código com ESLint:

```bash
npm run lint
```
