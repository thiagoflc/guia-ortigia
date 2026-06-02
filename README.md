# Ortigia · Guia Interativo

Guia turístico interativo *single-page* (SPA) para uma jornada de um dia pela ilha de **Ortigia** (Siracusa, Sicília), com estética *quiet luxury*.

**39 paragens** organizadas em 5 atos (09h30 → pôr do sol), partindo e regressando ao Palazzo Alfeo.

## Funcionalidades

- **Mapa interativo** escuro (Leaflet + CartoDB Dark Matter) sempre visível, com `flyTo` dinâmico.
- **Timeline rolável** sincronizada com o mapa (scroll-spy bidirecional).
- Pontos de **foco** com cards expansíveis e **modal glassmorphism** (descrição, história, horário ideal, custo, insights).
- **Mobile-first**, otimizado para iPhone Pro Max: app-shell, `dvh`, safe areas, swipe-para-fechar, alvos de toque ≥44px, web-app instalável.
- **Imagens reais** de licença livre (Wikimedia Commons), com atribuição no rodapé.

## Stack

HTML5 · Tailwind CSS (CDN) · Alpine.js · Leaflet — tudo em um único arquivo (`index.html`), sem build.

## Ragusa · Dossiê de Operação Tática

Segundo guia no mesmo padrão, em `ragusa.html`: uma operação de um dia por **Ragusa Ibla** e **Ragusa Superiore** (Val di Noto), lida como uma falha tectônica aberta pelo terramoto de 1693. **9 pontos nodais** em 5 atos (09h00 → pôr do sol), partindo e regressando ao *Giardino sul Duomo*. Mesma stack e interações do guia de Ortigia.

## Rodar localmente

Basta abrir `index.html` (Ortigia) ou `ragusa.html` (Ragusa) no navegador, ou servir a pasta:

```bash
npx serve .
# Ortigia → http://localhost:3000/
# Ragusa  → http://localhost:3000/ragusa
```

## Créditos das imagens

Todas as fotografias são reais e de licença livre via **Wikimedia Commons** — autoria e licença listadas na seção "Créditos das imagens" do próprio guia.
