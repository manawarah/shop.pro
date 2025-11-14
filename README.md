📘 Projeto — Aplicação Next.js

Este repositório contém uma aplicação desenvolvida com Next.js, utilizando TypeScript, TailwindCSS, ShadCN/UI e outras ferramentas modernas de desenvolvimento frontend.

🚀 Tecnologias Utilizadas:
Next.js (App Router)
React
TypeScript
TailwindCSS
ShadCN/UI
PNPM como gerenciador de pacotes
PostCSS
ESLint

📂 Estrutura do Projeto
A estrutura principal do projeto é organizada da seguinte forma:

/
├── app/               # Rotas e páginas principais do Next.js
├── components/        # Componentes reutilizáveis
├── hooks/             # Hooks customizados
├── lib/               # Funções utilitárias e configurações
├── public/            # Arquivos estáticos
├── styles/            # Estilos globais
├── package.json       # Dependências e scripts
├── next.config.mjs    # Configurações do Next.js
└── tsconfig.json      # Configuração do TypeScript

▶️ Como Rodar o Projeto:

1. Instale o PNPM (se ainda não tiver)

PNPM é o gerenciador de pacotes recomendado para este projeto.
npm install -g pnpm

2. Instale as dependências

Abra o terminal na pasta do projeto e execute:
pnpm install

3. Rodar o servidor de desenvolvimento
pnpm dev

O projeto estará disponível em:
👉 http://localhost:3000

🧪 Scripts Disponíveis

No package.json, você encontra:

| Script       | Função                               |
| ------------ | ------------------------------------ |
| `pnpm dev`   | Inicia o servidor de desenvolvimento |
| `pnpm build` | Gera o build otimizado para produção |
| `pnpm start` | Inicia a aplicação em produção       |
| `pnpm lint`  | Analisa o código com ESLint          |

🎨 Estilização

O projeto usa:

TailwindCSS para layout e estilos utilitários
ShadCN/UI para componentes visuais de alto nível
configuração modular para fácil expansão




