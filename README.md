# Site — Bruno Kzimiro Tattoo

Site estático (HTML/CSS/JS puro, sem build, sem dependências de servidor).

## Estrutura
```
index.html          → a página inteira
assets/img/          → fotos e logo
assets/video/        → vídeo do estúdio + capa (poster)
```

## Como subir no GitHub Pages
1. Crie um repositório novo no GitHub e suba todo o conteúdo desta pasta (mantendo a estrutura de pastas).
2. Vá em **Settings → Pages** do repositório.
3. Em "Branch", selecione `main` (ou `master`) e pasta `/root`, depois salve.
4. Em alguns minutos o site fica disponível em `https://SEUUSUARIO.github.io/NOME-DO-REPOSITORIO/`.

Não precisa de nenhum passo de build — é só HTML/CSS/JS direto.

## O que ajustar antes de publicar de verdade
Abra `index.html`, procure por `CONFIG` perto do final do arquivo (dentro da tag `<script>`) e confira:

- `whatsappNumber` — número que recebe os pedidos de orçamento pelo formulário.
- `instagramUrl` — está como `https://www.instagram.com/b.kzimiro/`, achado por busca e confirmado pelo cliente.
- `mapsUrl` / `reviewsUrl` — links do Google Maps (local e avaliações).

## Pendências conhecidas
- O vídeo da seção "Localização" está com um ângulo bem inclinado (estilo do vídeo original enviado pelo cliente) — não foi alterado porque parece intencional, mas vale confirmar com o cliente se ele quer trocar por outro vídeo/fotos.
- Se novas fotos de tatuagens forem adicionadas, mantenha a proporção retrato (3:4) pra não cortar a tatuagem — é o padrão usado em toda a galeria.
