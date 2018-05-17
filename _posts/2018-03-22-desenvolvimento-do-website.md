---
title: Desenvolvimento do Website
layout: post
date: 2018-03-22 17:42:46 +0000
figure: "/uploads/2018/03/22/work_nerd.png"
summary: Resumo de todo o trabalho feito até agora
author: Rodrigo Rosmaninho
published: false
tags:
- site
files:
- "/uploads/2018/05/17/LSDig_2017-18_TrabPrat07.pdf"
---
![](/uploads/2018/03/22/nerd_s.png)

# Motivações e Objetivos

> "Quanto às ideias o que já se tinha falado era um site cujo principal foco é mostrar os projetos do nerd. Tem que dar para por fotos dos projetos juntamente com texto. Tipo instructables talvez"
>
> -Magalhães

* Ter um lugar onde haja informação geral sobre o NeRD e os principais projetos. Pode ajudar na obtenção de novos elementos.
* Ter um lugar onde o pessoal interessado se pode ir mantendo a par dos projetos do NeRD através de posts com mais detalhe do que aquilo que é posto no facebook.

# **Planeamento e Decisões**

Apesar de podermos fazer o que nos foi proposto apenas com o Wordpress ou tecnologias do género, achamos que era mais interessante não facilitar tanto o trabalho. Podíamos fazer algo mais interessante e aprender a fazer sites em condições no processo.

No entanto, também não queremos que seja tudo muito complicado e que tenhamos que 'reinventar a roda' constantemente.

Após a maioria do site ter sido pensado e desenvolvido com uma framework baseada em python (Django), foi descoberta uma alternativa melhor e o site foi, portanto, adaptado.

### Jekyll

[https://github.com/jekyll/jekyll](https://github.com/jekyll/jekyll)

O jekyll é um sistema open-source que permite, de forma simples, a gestão de blogs.

A sua principal vantagem é permitir converter toda a funcionalidade do blog em ficheiros estáticos, possibilitando assim a hospedagem do website sem custos no **Github Pages** ou serviços semelhantes .

Novos posts são escritos em formato **markdown** e adicionados através de commits de git.

No entanto, como o objetivo é que qualquer membro do NeRD possa adicionar um novo post, é importante ter um editor que não obrigue as pessoas a saber markdown.

Como tal, foi adicionada uma página de administração que redireciona para um editor de markdown porreiro ( que primeiro pede login).

[nerd-aettua.github.io/admin/](https://nerd-aettua.github.io/admin/)

# Trabalho Pendente

* Implementação de filtração de posts por tags / categorias (função nativa do jekyll) ----> R. Rosmaninho
* Documentação do projeto ----> R. Rosmaninho


* Pensar no conteúdo que é importante ter nas páginas que estão incompletas (index.html, about.html, contacts.html) ----> J. Alegria
* Implementar  o tal conteúdo ----> Tomás Martins