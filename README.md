# Template HTML Blocks - Blog Moderno com Bootstrap 5

Uma coleção completa de templates HTML e componentes para criar um **blog moderno**, utilizando **Bootstrap 5.3** e **Bootstrap Icons**. Perfeito para quem deseja começar um projeto de blog rapidamente sem complicações de build tools ou frameworks complexos.

## 📋 Estrutura do Projeto

```
template-html-blocks/
├── blocks-image/                    # 📸 Screenshots e imagens dos designs
├── boostrap-ideas/                  # 💡 Templates base e exemplos de Bootstrap
│   ├── index.html                   # Landing page do blog
│   ├── post.html                    # Página individual de artigo
│   ├── cards_blog (1-2).html        # Variações de layouts com cards
│   ├── index-2.html, index-3.html   # Alternativas de homepage
│   ├── posts-2.html                 # Lista avançada de posts
│   └── assets/
│       ├── css/styles.css           # Estilos customizados
│       ├── js/scripts.js            # Funcionalidades JavaScript
│       └── img/                     # Imagens do projeto
└── qwen-blog-dashboard/             # 🎨 Blog Dashboard Completo
    ├── home.html                    # Homepage principal
    ├── artigos.html                 # Listagem de artigos
    ├── post.html                    # Página de artigo individual
    ├── categorias.html              # Página de categorias
    ├── sobre.html                   # Página sobre o blog
    ├── contato.html                 # Página de contato
    ├── login.html                   # Página de login
    ├── register.html                # Página de registro
    └── dashboard/                   # 📊 Painel administrativo
        ├── dash-home.html           # Dashboard home
        ├── dash-articles.html       # Gerenciar artigos
        ├── dash-categories.html     # Gerenciar categorias
        ├── dash-users.html          # Gerenciar usuários
        ├── dash-settings.html       # Configurações
        ├── dash-logs.html           # Logs do sistema
        └── dash-*.html              # Outras páginas administrativas
```

## 🎯 Características Principais

### ✨ Bootstrap 5.3 Puro
- Sem dependências complexas
- Apenas CDN do Bootstrap 5.3
- Bootstrap Icons para ícones modernos
- Totalmente responsivo (mobile-first)

### 🎨 Layouts Disponíveis
- **Homepage**: Hero section moderno com call-to-action
- **Blog**: Listagem de artigos com cards variados
- **Post Individual**: Página completa de leitura de artigo
- **Categorias**: Grid de categorias com ícones
- **Dashboard**: Sistema completo de administração
- **Autenticação**: Páginas de login e registro

### 📱 Responsивность
- Design mobile-first
- Totalmente adaptável a todos os tamanhos de tela
- Navbar colapsível para dispositivos menores
- Grid system flexível do Bootstrap

### 🔍 SEO Pronto
- Meta tags semânticas
- Estrutura HTML adequada
- Acessibilidade WCAG

## 🚀 Como Usar

### 1. Clonar o Repositório
```bash
git clone https://github.com/mervy/template-html-blocks.git
cd template-html-blocks
```

### 2. Abrir os Arquivos
**Opção A - Diretamente no navegador:**
```bash
# Linux/Mac
open boostrap-ideas/index.html

# Ou use um servidor local
python3 -m http.server 8000
# Acesse: http://localhost:8000
```

**Opção B - Com VS Code:**
- Instale a extensão "Live Server"
- Clique com botão direito no arquivo HTML
- Selecione "Open with Live Server"

### 3. Personalizar
- Edite os arquivos HTML conforme necessário
- Use as classes Bootstrap para alterações rápidas
- Customize cores e temas via variáveis CSS ou bootstrap themes

## 📦 Conteúdo Incluído

### Bootstrap Ideas (boostrap-ideas/)
Templates variados baseados em exemplos oficiais do Bootstrap:
- Blog homepage
- Layouts de cards de blog
- Múltiplas variações de design
- Assets base (CSS, JS, imagens)

### Qwen Blog Dashboard (qwen-blog-dashboard/)
Sistema completo de blog com:
- **Frontend**: Páginas públicas do blog (home, artigos, categorias, etc.)
- **Autenticação**: Login e registro
- **Dashboard Administrativo**: 
  - Gerenciamento de artigos
  - Gerenciamento de categorias
  - Gerenciamento de usuários
  - Logs e configurações

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Versão | Uso |
|-----------|--------|-----|
| Bootstrap | 5.3.2+ | Framework CSS |
| Bootstrap Icons | 1.11.3+ | Ícones SVG |
| HTML5 | - | Estrutura |
| CSS3 | - | Estilos (apenas Bootstrap) |
| JavaScript | Vanilla | Interatividade |

