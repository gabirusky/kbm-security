# KBM Security - Red Team & Pentest Services

![KBM Security](https://img.shields.io/badge/Security-Red%20Team-red?style=for-the-badge)
![React](https://img.shields.io/badge/React-18.3-61DAFB?style=for-the-badge&logo=react)
![Vite](https://img.shields.io/badge/Vite-5.2-646CFF?style=for-the-badge&logo=vite)
![TailwindCSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC?style=for-the-badge&logo=tailwind-css)

Uma landing page moderna e profissional para serviços de segurança cibernética, especializada em Red Team, Pentest e Análise de Vulnerabilidades.

## 🎯 Características

- **Design Cyberpunk Premium**: Interface dark com efeitos glitch, animações suaves e estética futurista
- **Totalmente Responsivo**: Otimizado para desktop, tablet e mobile
- **Performance Otimizada**: Construído com React + Vite para carregamento rápido
- **SEO Otimizado**: Meta tags completas para melhor indexação
- **Acessibilidade**: Implementação de ARIA labels e navegação por teclado
- **Formulário de Contato**: Integração com mailto para facilitar o contato

## 🛠️ Tecnologias Utilizadas

- **React 18.3** - Biblioteca JavaScript para interfaces
- **Vite 5.2** - Build tool moderna e rápida
- **Tailwind CSS 3.4** - Framework CSS utility-first
- **Lucide React** - Ícones modernos e customizáveis
- **Google Fonts** - Tipografia premium (Space Grotesk & JetBrains Mono)

## 📦 Instalação

### Pré-requisitos

- Node.js 18+ instalado
- npm ou yarn

### Passos

1. **Clone o repositório ou navegue até a pasta do projeto:**

```bash
cd d:\Code\kbm\kbm-security
```

2. **Instale as dependências:**

```bash
npm install
```

3. **Inicie o servidor de desenvolvimento:**

```bash
npm run dev
```

4. **Abra no navegador:**

O aplicativo estará rodando em `http://localhost:3000`

## 🚀 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Cria a build de produção
- `npm run preview` - Visualiza a build de produção localmente
- `npm run lint` - Executa o linter para verificar código

## 📁 Estrutura do Projeto

```
kbm-security/
├── public/
│   └── shield-icon.svg          # Favicon
├── src/
│   ├── components/
│   │   ├── Navigation.jsx       # Barra de navegação
│   │   ├── Hero.jsx            # Seção hero com efeito glitch
│   │   ├── Standards.jsx       # Padrões de segurança
│   │   ├── TerminalAbout.jsx   # Sobre com terminal simulado
│   │   ├── ProblemSection.jsx  # Seção de problemas/soluções
│   │   ├── Services.jsx        # Cards de serviços
│   │   ├── Contact.jsx         # Formulário de contato
│   │   └── Footer.jsx          # Rodapé
│   ├── App.jsx                 # Componente principal
│   ├── main.jsx                # Entry point
│   └── index.css               # Estilos globais + Tailwind
├── index.html                   # HTML principal
├── package.json                 # Dependências
├── vite.config.js              # Configuração Vite
├── tailwind.config.js          # Configuração Tailwind
└── postcss.config.js           # Configuração PostCSS
```

## 🎨 Seções da Landing Page

1. **Hero** - Apresentação principal com efeito glitch e typewriter
2. **Standards** - Metodologias e padrões de segurança (OWASP, NIST, MITRE ATT&CK)
3. **About** - Informações sobre a empresa com terminal simulado
4. **Problem** - Destaque dos problemas de segurança e soluções
5. **Services** - Cards interativos com os serviços oferecidos
6. **Contact** - Formulário funcional de contato
7. **Footer** - Informações de copyright e links

## 🎭 Efeitos Visuais

- **Glitch Effect**: Animação de glitch no título principal
- **Cyber Grid**: Background com grade cyberpunk
- **Scanline**: Efeito de linha de varredura
- **Hover Effects**: Transições suaves em cards e botões
- **Typewriter**: Efeito de digitação no hero
- **Smooth Scroll**: Navegação suave entre seções

## 🌐 Deploy

### Vercel (Recomendado)

1. Instale a CLI do Vercel:
```bash
npm i -g vercel
```

2. Execute o deploy:
```bash
vercel
```

### Netlify

1. Crie uma conta em [Netlify](https://netlify.com)
2. Conecte seu repositório Git
3. Configure:
   - Build command: `npm run build`
   - Publish directory: `dist`

### Build Manual

```bash
npm run build
```

Os arquivos estarão em `dist/` prontos para deploy em qualquer servidor estático.

## 📧 Contato

Para dúvidas ou sugestões sobre o projeto:

- Email: kbmsecurity@gmail.com

## 📄 Licença

© 2025 KBM Security. Todos os direitos reservados.

---

**Desenvolvido com ❤️ e ☕ para proteger sua infraestrutura**
