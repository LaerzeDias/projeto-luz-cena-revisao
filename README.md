🎬 Projeto: Luz & Cena – Landing Page de Cinema

Desenvolvimento de uma Landing Page responsiva para um cinema fictício, focada em alta performance visual e experiência do usuário (UX). O projeto simula uma interface moderna de streaming/venda de ingressos, priorizando a semântica do HTML5 e recursos modernos de CSS.

Destaques Técnicos & Soluções de Engenharia
UX Avançada com CSS Moderno: Implementação de feedbacks em tempo real na seção de Newsletter utilizando a pseudo-classe :has(), permitindo validações visuais complexas (como estados de erro e desabilitação de botões) sem a necessidade imediata de JavaScript.

Arquitetura de Layout Sticky: Desenvolvimento de um cabeçalho de navegação (cartaz__cabecalho) com position: sticky. O desafio técnico consistiu em manter o elemento fixo apenas dentro da sua seção de contexto, garantindo que o alinhamento do conteúdo respeitasse o max-width global do projeto.

Acessibilidade (A11y): Aplicação rigorosa de semântica HTML, utilizando tags como <main>, <section>, <label> e atributos ARIA (aria-live, aria-label) para garantir que a interface seja compreensível por tecnologias assistivas e leitores de tela.

Design Responsivo Intrinseco: Uso de estratégias de Flexbox e flex-basis para criar componentes que se adaptam fluidamente a diferentes tamanhos de tela (Mobile, Tablet, Desktop) com o mínimo de Media Queries possível.

Micro-interações & Polimento Visual: Implementação de efeitos de hover com pseudo-elementos (::after) para navegação e controle de interação de texto (user-select) para reforçar a imersão estética dos banners.

Tecnologias Utilizadas
HTML5 (Semântico e estrutural)

CSS3 (Variáveis, Flexbox, Sticky Positioning, Pseudo-classes modernas)

Metodologia BEM (Block Element Modifier) para organização e escalabilidade do código.