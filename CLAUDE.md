# Brasil Fashion Premium em Crochê — Página de Vendas

Projeto de página de vendas HTML estática para o curso **"Brasil Fashion Premium em Crochê"**.

## Estrutura do projeto

```
Brasil Fashion Premium em Crochê/
├── index.html          ← ARQUIVO PRINCIPAL (fonte da verdade, editar aqui)
├── site-netlify/
│   ├── index.html      ← Cópia sincronizada do index.html principal
│   ├── netlify.toml    ← Configurações de segurança/cache do Netlify
│   └── robots.txt      ← Permite indexação pelo Google
├── site-hostinger.zip  ← Zip pronto para upload na Hostinger
└── CLAUDE.md           ← Este arquivo
```

## Regras importantes

- **Sempre editar `index.html`** na raiz — ele é a fonte da verdade.
- Após editar, **sincronizar** `site-netlify/index.html` (copiar o index.html para lá).
- Após sincronizar, **recriar o zip** `site-hostinger.zip` com os arquivos de `site-netlify/`.

## Produto

- **Nome:** Brasil Fashion Premium em Crochê
- **Tipo:** Curso completo (vídeo aulas)
- **Checkout:** Hotmart — substituir `[LINK_HOTMART]` no HTML
- **Preço:** substituir `[PRECO_DE]` e `[XX],[XX]` no HTML
- **Meta Pixel:** substituir `[META_PIXEL_ID]` no HTML
- **Imagem OG:** substituir `[OG_IMAGE_URL]` no HTML
- **Imagens:** substituir placeholders `.ph` por `<img>` reais (Cloudinary recomendado)
- **Fontes:** Google Fonts (Cormorant Garamond, DM Sans, JetBrains Mono)

## Identidade visual

- Paleta: vinho (`oklch(0.37 0.13 10)`) + ouro (`oklch(0.78 0.14 83)`) + blush + ivory
- **Completamente independente** do projeto Crochê PET Copa Brasil

## Deploy

- **Netlify:** arrastar a pasta `site-netlify/` em https://app.netlify.com/drop
- **Hostinger:** fazer upload do `site-hostinger.zip` no painel de hospedagem

## Placeholders para preencher antes do lançamento

| Placeholder | O que colocar |
|---|---|
| `[META_PIXEL_ID]` | ID do pixel do Facebook |
| `[OG_IMAGE_URL]` | URL da imagem de compartilhamento |
| `[LINK_HOTMART]` | Link do checkout Hotmart |
| `[PRECO_DE]` | Preço riscado (ex: 197,00) |
| `[XX],[XX]` | Preço atual (ex: 97,00) |
| Blocos `.ph` | Substituir por `<img src="...">` reais |
