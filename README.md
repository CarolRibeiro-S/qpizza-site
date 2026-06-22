# QPIZZA — Site Institucional

Site institucional da **QPIZZA**, pizzaria artesanal localizada em Brasília/DF. Desenvolvido como projeto pessoal por [Carol Ribeiro](https://www.instagram.com/carolribeirodev/).

---

## Tecnologias

- HTML5 semântico
- CSS3 (variáveis CSS, Grid, Flexbox, animações)
- JavaScript vanilla
- Google Fonts — Nunito + Urbanist
- Deploy via [Vercel](https://vercel.com) com integração ao GitHub

---

## Estrutura de Páginas

| Arquivo | Página |
|---|---|
| `index.html` | Home — hero, cards de destaque e localização |
| `promocoes.html` | Promoções — cardápio semanal com pizzas, dogs e esfihas |
| `informacoes.html` | Informações — horários, áreas de entrega, formas de pagamento e FAQ |
| `historia.html` | Nossa História — origem e valores da QPIZZA |
| `reserva.html` | Reservas — formulário de reserva de mesa com código verificador |
| `feedback.html` | Feedback — formulário de avaliação da experiência |
| `trabalhe-conosco.html` | Trabalhe Conosco — vagas abertas e banco de talentos |

---

## Assets

```
qpizza2.logo.png        — Logo principal (header)
qpizza_favicon.ico      — Favicon
qpizza_favicon-512.png  — Apple touch icon
fundo site.jpeg         — Imagem de fundo (hero e seções)
Nossa história.jpeg     — Foto da seção Nossa História
styles.css              — Estilos globais
```

---

## Como Rodar Localmente

O projeto é 100% estático — basta abrir o `index.html` no navegador ou usar qualquer servidor local:

```bash
# Com Live Server (VS Code)
# Clique com botão direito em index.html → "Open with Live Server"

# Com Python
python -m http.server 8000

# Com Node.js (npx)
npx serve .
```

---

## Funcionalidades

- **Pedido online** — todos os botões de pedido redirecionam para `qpizza.wabiz.delivery`
- **Reserva de mesa** — formulário com geração de código verificador único
- **Filtro de informações** — alternância entre "Informações Gerais" e "Dúvidas Frequentes"
- **Promoções por dia da semana** — cardápio dinâmico com categorias filtráveis
- **Formulário de feedback** — avaliação de nota, canal de pedido e comentário livre
- **Formulário "Trabalhe Conosco"** — candidatura com seleção de vaga e banco de talentos
- **Menu mobile responsivo** — hamburguer com animação e fechamento ao clicar nos links
- **Cursor personalizado** — cursor 🍕 em toda a página

---

## Design

- **Paleta:** fundo escuro `#1c1a19` / alternado `#2c2a29`, laranja `#f15223`
- **Tipografia:** Nunito (títulos e botões), Urbanist (corpo do texto)
- **Responsivo:** breakpoints em 1200px, 1024px e 768px

---

## Deploy

O site é publicado automaticamente via Vercel a cada push na branch `main` do repositório GitHub [`CarolRibeiro-S/qpizza-site`](https://github.com/CarolRibeiro-S/qpizza-site).

---

*Site criado e desenvolvido por [Carol Ribeiro](https://www.instagram.com/carolribeirodev/)*
