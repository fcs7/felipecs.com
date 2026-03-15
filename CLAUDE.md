# felipecs.com

Portal pessoal com links para aplicações self-hosted.

## Stack

- HTML/CSS/JS puro — sem frameworks, sem build step
- Hospedagem: Plesk com Git auto-deploy
- Deploy: push para remote → Plesk puxa automaticamente

## Estrutura

```
index.html          # Página única
css/style.css       # Estilos com CSS custom properties
js/main.js          # Animações mínimas (Intersection Observer)
assets/icons/       # Ícones SVG (se necessário)
```

## Convenções

- **CSS**: Custom properties em `:root` para cores/espaçamentos. Mobile-first.
- **HTML**: Semântico (header/main/footer). Cards são `<a class="card">`.
- **JS**: Mínimo e progressivo. Sem dependências externas.
- **Adicionar novo app**: Copiar bloco `<a class="card">` em `index.html` dentro da `.cards-grid`.

## Design

- Tema escuro com glassmorphism sutil
- Fonte display: Sora (Google Fonts)
- Paleta definida em CSS custom properties em `:root`
