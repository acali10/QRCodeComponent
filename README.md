# 📱 QR Code Component

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

Resolução do desafio **QR Code Component** do [Frontend Mentor](https://www.frontendmentor.io/). O objetivo foi construir um cartão simples e centralizado exibindo um QR code, com foco em fidelidade visual ao design fornecido.

🔗 **[🚀 Clique aqui para ver o projeto online](https://acali10.github.io/QRCodeComponent/)**

---

## 📷 Demonstração

![Preview do Projeto](./assets/screenshot.png)

---

## 🛠️ Tecnologias e Conceitos Aplicados

- **HTML5 Semântico:** uso de `<main>` e `<footer>` para estruturar o conteúdo, e `<div class="textos">` para agrupar o título e a descrição do card.
- **Flexbox:** `body` com `flex-direction: column` e `justify-content: space-between` para distribuir o card e o footer na tela, e `.container` com `flex-grow: 1` para ocupar o espaço restante e manter o card sempre centralizado verticalmente.
- **CSS Nesting:** aninhamento nativo de seletores dentro de `.card` e `.textos` para agrupar estilos de elementos filhos (`img`, `h2`, `p`).
- **Border Radius:** bordas arredondadas no card e na imagem, seguindo o design original do desafio.
- **Acessibilidade por teclado:** estado `a:focus-visible` com contorno visível, garantindo que os links do footer sejam identificáveis ao navegar com Tab, sem depender apenas do mouse.
- **Favicon:** ícone customizado da aba do navegador via `<link rel="icon">`.

---

## 💡 O que aprendi

Esse desafio, apesar de visualmente simples, foi um bom exercício de **fidelidade a um design fornecido** — reproduzir exatamente o espaçamento, as proporções do card e o alinhamento entre imagem e texto, sem margem para "interpretação livre" como em projetos mais abertos.

Também revisei a acessibilidade por teclado, adicionando um estado de foco visível nos links, já que o CSS original só tratava o `:hover` (mouse), deixando quem navega via Tab sem indicação clara de onde estava o foco:

```css
a:focus-visible{
    outline: 2px solid #1f3251;
    outline-offset: 3px;
    border-radius: 4px;
}
```

---

## 💻 Como rodar o projeto localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/acali10/QRCodeComponent.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd QRCodeComponent
   ```
3. Abra o arquivo `index.html` em seu navegador.

---

## 🔜 Melhorias futuras

- Adicionar um `alt` descritivo na imagem do QR code (atualmente vazio).
- Converter a imagem para `.webp` visando otimização de carregamento.
- Adicionar variáveis CSS (`:root`) para facilitar manutenção de cores, caso o projeto cresça.

---

## 👤 Autora

Desenvolvido por Caline Nepomoceno:
- GitHub: [@acali10](https://github.com/acali10)
- Frontend Mentor: [@acali10](https://www.frontendmentor.io/profile/acali10)
