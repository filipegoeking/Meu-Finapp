# Finanças Pessoais — V1

Aplicação web React + Vite para o núcleo do produto de finanças pessoais.

## Rodar
```bash
npm install
npm run dev
```

## Módulos
Dashboard, Lançamentos, Contas, Cartões, Parcelas, Orçamento, Metas, Projeção, Simulador, Analista Financeiro e **Configurações**.

## Nova camada de Configurações
A V1 inclui:
- parâmetros do usuário editáveis pela interface;
- ajuda contextual `?` em cada parâmetro;
- estrutura P1–P5 configurável conceitualmente;
- seção de documentação e governança;
- manual em `docs/MANUAL_OPERACIONAL.md`.

## Próxima etapa
Persistência real, autenticação, API, regras server-side, auditoria, Open Finance e IA.


## PWA / iPhone
A V1.0.3 foi preparada como Progressive Web App (PWA). Depois de publicada em uma URL HTTPS (por exemplo, Vercel), abra no Safari do iPhone e use **Compartilhar → Adicionar à Tela de Início**. O app abre em modo standalone e usa o ícone do Meu Finapp.

### Build
```bash
npm install
npm run build
```
