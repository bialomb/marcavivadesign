# Contexto do Projeto: marcaVIVAdesign

## Visão Geral
Projeto greenfield de webapp fullstack utilizando tecnologias modernas.
O objetivo é criar uma plataforma para marcaVIVAdesign.

## Stack Tecnológica
- **Frontend Framework**: Next.js (App Router)
- **Linguagem**: TypeScript
- **Estilização**: Tailwind CSS
- **Backend/Infra**: Supabase (Auth, DB, Storage)
- **Gerenciamento de Estado**: React Hooks / Server Actions

## Estrutura de Diretórios Importantes
- `src/app`: Páginas e rotas do Next.js (App Router)
- `src/components`: Componentes React reutilizáveis
- `src/utils/supabase`: Configuração do cliente Supabase (client, server, middleware)
- `src/middleware.ts`: Middleware de autenticação e sessão

## Convenções
- Usar `camelCase` para funções e variáveis.
- Usar `PascalCase` para componentes React.
- Usar `kebab-case` para nomes de arquivos de componentes (ex: `my-component.tsx`) ou o padrão Next.js (ex: `page.tsx`, `layout.tsx`).
- Preferir Server Components por padrão; usar `'use client'` apenas quando necessário (hooks, interatividade).
- Estilização via classes utilitárias do Tailwind.

## Comandos Úteis
- `npm run dev`: Iniciar servidor de desenvolvimento (http://localhost:3000)
- `npm run build`: Build de produção
- `npm run start`: Iniciar servidor de produção
- `npm run lint`: Verificar linting
