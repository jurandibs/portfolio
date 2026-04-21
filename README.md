<h1 align="center">
  <br>
  <img src="assets/img/favicon.png" alt="Logo" width="80">
  <br>
  Jurandi Barreto Silva — Portfolio
  <br>
</h1>

<p align="center">
  <strong>Diretor Operacional · Full Stack Developer · Business Intelligence</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jurandi-barreto-silva-4625b720/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/jurandibs">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://politicoconnect.app">
    <img src="https://img.shields.io/badge/Político_Connect-149ddd?style=for-the-badge&logo=rocket&logoColor=white" alt="Político Connect">
  </a>
  <a href="https://trilhaflow.app">
    <img src="https://img.shields.io/badge/TrilhaFlow-0972a3?style=for-the-badge&logo=rocket&logoColor=white" alt="TrilhaFlow">
  </a>
</p>

---

## 📋 Sobre o Projeto

Portfólio profissional e interativo que apresenta minha trajetória de mais de **15 anos** em Tecnologia da Informação, abrangendo desde a gestão operacional e implantação de ERPs até o desenvolvimento de aplicações SaaS modernas com Inteligência Artificial.

### ✨ Principais Features

- 🌐 **Bilíngue (PT-BR / EN-US)** — Toggle de idiomas em tempo real, sem recarregamento de página
- 📧 **Formulário de Contato Funcional** — Integrado com EmailJS para envio direto de mensagens
- 🗺️ **Mapa Interativo** — Google Maps embarcado apontando para Aracaju/SE
- 🎨 **Design Premium** — Interface moderna com cards elevados, gradientes e micro-animações
- 📱 **Totalmente Responsivo** — Adaptado para desktop, tablet e mobile
- ⚡ **Performance** — Carregamento otimizado com lazy loading e animações AOS

---

## 🛠️ Stack Tecnológica

<table>
  <tr>
    <td align="center"><strong>Categoria</strong></td>
    <td align="center"><strong>Tecnologias</strong></td>
  </tr>
  <tr>
    <td><strong>Front-End</strong></td>
    <td>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white">
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white">
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
    </td>
  </tr>
  <tr>
    <td><strong>Framework CSS</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Bootstrap_5.3-7952B3?style=flat-square&logo=bootstrap&logoColor=white">
    </td>
  </tr>
  <tr>
    <td><strong>Bibliotecas JS</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Typed.js-333?style=flat-square&logo=javascript&logoColor=white">
      <img src="https://img.shields.io/badge/AOS-4CAF50?style=flat-square&logo=css3&logoColor=white">
      <img src="https://img.shields.io/badge/GLightbox-FF6B6B?style=flat-square&logo=image&logoColor=white">
      <img src="https://img.shields.io/badge/Isotope-0D47A1?style=flat-square&logo=grid&logoColor=white">
      <img src="https://img.shields.io/badge/Swiper-6332F6?style=flat-square&logo=swiper&logoColor=white">
      <img src="https://img.shields.io/badge/PureCounter-149ddd?style=flat-square&logo=counter&logoColor=white">
    </td>
  </tr>
  <tr>
    <td><strong>Serviços</strong></td>
    <td>
      <img src="https://img.shields.io/badge/EmailJS-FC5C65?style=flat-square&logo=gmail&logoColor=white">
      <img src="https://img.shields.io/badge/Google_Maps-4285F4?style=flat-square&logo=googlemaps&logoColor=white">
      <img src="https://img.shields.io/badge/Google_Fonts-4285F4?style=flat-square&logo=googlefonts&logoColor=white">
    </td>
  </tr>
  <tr>
    <td><strong>Template Base</strong></td>
    <td>
      <a href="https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/">iPortfolio by BootstrapMade</a>
    </td>
  </tr>
</table>

---

## 📂 Estrutura do Projeto

```
portfolio/
├── assets/
│   ├── css/
│   │   └── main.css          # Estilos principais + overrides customizados
│   ├── img/                   # Imagens do portfólio
│   ├── js/
│   │   ├── env.js             # 🔒 Variáveis de ambiente (não versionado)
│   │   ├── i18n.js            # Sistema de internacionalização (PT-BR / EN-US)
│   │   └── main.js            # Inicialização de plugins e interações
│   └── vendor/                # Bibliotecas de terceiros (Bootstrap, AOS, etc.)
├── .gitignore                 # Proteção de arquivos sensíveis
├── index.html                 # Página principal do portfólio
└── README.md                  # Este arquivo
```

---

## 🚀 Deploy

### Pré-requisitos

O projeto é **100% estático** (HTML/CSS/JS puro), não requer Node.js nem build tools.

### Rodando Localmente

```bash
# Clone o repositório
git clone https://github.com/jurandibs/portfolio.git
cd portfolio

# Crie o arquivo de configuração do EmailJS
# (necessário para o formulário de contato funcionar)
cat > assets/js/env.js << 'EOF'
const ENV = {
  EMAILJS_PUBLIC_KEY: "SUA_PUBLIC_KEY",
  EMAILJS_SERVICE_ID: "SEU_SERVICE_ID",
  EMAILJS_TEMPLATE_ID: "SEU_TEMPLATE_ID"
};
EOF

# Inicie um servidor local
python -m http.server 8000
# ou
npx serve .
```

Acesse **http://localhost:8000** no navegador.

### Deploy em Produção

| Plataforma | Comando / Instrução |
|---|---|
| **GitHub Pages** | Settings → Pages → Source: `main` / `root` |
| **Vercel** | `npx vercel --prod` |
| **Netlify** | Arraste a pasta para o dashboard |

> ⚠️ **Importante:** Em qualquer plataforma, o arquivo `assets/js/env.js` precisa existir no servidor para o formulário funcionar. Como ele está no `.gitignore`, você precisará criá-lo manualmente no ambiente de deploy ou utilizar variáveis de ambiente do host.

---

## 🔒 Segurança

- Chaves do EmailJS isoladas em `env.js` (não versionado via `.gitignore`)
- Apenas a **Public Key** do EmailJS é utilizada no front-end (padrão recomendado)
- Nenhum dado pessoal sensível exposto no código-fonte
- Links externos com proteção `rel="noopener noreferrer"`

---

## 📄 Licença

Este projeto utiliza o template [iPortfolio](https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/) da BootstrapMade sob sua [licença original](https://bootstrapmade.com/license/).

---

<p align="center">
  Feito com ☕ e muita dedicação por <strong>Jurandi Barreto Silva</strong>
</p>
