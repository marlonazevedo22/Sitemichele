# Site Michele Almeida

Landing pages e site institucional para Fisioterapia Pediátrica.

## Estrutura
- `index.html`: Home
- `servicos.html`: Serviços
- `ebook.html`: LP do Ebook (Hotmart)
- `sobre.html`, `metodo.html`, `404.html`, `robots.txt`, `sitemap.xml`, `style.css`
- `privacidade.html`, `termos.html`: Páginas legais

## Configurações
- Hotmart: link configurado em `ebook.html` (const `HOTMART_LINK`) e na home para CTA do ebook.
- Imagens: `mokap-ebook.jpg` (capa do ebook) e `MicheleProf.JPG` (foto).

## Desenvolvimento
Abra com Live Server ou qualquer http server.

```bash
# Exemplo com Python
python -m http.server 8080
# Depois, acesse http://localhost:8080
```

## Deploy
Publicar em qualquer host estático (Netlify, Vercel, GitHub Pages ou servidor próprio).
- Garanta HTTPS
- Configure redirecionamentos 404 se necessário

## Boas práticas
- Links externos com `rel="noopener noreferrer"`
- Contador da LP persiste 48h via `localStorage`
- CSS centralizado em `style.css`

## SEO
- Metas OG e canonical configuradas em `index.html` e `ebook.html`
- `sitemap.xml` e `robots.txt` presentes

## Licenças e direitos
Conteúdos são propriedade da autora. Não reproduzir sem autorização.
