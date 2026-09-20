# 🎬 Newflix

Projeto Web inspirado na Netflix, desenvolvido com **HTML5**, **CSS3** e **JavaScript** puro, como parte do desafio do **Bootcamp de Desenvolvedor Frontend** do **Banco Inter**.

## 📖 Sobre o projeto

O Newflix é um projeto inspirado na interface da Netflix que simula uma plataforma de streaming, contendo página inicial com catálogo de séries, filmes e documentários organizados em carrosséis, tela de login, página de informações sobre o conteúdo e página de erro. O foco do desafio foi reproduzir em boa parte a experiência visual e a responsividade da Netflix utilizando apenas tecnologias front-end básicas.

## ✨ Funcionalidades

- **Página inicial** com banner de destaque e botões de "Assistir agora" e "Mais informações"
- **Carrosséis de conteúdo** (Populares, Em alta e Gratuitos) para Séries, Filmes e Documentários, usando a biblioteca [Owl Carousel](https://owlcarousel2.github.io/OwlCarousel2/)
- **Sistema de login simulado**, que captura o e-mail digitado e exibe na navbar após a autenticação
- **Botão de logout**, que retorna o usuário ao estado deslogado
- **Página de informações** com detalhes sobre o conteúdo selecionado
- **Página de erro** amigável para simular falhas de reprodução
- **Layout responsivo**, adaptado para diferentes tamanhos de tela via media queries

## 🛠️ Tecnologias utilizadas

- **HTML5** — estruturação semântica das páginas
- **CSS3** — estilização, variáveis de cor e responsividade (media queries)
- **JavaScript** — manipulação do DOM e lógica de login/logout via query params
- **[Owl Carousel](https://owlcarousel2.github.io/OwlCarousel2/)** — carrosséis de imagens
- **[Font Awesome](https://fontawesome.com/)** — ícones

## 🚀 Como executar

Por ser um projeto estático (sem back-end), basta:

1. Clonar o repositório
   ```bash
   git clone https://github.com/seu-usuario/newflix.git
   ```
2. Entrar na pasta do projeto
   ```bash
   cd newflix
   ```
3. Abrir o arquivo `index.html` no navegador (ou usar uma extensão como o **Live Server** do VS Code)

## 🔑 Testando o login

Na página de login, digite qualquer e-mail no campo correspondente e clique em **Confirmar**. Você será redirecionado para a página inicial, onde o e-mail informado aparecerá na navbar no lugar do botão de login, junto com um botão para sair.

## 🧠 Aprendizados

Este desafio permitiu praticar:

- Estruturação de múltiplas páginas HTML com navegação entre elas
- Uso de variáveis CSS (`:root`) para manter consistência visual
- Layouts responsivos com `flexbox`, `grid` e media queries
- Integração de bibliotecas externas (Owl Carousel e Font Awesome)
- Manipulação do DOM e passagem de dados entre páginas via `URLSearchParams`

## 📌 Possíveis melhorias futuras

- [ ] Adicionar validação de campos no formulário de login
- [ ] Implementar busca de conteúdo
- [ ] Tornar o catálogo dinâmico a partir de uma API
- [ ] Adicionar modal de detalhes ao clicar em um item do carrossel
- [ ] Persistir o login com `localStorage`

## 👤 Autor

Desenvolvido como parte do **Bootcamp de Desenvolvedor Frontend do Banco Inter**.

Obrigado por chegar até aqui. Me chamo João Gabriel e sinta-se à vontade para utilizar este projeto como inspiração para o seu próprio desafio! 🚀