# 📝 VexHub Blog - Artigos em Alta

Um blog moderno e responsivo que apresenta os melhores artigos em desenvolvimento web, IA, DevOps e muito mais.

## 🚀 Características

- **📊 Artigos em Alta**: Seção destacada com os conteúdos mais populares
- **📰 Artigos Recentes**: Conheça o conteúdo mais novo
- **🏷️ Categorias**: Navegue por diferentes tópicos
- **📱 Design Responsivo**: Funciona perfeitamente em todos os dispositivos
- **⚡ Performance**: Otimizado para velocidade
- **🎨 Interface Moderna**: Design limpo e intuitivo

## 📂 Estrutura

```
blog/
├── index.html      # Página principal
├── styles.css      # Estilos CSS
├── script.js       # Funcionalidades JavaScript
└── README.md       # Este arquivo
```

## 🎯 Seções

### 1. Header (Navegação)
- Logo do VexHub Blog
- Links de navegação rápida
- Sticky navigation para fácil acesso

### 2. Hero
- Chamada para ação
- Subtítulo atrativo
- Gradiente vibrante

### 3. Artigos em Alta 🔥
- Os 3 artigos mais populares
- Badge de trending
- Contador de visualizações
- Informações do artigo

### 4. Artigos Recentes
- Últimos artigos publicados
- Organização por data
- Categorização

### 5. Categorias
- Frontend (42 artigos)
- Backend (38 artigos)
- DevOps (25 artigos)
- IA e ML (31 artigos)

## 🎨 Paleta de Cores

```
--primary-color: #6366f1 (Indigo)
--secondary-color: #ec4899 (Rosa)
--trending-color: #f97316 (Laranja)
--dark-bg: #0f172a (Azul Escuro)
```

## 💻 Como Usar

1. Abra o arquivo `index.html` em seu navegador
2. Navegue pelas seções usando os links no menu
3. Clique em "Ler Artigo" para ver mais detalhes
4. Explore as categorias disponíveis

## 🔧 Personalização

### Adicionar Novo Artigo

Edite o arquivo `index.html` e adicione um novo `article-card`:

```html
<article class="article-card">
    <div class="article-header">
        <span class="badge">Sua Categoria</span>
        <span class="views">👁️ 0</span>
    </div>
    <h3>Título do Seu Artigo</h3>
    <p>Descrição breve do artigo...</p>
    <div class="article-meta">
        <span class="date">Data</span>
        <span class="category">Categoria</span>
    </div>
    <button class="read-btn">Ler Artigo →</button>
</article>
```

### Modificar Cores

Edite as variáveis CSS em `styles.css`:

```css
:root {
    --primary-color: #sua-cor;
    --secondary-color: #sua-cor;
    /* ... */
}
```

## 📊 JavaScript Features

- Scroll suave (smooth scroll)
- Animação de entrada dos cards
- Contador dinâmico de visualizações
- Destaque de seção ativa na navegação
- Responsividade com IntersectionObserver

## 🌐 Responsividade

O blog é totalmente responsivo:
- **Desktop**: Grid com 3 colunas
- **Tablet**: Grid com 2 colunas
- **Mobile**: Grid com 1 coluna

## 🚀 Deploy

Para fazer deploy do seu blog:

1. **GitHub Pages**: Envie para a branch `gh-pages`
2. **Vercel**: Conecte seu repositório ao Vercel
3. **Netlify**: Faça drag and drop da pasta `blog`

## 📝 Próximas Melhorias

- [ ] Sistema de comentários
- [ ] Busca de artigos
- [ ] Filtro por categoria
- [ ] Integração com banco de dados
- [ ] Sistema de autenticação
- [ ] Newsletter
- [ ] Sharing em redes sociais

## 📧 Contato

Para dúvidas ou sugestões, entre em contato com o time VexHub!

---

**Desenvolvido com ❤️ para a comunidade dev**