## 📝 Exemplos de Uso

### Modificar Navbar
```html
<nav class="navbar navbar-expand-lg navbar-dark bg-info bg-gradient shadow-sm">
  <!-- Personalize as cores com: bg-primary, bg-success, bg-danger, etc. -->
</nav>
```

### Adicionar Cards de Artigos
```html
<div class="card mb-4">
  <img class="card-img-top" src="imagem.jpg" alt="...">
  <div class="card-body">
    <h5 class="card-title">Título do Artigo</h5>
    <p class="card-text">Resumo do artigo...</p>
  </div>
</div>
```

### Criar Hero Section
```html
<header class="py-5 bg-light border-bottom">
  <div class="container">
    <h1 class="display-5 fw-bold">Título Principal</h1>
    <p class="lead text-muted">Subtítulo ou descrição</p>
  </div>
</header>
```

## 🎨 Personalizando Temas

### Cores Bootstrap Disponíveis
- `bg-primary` - Azul
- `bg-success` - Verde
- `bg-danger` - Vermelho
- `bg-warning` - Amarelo
- `bg-info` - Ciano
- `bg-dark` - Escuro
- `bg-light` - Claro

### Gradientes
Adicione `bg-gradient` para efeito degradê:
```html
<div class="bg-primary bg-gradient">
  <!-- Conteúdo com gradiente -->
</div>
```

## 📸 Telas Disponíveis

O projeto inclui screenshots de todos os layouts em `blocks-image/`:
- Navbar com search
- Hero sections
- Cards de blog
- Layouts de categorias
- Dashboard administrativo
- Páginas de autenticação

## 🔗 Recursos Úteis

- [Bootstrap 5.3 Documentação](https://getbootstrap.com/docs/5.3/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [Bootstrap Examples](https://getbootstrap.com/docs/5.3/examples/)

## 📄 Estrutura de Páginas

### Página Pública
- **URL**: `home.html`
- **Elementos**: Navbar, Hero, Lista de artigos, Footer

### Página de Artigo
- **URL**: `post.html`
- **Elementos**: Cabeçalho, Conteúdo, Sidebar, Comentários

### Dashboard
- **URL**: `dash-home.html`
- **Acesso**: Via login
- **Funções**: CRUD de artigos, categorias e usuários

## 💡 Dicas de Desenvolvimento

1. **Manter Simplicidade**: Use apenas classes Bootstrap, evite CSS customizado
2. **Responsividasde**: Teste sempre em dispositivos móveis
3. **Acessibilidade**: Mantenha atributos `alt` em imagens e labels em formulários
4. **Performance**: Use imagens otimizadas e CDN do Bootstrap
5. **Manutenção**: Comente seu código para facilitar manutenção futura

## 🤝 Contribuindo

Para sugerir melhorias ou reportar bugs:
1. Abra uma Issue no repositório
2. Faça um Fork do projeto
3. Crie uma branch com sua feature (`git checkout -b feature/AmazingFeature`)
4. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
5. Push para a branch (`git push origin feature/AmazingFeature`)
6. Abra um Pull Request

## 📄 Licença

Este projeto está disponível sob licença MIT. Você é livre para usar, modificar e distribuir este código.

## 👨‍💻 Autor

**Mervy** - [GitHub](https://github.com/mervy)

---

## ❓ Perguntas Frequentes

**P: Preciso de um servidor para rodar?**
R: Não obrigatoriamente, mas é recomendado para melhor compatibilidade com recursos modernos. Use `python3 -m http.server 8000`.

**P: Posso usar em produção?**
R: Sim! Os templates são baseados em melhores práticas do Bootstrap e são prontos para produção.

**P: Como adicionar uma nova página?**
R: Copie um arquivo HTML existente, renomeie e customize conforme necessário. Mantenha a estrutura base.

**P: Posso customizar as cores?**
R: Sim! Use as variáveis de cor do Bootstrap nas classes (bg-primary, text-info, etc.) ou adicione CSS customizado no `assets/css/`.

---

**Última atualização**: Maio/2026 | Bootstrap 5.3.8
