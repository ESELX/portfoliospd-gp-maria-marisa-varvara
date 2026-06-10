---
title: Deadlocked
icon: lucide/box
tags: galeria
status: not-started
hero_image: attachments/hero.jpg
hero_title: Deadlocked
hero_subtitle: Marisa Filipe · 2025-26
hero_height: 80vh
hero_overlay: 0.25
hero_align: center
published: true
student_name: Marisa Filipe
student_number: "2024338"
---

# Deadlocked

Frase-conceito: Prende o cabelo como uma tranca

## Conceito

Para este projeto pensei primeiramente num acessório que me fosse útil. Rapidamente apercebi-me que faria sentido fazer um objeto para usar no cabelo. Procurei algumas inspirações e senti  que faltava algo aos acessórios de cabelo comuns. Assim, decidi juntar à minha ideia o símbolo de uma personagem de um jogo, a Deadlock. Escolhi esta personagem pelo seu poder especial, o Sonic Sensor, que funciona como um sensor que trava os inimigos. 

![](attachments/Deadlock_Artwork_Full%201.webp)

Fig. 1 - Personagem Deadlock do Valorant


![658](attachments/Sonic_Sensor.webp)

Fig. 2 - Sonic Sensor, Símbolo do Poder da Deadlock

Da mesma forma, este acessório de cabelo tem a mesma forma e elementos e necessariamente prende o cabelo para que ele não caia, o que cria uma mensagem intuitiva à função do objeto.

É importante mencionar que este projeto surgiu a partir das minhas ideias iniciais: uma máquina de costura manual que seria como desenhar mas a coser e mais tarde, a ideia de cartas de tarot impressas em 3D, o que impulsionou as possibilidades criativas, especialmente em direção à funcionalidade tridimensional.

![](attachments/sketchmc.jpg)

Fig. 3 -  Esboços da Máquina de Costura
## Tecnologias Usadas

Uma ou mais tecnologias estudadas em laboratório:

- [ ] Corte 2D (laser / vinil)
- [x] Impressão 3D
- [ ] CNC
- [ ] Micro:bit / computação física
- [ ] Outras —
## Processo

### Iteração 1 — [Sketch]

Comecei por criar um ficheiro híbrido no fusion e desenhei um círculo com um diâmetro de 7 cm ao centro no plano horizontal e outro diâmetro à volta sem medidas.

![](attachments/diametro.png)

De seguida, escolhi a medida do círculo interior até ao exterior com uma margem de 1,50 cm.

![](attachments/margem.png)

Agora que já tenho a forma principal crio a espécie de losango que está a volta deste círculo. Sendo assim, desenho primeiro uma "Conic Curve" sem uma distância exata do círculo exterior e com um ângulo da curva de 0,5 cm.

![](attachments/coniccurve.png)

![](attachments/desenhocurva.png)

Para não ter que fazer denovo em todos os lados, usei o circular pattern com para repetir esta curva como objeto quatro vezes com o center point da origin.

![374](attachments/circularpattern.png)

![](attachments/circularpattern2.png)

![](attachments/circular3.png)

Para juntar estas curvas, criei mais outra Conic Curve com 0,6 cm de  ângulo da curva conectada pelos pontos exteriores das curvas criadas anteriormente e usei mais uma vez o circular pattern.

![](attachments/coniccurve2.png)

Entertanto, queria criar os cortes interiores do símbolo e fui fazendo algumas tentativas repetidas sem qualquer tipo de medidas que fossem necessárias até acertar na distância que achava adequada.

![](attachments/tentativa1.png)

![](attachments/tentativa2.png)

![](attachments/tentativa3.png)

![](attachments/acertodaforma.png)

Após chegar à forma adequada adicionei o corte inferior, tentando seguir o formato similar do círculo exterior. Adicionei a curva com um ângulo de 0,75 cm.

![](attachments/corteinferior.png)

Conectei as partes laterais desta forma curva com um ângulo de 0,5 cm e usei o Mirror para evitar criar outra curva. Logo de seguida, uso novamente o circular pattern quatro vezes já com a forma concluída.

![](attachments/curvaconectadaajuste.png)

![](attachments/formaconcluida.png)

![](attachments/formaduplicada.png)

![](attachments/concluidosketch.png)

E assim fica concluída a parte do sketch da forma principal. 
Para fazer o outro objeto que se prende a esta forma fiz um sketch que depois foi descartado porque como eram formas simples já existiam em modo 3d. 

Sendo assim decidi mostrar na mesma esta parte do processo:

![](attachments/tentativaerro.png)

Criei um círculo de 4 cm de diâmetro.

![](attachments/te2.png)

Depois uma linha com 15 cm tangente ao círculo, mirror da linha e depois criei um círculo igual que iria deixar tangente à linha.

![](attachments/te3.png)

**O que tentei:** Para a forma principal tentei não complicar muito com formas irregulares ou assimétricas. No fundo que fosse algo intuitivo e sem muitas restrições para ser feito sendo que não exigia esses aspetos para a sua função. Tentei pensar num acessório que tivesse um conceito interessante aplicado à construção e no processo em geral. Adicionalmente tentei fazer um sketch para um objeto que era 3d mas que seria simétrico para os dois lados.

**O que aprendi:** Aprendi que por um lado fazer as coisas mais simplificadas ajuda mas cria problemas de gestão mais tarde. Em aspetos que, por exemplo, poderia ter criado a forma 3d na mesma através do sketch mas preferi evitar pela complexidade, sendo que seria só extrudir para os dois lados simetricamente. No fundo poderia ter feito uma melhor gestão de tempo para não ter que pensar tão rápido na aplicação prática deste projeto. Aprendi que também é extremamente complexo fazer formas concavas e sem partes conectadas através do esboço.

