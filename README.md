# Asian Soul - Restaurante Asiático Responsivo 🍣

## Sobre o Projeto

Site completo para um restaurante asiático fictício chamado "Asian Soul", apresentando culinárias do Japão, Coreia, China e Tailândia. Desenvolvido como projeto para portfólio, demonstra habilidades em:

- **Front-end moderno** com HTML5, CSS3 e JavaScript
- **Design responsivo** utilizando Bootstrap 5
- **Animações e efeitos visuais** com Intersection Observer API
- **Organização de código** modular e semântico

## Tecnologias Utilizadas

- ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)
- ![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?logo=bootstrap&logoColor=white)

## Recursos Implementados

✔️ **Navegação responsiva** com menu hamburger  
✔️ **Carrossel de imagens** automático  
✔️ **Seção de cardápio** com abas interativas  
✔️ **Formulário de contato** funcional  
✔️ **Animações suaves** ao rolar a página  
✔️ **Design temático** com cores e elementos asiáticos  
✔️ **Mapa integrado** do Google Maps  

## Destaques de Código

```javascript
// Sistema de animação ao scroll
const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.classList.add('active');
            observer.unobserve(entry.target);
        }
    });
}, { threshold: 0.1 });

document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));
```

## Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/asian-soul-restaurante.git
```

2. Abra o arquivo `index.html` no seu navegador preferido

Ou acesse: https://restaurante-asian-soul.vercel.app/

## Créditos e Agradecimentos

Este projeto contou com o suporte da IA [DeepSeek](https://www.deepseek.com) para:
- Resolução de dúvidas técnicas
- Sugestões de organização de código
- Otimização de performance
- Revisão de boas práticas

## Autor

👨‍💻 **Alex Magalhães**  
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alex-magalhaes-lkn/)

---

✨ Projeto desenvolvido com paixão pela cultura asiática e tecnologia web. Críticas e sugestões são sempre bem-vindas!
