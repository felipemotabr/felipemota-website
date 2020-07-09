---
date: 2020-07-08
title: Hello, World!
author: Felipe Mota
excerpt: É com a popular frase de início de uma aplicação que começo esse post.

---
É com essa popular frase de teste de linguagem de programação que começo esse post..

A nova versão do meu site foi projetado com as mais recentes tecnologias de mercado e vou explicar brevemente cada uma delas aqui.

O framework necessário para rodar essa aplicação foi o Vue.js, porém uso [Gridsome](https://gridsome.org/), uma Jamstack que facilita o desenvolvimento e a curva de aprendizagem é mínima. Os benefícios de usar uma Jamstack são desempenho melhor, mais seguro, o custo da aplicação relativamente é muito mais barato (ou no meu caso nem existe), desenvolvimento ágil e ainda permite escalabilidade.

> "Uma arquitetura moderna de desenvolvimento web baseada em JavaScript do lado do cliente, APIs reutilizáveis ​​e marcação pré-criada"
>
> \- Mathias Biilmann (CEO e cofundador da Netlify).


![](/uploads/forestry-screenshot.PNG)


Para gerenciar todo o conteúdo das páginas, tais como edição de posts e projetos, faço uso do [Forestry](https://forestry.io/). Sempre que eu faço uma nova alteração no conteúdo, o site gera uma nova compilação estática no servidor. O Forestry tem no seu editor, linguagem de marcação **Markdown**, baseado em Git. 

Pra finalizar esse combo, entra o [Netlify](https://www.netlify.com/), que trabalha com integração contínua usando git. Todas as vezes que faço alteração nessa aplicação na branch de produção ou insiro um novo conteúdo pelo Forestry, graças a integração continua o deploy é feito automaticamente. O legal que a Netlify já estar preparada para o combo Jamstack.

Ficou interessado nisso tudo e gostaria de explorar melhor? Você pode [clonar esse site](https://github.com/felipemotabr/felipemota-website) e estudar mais a respeito.