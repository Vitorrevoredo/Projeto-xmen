# Projeto de Seleção de Personagens - X-Men

Este projeto foi desenvolvido para exibir uma lista de personagens do universo X-Men, onde o usuário pode interagir com a interface para selecionar um personagem e visualizar suas informações detalhadas. O layout é responsivo e adapta-se a diferentes tamanhos de tela. O projeto utiliza HTML, CSS e JavaScript para criar uma experiência interativa.

## Funcionalidade

A página contém uma lista de personagens, cada um com uma imagem e uma breve descrição. Ao passar o mouse sobre um personagem, ele é destacado e suas informações são exibidas de forma detalhada em uma área de seleção. 

### Interatividade com JavaScript

O arquivo `index.js` adiciona a interatividade da página:

- **Seleção de Personagem**: Ao passar o mouse sobre qualquer personagem, ele é destacado com uma borda azul (classe `selecionado`), e as informações relacionadas a esse personagem são atualizadas na área ao lado.
- **Imagem e Descrição**: A imagem do personagem selecionado é atualizada para uma versão maior, e o nome e a descrição do personagem são exibidos na área de detalhes.
- **Desempenho Responsivo**: A página automaticamente faz o scroll para o topo ao visualizar os personagens em dispositivos móveis (quando a largura da tela é menor que 450px).
