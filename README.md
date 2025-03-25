# 💰 VCA Investment - Vera Cruz Assets

<div align="center">
<img src="https://github.com/claudio-lins-dev/vca-invest/blob/main/assets/vca-v-neg.png?raw=true" width="350" />
</div>

<br/>

<div data-badges>
  <img src="https://img.shields.io/badge/next.js-%23000000.svg?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
  <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS" />
  <img src="https://img.shields.io/badge/clerk-%23000000.svg?style=for-the-badge&logo=clerk&logoColor=white" alt="Clerk" />
  <img src="https://img.shields.io/badge/Shadcn/ui-%23000000.svg?style=for-the-badge&logo=shadcnui&logoColor=white" alt="Shadcn/ui" />
</div>

<br/>
<br/>

Este projeto é uma aplicação web desenvolvida para o segmento de investimentos financeiros. O site foi construído utilizando tecnologias modernas de desenvolvimento front-end, com foco em oferecer uma experiência de usuário intuitiva e responsiva.

A aplicação apresenta uma arquitetura robusta baseada em Next.js, incorporando autenticação segura via Clerk e componentes de interface reutilizáveis com Shadcn/ui. O sistema permite que usuários visualizem informações sobre serviços financeiros, acessem um dashboard personalizado após autenticação e utilizem ferramentas como simuladores e calculadoras financeiras.

O projeto foi estruturado seguindo boas práticas de desenvolvimento, incluindo tipagem estática com TypeScript, gerenciamento de estado com React Query e validação de dados com Zod, resultando em um código mais seguro e de fácil manutenção.

## 🖥️ Como rodar este projeto 🖥️

### Requisitos:

- [Node.js](https://nodejs.org/pt) instalado
- [pnpm](https://pnpm.io/installation) instalado

### Execução:

1. Clone este repositório:

   ```sh
   git clone https://github.com/claudio-lins/vca-invest-web_clerk
   ```

2. Acesse o diretório do projeto:

   ```sh
   cd vca-invest-web_clerk
   ```

3. Instale as dependências:

   ```sh
   pnpm install
   ```

4. Configure as variáveis de ambiente:

   Será necessário criar um arquivo `.env` com as mesmas variáveis de ambiente listadas no arquivo `.env.example` na pasta raiz da aplicação e preencher esse arquivo com as variáveis de ambiente correspondentes.

5. Inicie o servidor (Next.js):

   ```sh
   pnpm dev
   ```

6. Acesse o projeto em [http://localhost:3000](http://localhost:3000).

## 🗒️ Features técnicas implementadas 🗒️

- Sistema de autenticação completo usando Clerk
- Dashboard interativo com métricas e visualizações de dados
- Formulários avançados com validação usando React Hook Form e Zod
- Layout responsivo implementado com Tailwind CSS
- Componentes de UI reutilizáveis baseados em Shadcn
- Rotas protegidas com middleware de autenticação
- Carrossel de conteúdo implementado com componentes personalizados
- Otimização de performance com React Query para gerenciamento de cache
- Interface adaptativa para diferentes dispositivos
- SEO otimizado para melhor indexação por motores de busca

## 💻 Tecnologias utilizadas 💻

- **Next.js**: Framework React com renderização híbrida (SSR/SSG)
- **TypeScript**: Tipagem estática para desenvolvimento mais seguro
- **React**: Biblioteca para construção de interfaces de usuário
- **Tailwind CSS**: Framework CSS utilitário para estilização rápida
- **Shadcn/ui**: Componentes reutilizáveis e acessíveis
- **Clerk**: Sistema de autenticação seguro e completo
- **React Hook Form**: Gerenciamento de formulários avançado
- **Zod**: Validação de esquemas TypeScript
- **Lucide React**: Ícones simples e consistentes
- **React Query**: Gerenciamento de estado e cache de dados

## 💎 Links úteis 💎

- [Next.js](https://nextjs.org/docs)
- [TypeScript](https://www.typescriptlang.org/docs)
- [Tailwind CSS](https://tailwindcss.com/docs)
- [Shadcn/ui](https://ui.shadcn.com)
- [Clerk](https://clerk.com/docs)
- [React Hook Form](https://react-hook-form.com/)
- [Zod](https://zod.dev/)