### Iteração 2 — [Modelação 3D]

Continuando pela narrativa do segundo objeto, decidi criar diretamente sem esboço: criei duas esferas com 4 cm e um tubo com 15 cm.

![](attachments/esferas.png)

![](attachments/tubo.png)

Como não tinha restrições no 3d tentei mover as esferas até estarem sobrepostas pelo tubo, ou seja, para que fiquem presas de forma segura, para quando usar o combine ficar como um objeto só sem quaisqueres gaps.

![](attachments/mover.png)

![](attachments/mover2.png)

![](attachments/mover3.png)

Com este objeto concluído, dei extrude no sketch da outra forma com 3 cm de espessura.

![](attachments/extrusao.png)

Usei o Fillet para adicionar tridimensionalidade lateral com o Radius Type em Constant e como Setback com 0,4 de Fillet e outro na parte do círculo do meio.
Adicionalmente comecei a ver como é que se iria compor os dois objetos juntos, se seriam tangentes ou com uma espécie de intersecção com o mover. É importante mencionar que cortei o segundo objeto do tubo ao meio, para poder criar simetria com o Mirror mais tarde.

![](attachments/fillet.png)

![](attachments/mover1.png)

![](attachments/montagem%20objeto.png)

![](attachments/combine.png)

Mais tarde voltei a separar os objetos porque me apercebi que teriam que ser separados para conseguir agarrar ao cabelo de forma consistente, mudei também o tamanho dos objetos para não ficar tão grande na impressão 3d e ter a certeza que seria adaptado ao cabelo. Sendo que na aplicação só tem scale sem redução com números exatos.

![](attachments/separate.png)

![](attachments/scale.png)

**O que tentei:** Tentei criar tridimensionalidade para além do extrude, senti que se ajustava mais à linguagem gráfica do símbolo se adicionasse o Fillet. Tentei criar as esferas e o tubo como forma de facilitar o processo de junção mais tarde.

**O que aprendi:** Aprendi que deveria ter feito a parte 3d do segundo objeto a partir do sketch porque até esta parte não sabia se estava simétrico, porém como mais tarde cortei o objeto ao meio e usei o Mirror já ficou simétrico. Apesar de não ter muito conhecimento sobre este tipo de acessório de cabelo ao ver os exemplos na biblioteca online do Bamboo pensei que os objetos eram colados um ao outro, por isso mais tarde tive de fazer pesquisa extra, o que teria sido desnecessário se tivesse feito pesquisa extra. Também descobri que apesar de muitos destes acessórios terem uma forma concava para se adaptar à cabeça, é extremamente difícil criar esta curva a não ser que crie o objeto no plano frontal ou use uma tool num programa de esculpir como o Blender.

### Iteração 3 — [Preparação do Ficheiro]

Começei por salvar os corpos do fusion como mesh com formato STL.

![](attachments/Captura%20de%20ecrã%202026-05-20%20200639.png)

![](attachments/Captura%20de%20ecrã%202026-05-20%20194712.png)

Porém ocorreu-me um erro na Bambu Studio, no qual as peças ficavam com 6 horas de duração não importava o tamanho que tivesse ou a complexidade do ficheiro. Por isso tive de exportar as duas peças novamente mas desta vez em formato OBJ.

![](attachments/obj.png)

Mudei também algumas definições da máquina com as instruções do professor. Inclusive o filamento da máquina sendo que queria outro em vez do que estava na máquina.

![](attachments/file.png)

![](attachments/Captura%20de%20ecrã%202026-05-20%20202025%201.png)

![](attachments/seam.png)

![](attachments/flow.png)

![](attachments/height%201.png)

![](attachments/filamento.png)

![](attachments/export.png)

Por fim exportei o Plate para a pen e inseri na máquina.

![](attachments/video3d1.mp4)
## Resultado Final

Imagens finais do objeto impresso com o fundo removido.
![620](attachments/dealockedimpresso.png)

![697](attachments/deadlockimpresso2.png)
Aplicado no cabelo:

![](attachments/acessorionocabelo2.jpg)

Este objeto foi impresso com uma costura quase invísivel (em todo o lado do objeto) em vez de só uma parte do objeto, o que contribuíu para uma textura mais áspera, que inclusive se adapta a cabelos mais escorregadios e permite uma maior adaptação sem causar desconforto.
## Reflexão

Em relação aos objetos como um todo, acho que um aspeto muito importante é o tamanho e a forma que se compõe. Acredito que faria sentido ter um tamanho mais diminuído para não ser tão pesado apesar de não cair com muita facilidade. Gostaria de ter realizado este objeto com uma concavidade para ser menos conceptual e mais funcional no quotidiano. Também teria sido interessante explorar pintar ou personalizar este objeto ou até mesmo fazer outras versões possíveis.

Acredito que correu bem e no fim até ficou bem executado. Na minha opinião, aspetos como o tamanho, o filamento, a textura e o formato intencionalmente ajustaram-se à forma que uso as coisas: no sentido em que acessórios de cabelo costumam ser desconfortáveis para mim e por este objeto ser tão grande e solto, permite um conforto incrível para espaços que não exigem muito movimento. Até mesmo a questão de ser impresso em 3d: o material contribuí para a temperatura sendo que por ser fresco ainda adiciona mais conforto ao seu uso.