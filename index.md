---
title: Por que o Remix é uma aposta segura?
separator: <!-- p -->
verticalSeparator: <!-- v -->
theme: night
revealOptions:
  transition: 'concave'
---

## Remix

<!-- p -->

## Dia de tomar consciência 🤦🏻‍♀️
![Ada Lovelace](/assets/ada-lovelace.png)
<!-- v -->
![Gender percentage in tech](/assets/gender.png)
<!-- v -->
![Percentage of men in tech BR](/assets/country-gender.png)
https://2021.stateofjs.com/en-US/demographics

<!-- p -->

### Quem sou?

[@gustavoguichard](https://twitter.com/gustavoguichard)
ou simplesmente: Guga
<!-- v -->
### Vida offline 👨‍👩‍👦
![Como me defino](/assets/offline.png)

<!-- v -->
### Vida Online 🧑‍💻
#### Developer Experience Engineer [@seasoned](https://seasoned.cc)
- __P&D__
- Arquitetura, libs e tools, infra, etc
- Suporte
- Coding

<!-- p -->

### A [@seasonedcc](https://twitter.com/seasonedcc)
![Seasoned](/assets/seasoned.png)
<!-- v -->
### Patrocinadora oficial da
### [Remix Conf](https://remix.run/conf)
![Sponsors](/assets/sponsors.png)

<!-- p -->
### Para criar ferramentas úteis, temos que identificar as fontes de problemas 🔬
![#dev-help](/assets/devhelp.png)

<!-- v -->
### Depois que alguns legados foram removidos... 🗑
![Material UI](/assets/mui.png)

<!-- v -->
### A grande maioria dos problemas restantes: 🦠
- Camada de acesso a dados
- Gerenciamento de estato de Formulários
- Experiência do unhappy path

<!-- v -->
### Gargalo no front end 🍾
![Complexidade Front](/assets/complexidade-front.png)

<!-- p -->
## Como resolver a complexidade do estado de front? 👨🏽‍🚀

<!-- v -->
### Há uns anos atrás 👵🏽
![Redux Presentation](/assets/redux-presentation.png)
https://www.youtube.com/watch?v=uvAXVMwHJXU&t=7s
<!-- v -->
![Redux](/assets/redux.png)
<!-- v -->
### O que poderia dar errado? 😒
![Redux Forms](/assets/redux-forms.png)
<!-- v -->
### Pq não usamos mais Redux? 🚮
![Dan Abramov: Q](/assets/danabramov-question.png)
<!-- v -->
![Dan Abramov: A](/assets/danabramov-answer.png)
https://www.youtube.com/watch?v=XEt09iK8IXs


<!-- p -->
### E como se faz hoje em dia? 👩🏻‍🔬
![Current state management](/assets/current.png)
<!-- v -->
### Estamos contentes? 😶
![Framework satisfaction](/assets/framework-satisfaction.png)
https://2021.stateofjs.com/en-US/libraries/front-end-frameworks

<!-- v -->
### O que ainda não foi solucionado? 🕵🏽‍♀️
![Current problems](/assets/current-problems.png)

<!-- p -->
### A anatomia do stack atual 🫀
![spa-structure](/assets/spa-structure.png)
<!-- v -->
![spa-structure](/assets/spa-structure-1.png)
<!-- v -->
![spa-structure](/assets/spa-structure-2.png)
<!-- v -->
![spa-structure](/assets/spa-structure-3.png)

<!-- v -->
### Problemas da estrutura atual 😖
- Comunicação entre mundos
- Duplicação de código
- Falta de clareza sobre algumas responsabilidades
- Desenvolvimento de unhappy path
- Spinners, problemas de performance, exagero de requisições
- CORS - Cross-Origin Resource Sharing
- 2 plataformas de deploy, 2 infraestruturas
- Falhas de segurança

<!-- v -->
## Architectural Divergence ↔️
https://remix.run/blog/remix-vs-next#architectural-divergence

<!-- p -->
### Nossa aposta 🤞
![remix-structure](/assets/remix-structure.png)
<!-- v -->
![remix-arch](/assets/remix-arch.png)
<!-- v -->
### Soluções 🧞‍♀️
- Uma linguagem
- Reuso de código
- Clareza sobre responsabilidades
- Unhappy path solido "out of the box"
- Velocidade, sem disperdício de requests e payloads
- Não precisa se preocupar com CORS
- Um deploy, uma infraestrutura
- Segurança

<!-- v -->
### E mais... 🎁
- Progressive Enhancement
- Ótima experiência de desenvolvimento
- Code colocation
- Nested Router de verdade
- Domínio sobre fundamentos da Web
- Remix é a melhor ponte React Developer -> Mundo do Backend (e vice-versa)

<!-- v -->
![nested routes](/assets/nested-routes.gif)

<!-- v -->
### Todo o código que não temos que escrever ☀️
![simplicidade](/assets/leonard-thiessen.jpg)

<!-- p -->
### Nem tudo são flores 😅
- Testes
- Muitos gaps para preencher no backend
- Reforçar a tipagem "ponta a ponta"

<!-- p -->
### O que podemos esperar? 🧐
Quem é o pessoal por trás do Remix?
<!-- v -->
### [@ryanflorence](https://twitter.com/ryanflorence)
![Ryan Florence](/assets/ryan-florence.png)
https://www.youtube.com/watch?v=nVTXJyyBxQc&t=570s
<!-- v -->
### [@mjackson](https://twitter.com/mjackson)
![Michael Jackson](/assets/michael-jackson.png)
<!-- v -->
### React Training 👩‍🎓
![React Training](/assets/react-training.png)
https://reacttraining.com
<!-- v -->
### React Router 🚏
![React Router](/assets/react-router.png)
<!-- v -->
### [@kentcdodds](https://twitter.com/kentcdodds)
![Kent C Dodds](/assets/kentcdodds.png)
https://testingjavascript.com
<!-- v -->
### Testing library 🛡
![Testing library](/assets/testing-library.png)
<!-- v -->
### Browser APIs 🌐
<!-- v -->
### Tem respaldo? 🦾
- Comprometimento / Profissionalismo
- Web Standards
- Inclusão
- Os melhores recursos de aprendizado
- Testes!!!
<!-- p -->
### Obrigado 🙌
