# Bendito Sorvete | Site

Site da Bendito Sorvete, sorveteria de Arapongas-PR com sorvetes sem adição de açúcar.

## Estrutura
- `index.html`: página única (Tailwind e ícones via CDN)
- `imagens/`: fotos da loja, dos produtos e o selo (`selo.png`)
- `imagens/galeria/`: fotos da vitrine que passa na horizontal (formato 640x800)

## Publicação
Publicado pelo GitHub Pages a partir do branch `main`, pasta raiz.
Ativar em Settings > Pages > Branch: `main` / `(root)`.

## Manutenção
- Trocar uma foto: substitua o arquivo mantendo o mesmo nome.
- Nova foto na vitrine: salve em `imagens/galeria/` e copie uma linha do bloco `id="galeria"` no `index.html`.
- Preços do "Para levar" ficam no `index.html`, na seção `id="para-levar"`.
