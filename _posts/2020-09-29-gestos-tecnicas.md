---
layout: post
title: Gestos e técnicas de interação
subtitle: Os nomes e os conceitos
cover-img: /assets/img/img_3361_small.jpg
thumbnail-img: /assets/img/img_3361_small.jpg
share-img: /assets/img/img_3361_small.jpg
tags: [definições]
---

Ao tentar categorizar e reconhecer semelhanças e diferenças em visualizações interativas, ajuda separar dois conceitos que nem sempre são esclarecidos: *gestos* ou eventos vs. *técnicas* de interação.

### Gestos

Quando uma pessoa interage com uma visualização (ou com qualquer outra interface), ela dispõe de algumas ações que pode fazer sobre a visualização. Essas ações dependem muito da tecnologia sendo usada, mas normalmente em um desktop/laptop envolverão principalmente:

* cliques: o que você faz com cada link desse site, por exemplo;
* arrastar: o que você faz quando move uma figura em um programa de desenho, normalmente;
* brush: quando você desenha um retângulo de seleção clicando e arrastando o cursor; e
* hover/sobrevôo: quando você coloca o mouse sobre um elemento de interface e a interface responde, mesmo sem clique.

Assim como em outras interfaces, essas ações podem ser realizadas em *widgets* acessórios à visualização (sliders, botões, caixas de texto, etc.), mas aqui também podem ser realizadas *nos elementos da visualização*, como marcas, legendas, eixos e anotações. Como quando sobrevoamos uma barra e vemos um tooltip ou ela muda de cor. Ou quando clicamos em um ponto e isso destaca todos os outros pontos com a mesma cor.

### Técnicas

Repare que esses são gestos cujos eventos a interface entende, e que um mesmo gesto (clique ou sobrevôo por exemplo) pode ser usados para construir diferentes técnicas de interação. Um clique pode destacar ou esconder um ponto, ou alterar outra visão dos dados. Como construímos uma interação é o que chamaremos aqui no curso de técnica de interação.

Existem várias categorizações das técnicas mais usadas. Uma bastante clara e que usaremos aqui é a [desse artigo](https://www.cc.gatech.edu/~stasko/papers/infovis07-interaction.pdf) usado na semana 8 aqui do curso.

### Sobre outros gestos

Listamos ali em cima os gestos mais comuns de interface, mas existem muitos outros, claro. Por exemplo, é possível interagir pressionando alguma tecla no teclado. Isso não é tão comum em visualização, mas às vezes usamos as setas ou outras teclas.

Outro espaço que abre muitas possibilidades é o de visualizações em outros dispositivos. Por exemplo, o campo de visualização em telas touch (como celulares) é relativamente pouco explorado, e lá é possível capturar gestos de multi-touch e pinch, por exemplo. Ou gestos com acelerômetro e giroscópio do celular.
