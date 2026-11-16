# Portfólio Pessoal - Kleber Morais

**Aluno:** Kleber Morais

## 📄 Descrição do Portfólio
Este projeto representa a evolução do exercício inicial *"Meus Sites Favoritos"* desenvolvido em aula, transformado em um portfólio pessoal completo e responsivo. O site tem como objetivo apresentar meu perfil profissional, projetos desenvolvidos e as principais ferramentas web que utilizo no dia a dia de estudos em programação.

## 🚀 Tecnologias Utilizadas
* **HTML5:** Estruturação semântica das seções da página.
* **CSS3:** Estilização personalizada, gradientes, transições e animações de interação.
* **Bootstrap 5:** Sistema de grid responsivo, barra de navegação colapsável, cards, badges, carrossel e formulário de contato.
* **Bootstrap Icons:** Ícones vetoriais aplicados na navegação, cards e rodapé.
* **Git & GitHub Pages:** Controle de versão e publicação online do site.

## 🌐 Link do Site Publicado
Acesse o site publicado no GitHub Pages: [https://klebermorais.github.io/meus_sites_favoritos/](https://klebermorais.github.io/meus_sites_favoritos/)

## ⚙️ Explicação do Funcionamento do Projeto
O portfólio foi construído no formato de página única (*One-Page*) com rolagem suave (`scroll-behavior: smooth`):
1. **Menu de Navegação (`navbar`):** Fixo no topo da tela (`sticky-top`), permite acessar rapidamente qualquer seção e adapta-se automaticamente para telas menores por meio de um botão de menu responsivo.
2. **Seção de Perfil:** Apresenta minha foto vinculada diretamente ao GitHub, resumo profissional e links de acesso rápido aos projetos e ao perfil no GitHub.
3. **Seção de Projetos:** Combina um carrossel de destaques com uma grade responsiva de cards descrevendo os trabalhos realizados e as tecnologias aplicadas.
4. **Seção de Sites & Ferramentas Favoritas:** Integra os cinco sites do projeto original (Google, YouTube, GitHub, W3Schools e ChatGPT) organizados em cards responsivos com links externos.
5. **Seção de Contato:** Formulário estilizado com Bootstrap para envio de mensagens e link direto para o GitHub.

## ✨ Descrição do Recurso Novo Adicionado
Além da migração para o Bootstrap 5, foram adicionados três recursos novos em relação ao projeto básico da aula:
1. **Animações e transições (`hover`)** nos cards de projetos, nos ícones dos sites favoritos e na foto de perfil.
2. **Nova seção integrada ("Sites & Ferramentas Favoritas")** utilizando o sistema de grid de 5 colunas do Bootstrap.
3. **Efeitos visuais no Carousel**, combinando transição suave de opacidade (`carousel-fade`) com animação de zoom gradual na imagem ativa.

## 🛠️ Explicação de Como Esse Recurso foi Implementado
* **Animações de Hover:** Foi criada a classe CSS `.hover-card` com a propriedade `transition: transform 0.3s ease, box-shadow 0.3s ease`. Quando o cursor passa sobre o card (`:hover`), aplica-se `transform: translateY(-8px)` para elevá-lo, enquanto a classe `.site-icon` recebe `transform: scale(1.15) rotate(3deg)` para destacar o ícone do site.
* **Nova Seção de Sites Favoritos:** Estruturada com a classe `row-cols-lg-5` do Bootstrap 5, permitindo que os 5 cards originais fiquem alinhados lado a lado em telas grandes e se reorganizem automaticamente em colunas menores em tablets e celulares.
* **Efeitos no Carousel:** No elemento principal `#carouselProjetos`, adicionou-se a classe `carousel-fade` do Bootstrap. No CSS, a regra `.carousel-item.active img` aplica `transform: scale(1.06)` com transição de 6 segundos, criando um efeito dinâmico de movimento contínuo enquanto o slide está visível.
