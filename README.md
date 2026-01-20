# Site Michele Almeida

Landing pages e site institucional para Fisioterapia Pediátrica.

## 🚀 Repositório
[https://github.com/marlonazevedo22/Sitemichele](https://github.com/marlonazevedo22/Sitemichele)

## Estrutura
- `index.html`: Home
- `servicos.html`: Serviços
- `ebook.html`: LP do Ebook (Hotmart)
- `sobre.html`, `metodo.html`, `404.html`, `robots.txt`, `sitemap.xml`, `style.css`
- `privacidade.html`, `termos.html`: Páginas legais

## Configurações
- Hotmart: link configurado apenas em `ebook.html` (const `HOTMART_LINK`). Outras páginas redirecionam para a LP.
- Imagens: `mokap-ebook.jpg` (capa do ebook) e `MicheleProf.JPG` (foto).

## Desenvolvimento
Abra com Live Server (extensão do VS Code) ou qualquer servidor HTTP local.

## Deploy
Publicar em qualquer host estático (Netlify, Vercel, GitHub Pages ou servidor próprio).
- Garanta HTTPS
- Configure redirecionamentos 404 se necessário

### Deploy rápido com Netlify
```bash
# Instale o CLI (se ainda não tiver)
npm install -g netlify-cli

# Deploy direto da pasta
netlify deploy --prod
```

### Deploy com Vercel
```bash
# Instale o CLI
npm install -g vercel

# Deploy
vercel --prod
```

### GitHub Pages
1. Vá em Settings → Pages
2. Escolha branch `main` e pasta `/` (root)
3. Site estará em `https://marlonazevedo22.github.io/Sitemichele/`

## Boas práticas
- Links externos com `rel="noopener noreferrer"`
- Contador da LP persiste 48h via `localStorage`
- CSS centralizado em `style.css`

## SEO
- Metas OG e canonical configuradas em `index.html` e `ebook.html`
- `sitemap.xml` e `robots.txt` presentes

## Licenças e direitos
Conteúdos são propriedade da autora. Não reproduzir sem autorização.
