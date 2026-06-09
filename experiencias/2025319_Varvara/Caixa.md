---
title: Caixa
icon: lucide/box
tags: galeria
status: not-started
hero_image: attachments/hero.jpg
hero_title: Caixa
hero_subtitle: Varvara Pertseva · 2025-26
hero_height: 80vh
hero_overlay: 0.25
hero_align: center
published: true
student_name: Varvara Pertseva
student_number: "2025319"
---

# Optimizar o espaço de armazenamento

Frase-conceito: criar mais espaço para guardar objetos e otimizar a organização do espaço.

## Conceito

Há já algum tempo que desejava recriar um jogo de mesa que só fosse possível jogar num videojogo. E como o elemento mais importante desse jogo era um tabuleiro específico, desejei recriá-lo de uma forma que fosse fácil de transportar.
## Tecnologias Usadas

Uma ou mais tecnologias estudadas em laboratório:

- [ ] Corte 2D (laser / vinil)
- [x] Impressão 3D
- [ ] CNC
- [ ] Micro:bit / computação física
- [ ] Outras —

## Processo

### Iteração 1 — [Sketch]

**O que tentei:** Inicialmente, tinha muitos ângulos agudos, mas suavizei muitos deles, pois isso facilitou a impressão pela máquina.

Comecei pela parte inferior; como estou a fazer uma caixa, a forma é simples: basta criar várias caixas e retângulos com a forma desejada. É importante alisar as arestas, se possível, pois isso torna a estrutura mais resistente para a máquina.

Vou usar este mesmo esboço tanto para a parte inferior como para a parte superior da caixa.

**O que aprendi:** eficiência.

![](attachments/box%20sketch.png)

### Iteração 2 — [Autodesk Fusion]

Utilizei o Fusion 360 para criar o meu modelo, começando pelo esboço,

Gostaria de salientar que defini os parâmetros de tamanho antecipadamente, uma vez que pretendo que os dados caibam nos recortes quadrados mais pequenos. Assim, no meu caso, baseei todas as dimensões no facto de os quadrados pequenos terem de ter 17 mm, tendo tudo o resto sido adaptado a essa condição. Também anotei as dimensões de tudo em papel, para utilizar na segunda peça no futuro.

É muito importante ter as dimensões corretas, uma vez que fiz três tentativas antes de a impressora ter concluído o meu trabalho; as duas primeiras ficaram demasiado grandes e a terceira não imprimiu corretamente desde o início, pelo que tive de a tornar ainda mais pequena.

![](attachments/box%20bottom.png)

Como referi anteriormente, utilizei o mesmo esboço para ambas as peças, mas, neste caso, optei por extrudir os quadrados mais pequenos ao longo da plataforma principal, uma vez que não é necessário que estejam presentes em ambos os lados. Também extrudi as pequenas saliências que servem para fixar a caixa no lugar.

![](attachments/box%20top.png)

### Iteração 3 — [Bambu Studio]

O passo seguinte é a impressão propriamente dita; utilizei o «BambuStudio» com a «Bambu Lab A1 Mini». E utilizei filamento transparente. As configurações predefinidas do programa são mais do que adequadas para o meu projeto, por isso não alterei nada.

A partir daí, imprimi a base e a parte superior separadamente em duas sessões; felizmente para mim, tudo correu bem. 

![](attachments/box%20print.png)

## Resultado Final

Este é o aspeto final do objeto;
Tem uma parte superior e uma parte inferior, que se encaixam para ficarem no lugar. A caixa tem capacidade para até 18 dados, uma vez que essa é a quantidade necessária para o jogo.

![](attachments/box%20final.jpg)

## Reflexão

Na próxima iteração, dedicaria mais tempo a definir as dimensões de todas as peças, uma vez que, inicialmente, a caixa não conseguia fechar porque as saliências e os orifícios correspondentes tinham dimensões demasiado próximas.