# Template HTML Blocks — Blog Moderno com Bootstrap 5

Coleção de templates HTML e componentes para blogs e sites de notícias, construídos com **Bootstrap 5.3** e **Bootstrap Icons**. Sem build tools, sem frameworks complexos — apenas HTML puro pronto para usar.

## 📋 Estrutura do Projeto

```
template-html-blocks/
├── block-examples/                  # 🧩 35 blocos de layout prontos
│   ├── index.html                   # Galeria visual de todos os blocos
│   ├── 01-featured-split.html       # Destaque + lista lateral
│   ├── 02-news-hlist.html           # Lista horizontal de notícias
│   ├── 03-featured-sidebar.html     # Destaque com sidebar
│   ├── 04-events-list.html          # Lista de eventos
│   ├── 05-article-thumbnails.html   # Grid de thumbnails
│   ├── 06-deep-dives.html           # Cards com overlay
│   ├── 07-hero-mosaic.html          # Hero mosaico
│   ├── 08-stories-3col.html         # 3 colunas de stories
│   ├── 09-latest-news.html          # Últimas notícias (estilo The Verge)
│   ├── 10-brief-list.html           # Lista compacta
│   ├── 11-podcast-cards.html        # Cards de podcast
│   ├── 12-review-grid.html          # Grid de reviews
│   ├── 13-split-columns.html        # Duas colunas com imagem à direita
│   ├── 14-editorial-feature.html    # Destaque editorial
│   ├── 15-list-feature.html         # Lista com destaque
│   ├── 16-hero-sidebar.html         # Hero + sidebar
│   ├── 17-latest-stories.html       # Últimas histórias
│   ├── 18-tabbed-news.html          # Notícias com abas
│   ├── 19-overlay-grid.html         # Grid com overlay de texto
│   ├── 20-topic-tabs.html           # Tópicos em abas
│   ├── 21-article-stream.html       # Stream de artigos
│   ├── 22-feature-list.html         # Lista com destaque
│   ├── 23-multi-section.html        # Múltiplas seções
│   ├── 24-topic-spotlight.html      # Spotlight por tópico
│   ├── 25-lead-sidebar.html         # Matéria principal + sidebar
│   ├── 26-dark-grid.html            # Grid escuro 4 colunas
│   ├── 27-article-cards.html        # Cards de artigos
│   ├── 28-mosaic-grid.html          # Mosaico de imagens
│   ├── 29-article-featured.html     # Artigo em destaque
│   ├── 30-compact-stream.html       # Stream compacto
│   ├── 31-featured-trio.html        # Trio de destaques
│   ├── 32-wide-sidebar.html         # Layout largo + sidebar
│   ├── 33-dark-section.html         # Seção tema escuro
│   ├── 34-product-feature.html      # Destaque de produto
│   ├── 35-hero-carousel.html        # Hero com carrossel
│   └── *.png                        # Screenshots de referência
│
├── boostrap-ideas/                  # 💡 Páginas completas de blog
│   ├── index.html                   # Homepage do blog
│   ├── post.html                    # Página de artigo individual
│   ├── about.html                   # Página sobre
│   ├── contact.html                 # Página de contato
│   ├── login.html                   # Tela de login
│   ├── register.html                # Tela de cadastro
│   ├── dashboard.html               # Dashboard do usuário
│   ├── 404.html                     # Página de erro 404
│   └── 500.html                     # Página de erro 500
│
└── qwen-blog-dashboard/             # 🎛️ Painel administrativo completo
    ├── dash-home.html               # Dashboard principal
    ├── dash-articles.html           # Gerenciar artigos
    ├── dash-new-article.html        # Novo artigo
    ├── dash-categories.html         # Gerenciar categorias
    ├── dash-new-category.html       # Nova categoria
    ├── dash-users.html              # Gerenciar usuários
    ├── dash-new-user.html           # Novo usuário
    ├── dash-settings.html           # Configurações
    ├── dash-logs.html               # Logs do sistema
    ├── login.html                   # Login do painel
    └── register.html                # Registro do painel
```

## 🧩 Block Examples

A pasta `block-examples/` contém **35 blocos de layout** inspirados em sites de tecnologia reais (The Verge, TechCrunch, Ars Technica, SiliconAngle, MacWorld). Cada bloco é um arquivo HTML independente, com screenshot de referência em PNG.

Abra `block-examples/index.html` para ver a galeria completa com preview de todos os blocos.

### Padrões de layout incluídos
- Split layout (destaque grande + lista lateral)
- Lista horizontal com thumbnails
- Cards com overlay de gradiente
- Seções em tema escuro
- Grid de 4 colunas
- Colunas com imagem à direita
- Hero com carrossel
- Notícias com abas/categorias

## 💡 Bootstrap Ideas

Páginas completas prontas para uso como base de um blog:

| Arquivo | Descrição |
|---------|-----------|
| `index.html` | Homepage com hero, cards e sidebar |
| `post.html` | Artigo completo com sidebar e comentários |
| `about.html` | Página sobre com equipe e missão |
| `contact.html` | Formulário de contato |
| `login.html` | Login com gradiente e blobs decorativos |
| `register.html` | Cadastro com medidor de força de senha |
| `dashboard.html` | Dashboard do usuário autenticado |
| `404.html` | Página de erro 404 |
| `500.html` | Página de erro 500 |

## 🎛️ Dashboard Administrativo

Sistema completo de admin em `qwen-blog-dashboard/`:
- CRUD de artigos, categorias e usuários
- Logs e configurações do sistema
- Login e registro do painel

## 🚀 Como Usar

```bash
# Clonar
git clone https://github.com/mervy/template-html-blocks.git
cd template-html-blocks

# Servidor local (recomendado)
python3 -m http.server 8000
# Acesse: http://localhost:8000/block-examples/
```

Ou abra qualquer arquivo `.html` diretamente no navegador.

## 🛠️ Tecnologias

| Tecnologia | Versão | Uso |
|-----------|--------|-----|
| Bootstrap | 5.3.2+ | Framework CSS |
| Bootstrap Icons | 1.11.3+ | Ícones |
| HTML5 | — | Estrutura |
| JavaScript | Vanilla | Interatividade |

Todas as dependências são carregadas via CDN — sem instalação necessária.

## 🔗 Recursos

- [Bootstrap 5.3 Docs](https://getbootstrap.com/docs/5.3/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [picsum.photos](https://picsum.photos/) — imagens placeholder usadas nos exemplos

## 📄 Licença

MIT — livre para usar, modificar e distribuir.

## 👨‍💻 Autor

**Mervy** — [github.com/mervy](https://github.com/mervy)

---

**Última atualização**: Maio/2026 | Bootstrap 5.3
