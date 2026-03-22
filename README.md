# ZapSpark Media Bank

Repositório de mídia usada pelo sistema ZapSpark para aquecimento de chips WhatsApp.

## Estrutura

```
images/    → Imagens (.jpg .jpeg .png .gif .webp)
audios/    → Áudios (.mp3 .ogg .opus .wav .m4a)
stickers/  → Stickers (.webp — apenas nesta pasta)
videos/    → Vídeos (.mp4)
```

## Como adicionar mídia

Faça upload dos arquivos nas pastas correspondentes e faça commit.  
Depois, vá no painel Admin do ZapSpark e clique em **Sincronizar GitHub**.

O sistema irá buscar todos os arquivos via GitHub API e inserir as URLs no banco de mídia automaticamente. Sincronizações repetidas ignoram arquivos já existentes.

## Categorias especiais (subpastas)

- `images/status/` → usadas em status do WhatsApp
- `images/group/`  → usadas em grupos de aquecimento

