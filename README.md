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

## Modica · A Cidade dos Dois Rios

Terceiro guia, em `modica.html`: uma **jornada essencial de meio-dia** (10h30 → 15h00, chegando de carro) pela cidade-desfiladeiro do Val di Noto. Arco geológico e gastronômico em 5 atos — dos dois rios enterrados sob o **Corso Umberto I**, pela escadaria dos Apóstolos da **San Pietro** e o chocolate frio asteca da **Antica Dolceria Bonajuto**, subindo os 250 degraus do **Duomo di San Giorgio** (com a linha meridiana ao meio-dia) e o **Sabadì**, até o anfiteatro de pedra do **Belvedere del Pizzo** e o ponto mais alto em **San Giovanni Evangelista** — encerrando à mesa do **Fattoria delle Torri**, no pátio de limoeiros. **10 paragens.** Mesma stack e interações.

## Navegação por abas

As três cidades estão ligadas por uma **barra de abas** no cabeçalho de cada guia (Ortigia · Ragusa · Modica), permitindo alternar entre elas como abas de um mesmo site.

## Rodar localmente

Basta abrir `index.html` (Ortigia), `ragusa.html` (Ragusa) ou `modica.html` (Modica) no navegador, ou servir a pasta:

```bash
npx serve .
# Ortigia → http://localhost:3000/
# Ragusa  → http://localhost:3000/ragusa
# Modica  → http://localhost:3000/modica
```

## Créditos das imagens

Todas as fotografias são reais e de licença livre via **Wikimedia Commons** — autoria e licença listadas na seção "Créditos das imagens" do próprio guia.
