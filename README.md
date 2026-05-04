# Calculadora Boi Casado - PWA

Site PWA instalável para GitHub Pages.

## Arquivos

- `index.html` — app principal
- `manifest.json` — configura nome, ícones e instalação
- `sw.js` — service worker para funcionar offline
- `assets/icons/` — ícones do app
- `.nojekyll` — evita processamento do GitHub Pages

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
   - Importante: não envie só o `index.html`; envie também `manifest.json`, `sw.js` e a pasta `assets`.
3. No GitHub, entre em **Settings > Pages**.
4. Em **Build and deployment**, escolha:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Clique em **Save**.
6. Abra a URL gerada pelo GitHub Pages no celular.
7. No navegador, use **Adicionar à tela inicial** ou **Instalar app**.

## Observações

- O PWA precisa de HTTPS para instalar corretamente. O GitHub Pages já fornece HTTPS.
- O modo offline começa a funcionar depois do primeiro acesso publicado.
- Para atualizar o app, substitua os arquivos no GitHub. Se o celular continuar mostrando a versão antiga, feche o app e abra novamente; em alguns casos é preciso limpar cache ou reinstalar o atalho.
