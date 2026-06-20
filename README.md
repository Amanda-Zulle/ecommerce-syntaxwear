# 🛍️ SyntaxWear - E-commerce de Tênis e Sneakers

SyntaxWear é uma plataforma de e-commerce moderna e responsiva para compra de tênis e sneakers online. O projeto foi desenvolvido como parte do DevQuest 2.0 - Curso Front-end, com foco em boas práticas de desenvolvimento web, design responsivo e estrutura semântica.

## 📋 Sumário

- [Features](#features)
- [Tecnologias](#tecnologias)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Instalação](#instalação)
- [Como Usar](#como-usar)
- [Componentes](#componentes)
- [Variáveis CSS](#variáveis-css)
- [Responsividade](#responsividade)
- [Autor](#autor)

---

## ✨ Features

- ✅ Design responsivo para mobile, tablet e desktop
- ✅ Menu hamburger para navegação mobile
- ✅ Seção hero com banner principal
- ✅ Categorias de produtos
- ✅ Grid de produtos com layout flexível
- ✅ Navegação intuitiva
- ✅ Footer com informações da empresa
- ✅ Otimizado para SEO
- ✅ Acessibilidade (ARIA labels, semântica HTML)
- ✅ Carregamento rápido com CSS modular

---

## 🛠️ Tecnologias

**Front-end:**
- HTML5 (Estrutura semântica)
- CSS3 (Layout responsivo, Flexbox, Grid)
- JavaScript (Interatividade e menu mobile)

**Recursos:**
- Google Fonts (fonte Ubuntu)
- SVG para ícones e logos
- Meta tags para otimização

---

## 📁 Estrutura do Projeto

```
01-ecommerce-syntaxwear/
│
├── index.html                 # Página principal
├── README.md                  # Documentação
│
├── css/
│   ├── reset.css             # Reset de estilos padrão do navegador
│   ├── variables.css         # Variáveis CSS (fontes, cores, etc)
│   ├── base.css              # Estilos base globais
│   └── components/
│       ├── header.css        # Estilos do cabeçalho
│       ├── hero.css          # Estilos da seção hero
│       ├── product-category.css  # Estilos das categorias
│       ├── product-grid.css  # Estilos do grid de produtos
│       └── footer.css        # Estilos do rodapé
│
├── images/
│   ├── banners/              # Banners promocionais
│   ├── favicons/             # Ícones do navegador
│   ├── icons/                # Ícones SVG (hamburger, user, etc)
│   ├── logo/                 # Logo do site
│   └── products/             # Imagens dos produtos
│
├── js/                        # Arquivos JavaScript (vazio - pronto para expansão)
│
└── .git/                      # Controle de versão Git
```

---

## 🚀 Instalação

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (VS Code, Sublime Text, etc)
- Servidor web local (opcional, mas recomendado)

### Passos

1. **Clone ou baixe o repositório:**
```bash
git clone <https://github.com/Amanda-Zulle/ecommerce-syntaxwear.git>

```

2. **Abra no navegador:**
- Opção 1: Abra o arquivo `index.html` diretamente
- Opção 2: Use um servidor local (recomendado)

---

## 💻 Como Usar

### Estrutura HTML Principal

```html
<!-- Header com navegação -->
<header class="header">
  <h1 class="logo">SyntaxWear</h1>
  <nav class="nav-container">
    <!-- Navegação aqui -->
  </nav>
</header>

<!-- Seção Hero -->
<section class="hero"></section>

<!-- Categorias de Produtos -->
<section class="product-category"></section>

<!-- Grid de Produtos -->
<section class="product-grid"></section>

<!-- Footer -->
<footer class="footer"></footer>
```

## 🎨 Componentes

### Header (`css/components/header.css`)
Componente responsivo com:
- Logo com link para homepage
- Menu de navegação central
- Navegação lateral com acesso rápido
- Ícone de usuário
- Menu hamburger para mobile

### Hero (`css/components/hero.css`)
Banner principal com:
- Imagem de fundo
- Texto destaque
- Call-to-action

### Categorias de Produtos (`css/components/product-category.css`)
Seção com:
- Grid de categorias responsivo
- Cards de categoria com imagem
- Links para cada categoria

### Grid de Produtos (`css/components/product-grid.css`)
Layout com:
- Grid CSS automático
- Cards de produtos
- Informações: imagem, nome, preço
- Hover effects

### Footer (`css/components/footer.css`)
Rodapé com:
- Informações da empresa
- Links rápidos
- Redes sociais
- Informações de contato

---

## 🎯 Variáveis CSS

Arquivo: `css/variables.css`

```css
:root {
  --fonte-principal: 'Ubuntu', sans-serif;
  /* Adicione mais variáveis conforme necessário */
}
```

**Como usar variáveis:**
```css
body {
  font-family: var(--fonte-principal);
}
```

---

## 📱 Responsividade

O projeto é totalmente responsivo com breakpoints para:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

**Recursos responsivos implementados:**
- Menu hamburger para mobile
- Grid adaptativo de produtos
- Imagens escaláveis
- Tipografia fluida
- Flexbox e CSS Grid

---

## 📝 Padrões de Código

### Convenção de Nomes CSS
```css
.block-element-modifier {}  /* BEM - Block Element Modifier */
.header {}
.header__logo {}
.header--mobile {}
```

### Organização HTML
```html
<!-- Use elementos semânticos -->
<header>, <nav>, <section>, <article>, <footer>

<!-- Use ARIA labels para acessibilidade -->
<nav aria-label="Categorias Principais">
```

### Comentários
```css
/* Descrição clara e concisa */
```

---

## 🔗 Recursos Úteis

- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Web.dev - Responsive Design](https://web.dev/responsive-web-design-basics/)
- [A11y Project - Accessibility](https://www.a11yproject.com/)

---

## 👨‍💻 Autor

Desenvolvido como parte do **DevQuest 2.0 - Curso Front-end**

---

*Última atualização: 20 de junho de 2026*
