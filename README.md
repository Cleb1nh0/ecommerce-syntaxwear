# 🎯 SyntaxWear - Ecommerce de Tênis e Sneakers

[![GitHub](https://img.shields.io/badge/GitHub-Cleb1nh0%2Fecommerce--syntaxwear-black?logo=github)](https://github.com/Cleb1nh0/ecommerce-syntaxwear)

Um site ecommerce moderno e responsivo para venda de tênis e sneakers premium. Desenvolvido com HTML, CSS e JavaScript, oferecendo uma experiência de compra intuitiva e visualmente atrativa.

## 📋 Sumário

- [Visão Geral](#visão-geral)
- [Funcionalidades](#-funcionalidades)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como Começar](#-como-começar)
- [Repositório](#-repositório)
- [Estrutura de Arquivos](#-estrutura-de-arquivos)
- [Componentes CSS](#-componentes-css)
- [Seções do Site](#-seções-do-site)
- [Design Responsivo](#-design-responsivo)
- [Próximas Etapas](#-próximas-etapas)
- [Contribuições](#-contribuições)
- [Estrutura de Arquivos](#-estrutura-de-arquivos)
- [Componentes CSS](#-componentes-css)
- [Seções do Site](#-seções-do-site)
- [Design Responsivo](#-design-responsivo)
- [Contribuições](#-contribuições)

## 👀 Visão Geral

**SyntaxWear** é uma plataforma ecommerce especializada em tênis e sneakers de alta qualidade. O site oferece uma navegação intuitiva, catálogo de produtos bem organizado e interface responsiva que funciona perfeitamente em dispositivos móveis, tablets e desktops.

### Público-alvo
- Adultos que buscam tênis e sneakers de qualidade
- Consumidores interessados em moda urbana
- Clientes que valorizam design e conforto

## ✨ Funcionalidades

- ✅ **Navegação Responsiva** - Menu adaptável para mobile e desktop
- ✅ **Catálogo de Produtos** - Grid de produtos com categorias (Masculino, Feminino, Outlet)
- ✅ **Hero Section** - Banner principal destacado
- ✅ **Filtro de Categorias** - Organização por gênero e tipo
- ✅ **Design Moderno** - Interface limpa e professional
- ✅ **Otimização para Mobile** - Totalmente responsivo
- ✅ **Acessibilidade** - Marcação semântica HTML e ARIA labels
- ✅ **Carregamento Rápido** - Arquivo CSS modularizado

## 📁 Estrutura do Projeto

```
ecommerce-syntaxwear/
├── index.html              # Página principal
├── README.md               # Documentação do projeto
├── css/
│   ├── reset.css           # Reset e normalização
│   ├── variables.css       # Variáveis CSS (cores, fontes)
│   ├── base.css            # Estilos base globais
│   └── components/
│       ├── header.css      # Estilo do cabeçalho
│       ├── hero.css        # Estilo da seção hero
│       ├── product-category.css  # Estilo das categorias
│       ├── product-grid.css      # Estilo do grid de produtos
│       └── footer.css      # Estilo do rodapé
├── images/
│   ├── logo/               # Logo da marca
│   ├── banners/            # Imagens de banner
│   ├── icons/              # Ícones do site
│   ├── favicons/           # Favicon do navegador
│   └── products/           # Imagens dos produtos
├── js/                     # Arquivos JavaScript (em desenvolvimento)
└── .git/                   # Controle de versão Git

```

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Marcação semântica
- **CSS3** - Estilos e responsividade
  - Variáveis CSS (Custom Properties)
  - Flexbox e CSS Grid
  - Media Queries para responsividade
- **JavaScript** - Interatividade (a implementar)
- **Git** - Controle de versão

## 🚀 Como Começar

### Pré-requisitos
- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (VS Code recomendado)
- Git instalado (opcional)

### Instalação

1. **Clone o repositório** (se usando Git):
```bash
git clone https://github.com/Cleb1nh0/ecommerce-syntaxwear.git
cd ecommerce-syntaxwear
```

2. **Abra o arquivo principal**:
```bash
# No Windows
start index.html

# No macOS
open index.html

# No Linux
xdg-open index.html
```

Ou simplesmente abra o arquivo `index.html` diretamente no seu navegador.

## � Repositório

**[github.com/Cleb1nh0/ecommerce-syntaxwear](https://github.com/Cleb1nh0/ecommerce-syntaxwear)**

Clone ou contribua no nosso repositório GitHub.

## �📄 Estrutura de Arquivos

### HTML (`index.html`)

O arquivo HTML contém:
- **Header** - Logo, navegação principal e ícones de conta
- **Hero Section** - Banner principal com destaque
- **Product Category** - Filtros por categoria
- **Product Grid** - Exibição dos produtos
- **Footer** - Links e informações adicionais

Meta tags importantes:
```html
<title>SyntaxWear - tênis e Sneakers Online</title>
<meta name="description" content="...">
<meta name="viewport" content="width=device-width, initial-scale=1">
```

### CSS (`/css`)

#### Arquivos Base
- **reset.css** - Reset de estilos padrão do navegador
- **variables.css** - Variáveis reutilizáveis (cores, tipografia, espaçamento)
- **base.css** - Estilos globais e padrões

#### Componentes (`/css/components`)
- **header.css** - Cabeçalho com navegação responsiva
- **hero.css** - Seção de destaque principal
- **product-category.css** - Barra de categorias/filtros
- **product-grid.css** - Layout grid dos produtos
- **footer.css** - Rodapé do site

## 🎨 Componentes CSS

### Variáveis CSS
Definidas em `variables.css`:
- Cores primárias e secundárias
- Tipografia e tamanhos de fonte
- Espaçamento (padding, margin)
- Breakpoints de responsividade

### Estrutura de Componentes
Cada componente segue a estrutura:
- Estilo base
- Estados (hover, active, disabled)
- Responsividade (mobile-first)

## 📖 Seções do Site

### 1. **Header**
- Logo/marca SyntaxWear
- Menu de navegação principal (Masculino, Feminino, Outlet)
- Links rápidos (Nossas lojas, Sobre)
- Ícone de conta/login
- Menu hamburger responsivo para mobile

### 2. **Hero Section**
- Banner principal com destaque
- Imagem ou vídeo de fundo
- Call-to-action

### 3. **Categorias de Produtos**
- Filtros por categoria
- Opções de ordenação

### 4. **Grid de Produtos**
- Exibição em grid dos produtos
- Card de produto com:
  - Imagem do produto
  - Nome/título
  - Preço
  - Botão de ação

### 5. **Footer**
- Links úteis
- Informações de contato
- Redes sociais
- Políticas (privacidade, termos)

## 📱 Design Responsivo

O site é totalmente responsivo com breakpoints para:
- **Mobile** - até 480px
- **Tablet** - 481px a 768px
- **Desktop** - acima de 769px

Implementação via CSS Media Queries em cada componente.

## 🗂️ Organização de Imagens

```
images/
├── logo/              # Logo.svg e variações
├── banners/           # Imagens de banner principal
├── icons/             # hamburger.svg, user.svg, etc.
├── favicons/          # Favicon em diferentes formatos
└── products/          # Imagens dos produtos
    ├── masculino/     # Produtos masculinos
    ├── feminino/      # Produtos femininos
    └── outlet/        # Produtos de outlet
```

## 🔧 Como Adicionar Novos Produtos

1. Adicione a imagem do produto em `images/products/`
2. Atualize o HTML em `index.html` com novo item no grid
3. A estilização será aplicada automaticamente via `product-grid.css`

## 📦 Como Adicionar Novas Funcionalidades

### Adicionar um novo componente CSS:
1. Crie `css/components/novo-componente.css`
2. Importe em `index.html`: `<link rel="stylesheet" href="./css/components/novo-componente.css">`
3. Implemente a lógica HTML
4. Estilize em CSS

### Adicionar JavaScript:
1. Crie arquivo em `js/` (ex: `js/main.js`, `js/cart.js`)
2. Importe no final do `index.html`: `<script src="./js/arquivo.js"></script>`

## 🎯 Próximas Etapas (TODO)

- [ ] Implementar funcionalidade de carrinho de compras
- [ ] Adicionar sistema de filtros dinâmicos (JavaScript)
- [ ] Integrar com backend para dados de produtos
- [ ] Implementar sistema de autenticação
- [ ] Adicionar página de detalhe do produto
- [ ] Integração com gateway de pagamento
- [ ] Sistema de avaliações e comentários
- [ ] SEO otimizado

## 🤝 Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona NovaFuncionalidade'`)
4. Push para a branch (`git push origin feature/NovaFuncionalidade`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença [Sua Licença - ex: MIT, Apache 2.0]

## 📞 Suporte e Contato

- **Email**: contato@syntaxwear.com
- **Site**: www.syntaxwear.com
- **Redes Sociais**: [@syntaxwear](https://social.com)

## 📚 Referências e Recursos

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks](https://css-tricks.com/)
- [Can I Use](https://caniuse.com/) - Compatibilidade de navegadores
- [Accessibility Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)

---

**Última atualização**: 16 de fevereiro de 2026  
**Versão**: 1.0.0  
**Status**: Em Desenvolvimento
