# Crochê PET Copa Brasil — Página de Vendas

Projeto de página de vendas HTML estática para o produto "Roupinhas de Crochê para Pets — Edição Copa do Mundo".

## Estrutura do projeto

```
Croche PET Copa Brasil/
├── index.html          ← ARQUIVO PRINCIPAL (fonte da verdade, editar aqui)
├── app.jsx             ← Componente React de referência (desenvolvimento)
├── tweaks-panel.jsx    ← Painel de ajustes visual (desenvolvimento)
├── site-hostinger.zip  ← Zip pronto para upload na Hostinger
├── site-netlify/
│   ├── index.html      ← Cópia sincronizada do index.html principal
│   ├── netlify.toml    ← Configurações de segurança/cache do Netlify
│   └── robots.txt      ← Permite indexação pelo Google
└── CLAUDE.md           ← Este arquivo
```

## Regras importantes

- **Sempre editar `index.html`** na raiz — ele é a fonte da verdade.
- Após editar, **sincronizar** `site-netlify/index.html` (copiar o index.html para lá).
- Após sincronizar, **recriar o zip** `site-hostinger.zip` com os arquivos de `site-netlify/`.
- Os arquivos `app.jsx` e `tweaks-panel.jsx` são referência de desenvolvimento, não vão para o servidor.

## Produto

- **Nome:** Roupinhas de Crochê para Pets — Edição Copa do Mundo
- **Checkout:** Hotmart (links já embutidos nos botões do HTML)
- **Imagens:** hospedadas no Cloudinary
- **Fontes:** Google Fonts (Instrument Serif, Plus Jakarta Sans, JetBrains Mono)

## Deploy

- **Netlify:** arrastar a pasta `site-netlify/` em https://app.netlify.com/drop
- **Hostinger:** fazer upload do `site-hostinger.zip` no painel de hospedagem
