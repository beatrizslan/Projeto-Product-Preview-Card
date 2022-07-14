# Frontend Mentor - Projeto Product Preview Card Component

Minha solução de codificação do desafio proposto pelo Frontend Mentor, utilizando o design do projeto [Product Preview Card Component](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Indíce

Visão Geral | [Desafio](#desafio) | [Screenshot](#screenshot) | [Links](#links)
---|---|---|---

Meu Processo | [Construído com](#construído-com) | [O que eu aprendi](#o-que-eu-aprendi) | [Recursos úteis](#recursos-úteis)
---|---|---|---

Considerações Finais | [Autor](#autor) | [Agradecimentos](#agradecimentos)
---|---|---

## Visão Geral

### Desafio

O desafio foi construir este projeto e fazê-lo parecer o mais próximo possível do design. Os usuários devem ser capazes de:

- Vizualizar o layout ideal tanto para dispositivos mobiles quanto para desktops;
- Vizualizar os estados de foco para elementos interativos. 

### Screenshot

![Projeto Product Preview](https://user-images.githubusercontent.com/105252003/178893023-a868b572-df8b-46dd-8cd6-13e5bd71925f.jpg)

### Links

- URL da solução: [Index]([https://your-solution-url.com](https://github.com/beatrizslan/Projeto-Product-Preview-Card/blob/main/docs/index.html))
- URL do site: [Site](https://your-live-site-url.com)

## Meu processo

### Construído com

- HTML5 com tags semânticas;
- Propriedades personalizadas de CSS;
- Flexbox;
- Mobile-first.

### O que eu aprendi

- Entender a funcionalidade das tags picture e source para imagens flexíveis;
- Importar fontes externas;
- Utilizar variáveis no CSS;
- Trabalhar com o flexbox;
- Desenvolver uma página responsiva, começando pelo mobile-first.

```HTML
<picture>
  <source media="(min-width:720px)" srcset="images/image-product-desktop.jpg" type="image/jpg">
  <img src="images/image-product-mobile.jpg" alt="Perfume Gabrielle Essence">
</picture>
```

```CSS
@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,700&family=Montserrat:wght@500;700&display=swap');
  
:root {
  --cream: hsl(30, 38%, 92%);
}

body {
  background: var(--cream);
}

.card__content {
  display: flex;
  flex-direction: column;
  gap: 1.5em;
}
  
@media screen and (min-width:720px) {}
```

### Recursos úteis

- [Guia Completo do Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Este é um artigo incrível que me ajudou a entender melhor de como funciona o Flexbox e quais são suas propriedades. 
- [Media Queries](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/) - Este é um outro artigo do mesmo autor que também foi muito importante para eu ter uma melhor noção sobre as dimensões de telas dos dispositivos móveis.
  

## Considerações Finais

### Autor

- Website - [Beatriz Slan](https://www.your-site.com)
- Frontend Mentor - [@beatrizslan](https://www.frontendmentor.io/profile/beatrizslan)
- Linkedin - [in/beatriz-slan](https://www.linkedin.com/in/beatriz-slan-2324a4173/)


### Agradecimentos

Gostaria de agradecer a toda equipe envolvida do Frontend Mentor, por nos proporcionar tantos projetos reais e profissionais que nos ajudam muito a praticar e aprimorar todo nosso conhecimento deste mundo incrível do Front-end.  
