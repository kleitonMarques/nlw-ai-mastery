# nlw-ai-mastery
Aplicativo que permite fazer upload de vídeos e, por meio de IA, criar automaticamente títulos e descrições atraentes e com boa indexação.

### Versão do node
- v18.17.1

### Gerenciador de pacotes
- PNPM
- Instalar utilizando o NPM "npm install -g pnpm"

## 1) React Front-end
- Instalar dependencia com "pnpm i"
- Rodando o projeto "pnpm run dev"
- Projeto criado utilizando Vite
- Utilizando Tailwindcss
- Utilizando Radix UI
- Utilizando "shadcn-ui", utilizar "pnpm dlx shadcn-ui@latest add ${slider}" para criar um novo componente do shadcn-ui

## 2) Node Back-end
- Instalar dependencia com "pnpm i"
- Rodando o projeto "pnpm run dev"
- ORM Prisma
- Necessário ter extensão "Prisma" instalada no VCCode
- No VSCode - "Ctrl + Shift + p" =><br/>
	abrir settings (json) =><br/>
	adicionar o propriedade do "prisma" abaixo, dentro do objeto principal<br/>
	(o mesmo objeto onde esta a escolha do tema do VSCode)<br/>
	"[prisma]": { "editor.defaultFormatter": "Prisma.prisma", "editor.formatOnSave": true },
- Banco SQLite
- Para criar as tabelas no banco, rodar a migrate "pnpm prisma migrate dev"
- Para visualizar o Prisma Studio "pnpm prisma studio"
