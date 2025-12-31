# 🎬 Luz & Cena - Cinema Experience

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

> Landing page moderna para um cinema fictício, focada em performance visual, semântica e experiência do usuário.

## 🚀 Sobre o Projeto

O **Luz & Cena** foi desenvolvido como um desafio técnico para aplicar as funcionalidades mais modernas do CSS3 e as melhores práticas de HTML5. O objetivo principal foi criar uma interface imersiva que se comporta como uma aplicação real, tratando desde a acessibilidade até animações complexas dirigidas pelo scroll.

---

## 🛠️ Destaques Técnicos

### 🧪 CSS Moderno & Validação Nativa
Utilização da pseudo-classe `:has()` para realizar validações de formulário complexas sem JavaScript. 
* O botão de inscrição da Newsletter entra em estado *disabled* visual e a mensagem de erro é disparada automaticamente com base na validade do e-mail.

### 📍 Sticky Contextual
Implementação de um cabeçalho de categorias (`Em cartaz` / `Em breve`) utilizando `position: sticky`. 
* O elemento permanece fixo no topo apenas enquanto o usuário navega pela seção de filmes, respeitando o limite do container pai.

### 🎭 Scroll-Driven Animations
Uso de `view-timeline` e `animation-range` para revelar títulos e elementos conforme entram no campo de visão do usuário, criando uma nave
