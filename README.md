# Frontend Mentor - Solução do Projeto Product Preview Card Component

Esta é minha solução de codificação do desafio proposto pelo Frontend Mentor, utilizando o design do projeto [Product Preview Card Component](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Indíce

- [Visão Geral](#overview)
  - [Desafio](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Meu processo](#my-process)
  - [Construído com](#built-with)
  - [O que eu aprendi](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Visão Geral

### Desafio

O desafio foi construir este projeto e fazê-lo parecer o mais próximo possível do design. Os usuários devem ser capazes de:

- Vizualizar o layout ideal tanto para dispositivos mobiles quanto para desktops;
- Vizualizar os estados de foco para elementos interativos. 

### Screenshot

![](./screenshot.jpg)

### Links

- URL da solução: [Add solution URL here](https://your-solution-url.com)
- URL do site: [Add live site URL here](https://your-live-site-url.com)

## Meu processo

### Construído com

- HTML5 com Tags Semânticas
- Propriedades personalizadas de CSS
- Flexbox
- Mobile-first

### O que eu aprendi

- Entender a funcionalidade das tags <picture> e <source> para imagens flexíveis;
- Importar fontes externas;
- Utilizar variáveis no CSS;
- Trabalhar com o Flexbox;
- Desenvolver uma página responsiva, começando pelo mobile-first.


```HTML
<picture class="card__picture">
  <source media="(min-width:720px)" srcset="images/image-product-desktop.jpg" type="image/jpg" class="card__picture__desktop">
  <img src="images/image-product-mobile.jpg" alt="Perfume Gabrielle Essence" class="card__picture__mobile">
</picture>
```

```CSS @import
@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,700&family=Montserrat:wght@500;700&display=swap');
```

```CSS Variáveis
:root {
  --cream: hsl(30, 38%, 92%);
}

body {
  background: var(--cream);
}
```

```CSS Flexbox
.card__content {
  display: flex;
  flex-direction: column;
  gap: 1.5em;
  padding: 1.5rem 2rem;
}
```

```CSS Media Queries
@media screen and (min-width:720px) {

}
```

### Recursos úteis

- [Guia Completo do Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Este é um artigo incrível que me ajudou a entender melhor de como funciona o Flexbox e quais são suas propriedades. 
- [Media Queries](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/) - Este é um outro artigo do mesmo autor que também foi muito importante para eu ter uma melhor noção sobre as dimensões de telas dos dispositivos. 

## Autor

- Website - [Beatriz Slan](https://www.your-site.com)
- Frontend Mentor - [@beatrizslan](https://www.frontendmentor.io/profile/beatrizslan)
- Linkedin - [in/beatriz-slan](https://www.linkedin.com/in/beatriz-slan-2324a4173/)


## Agradecimentos

Gostaria de agradecer a toda equipe envolvida do Frontend Mentor, por nos proporcionar tantos projetos reais e profissionais que nos ajudam muito a praticar e aprimorar todo nosso conhecimento deste mundo incrível do Front-end.  
