# Série Superman & Lois

Este projeto, foi desenvolvido a partir de um exercício solicitadona plataforma [DevMedia](https://www.devmedia.com.br/) na [5° missão](https://www.devmedia.com.br/view/viewaula.php?idcomp=43350) da carreira **[front-end](https://www.devmedia.com.br/carreira-programador/?slug=front-end)** . O objetivo era desenvolver uma página *HTML* com estilização em *CSS*, focando principlamente em adquirir prática na aplicação de [Valores relativos](https://www.devmedia.com.br/view/viewaula.php?idcomp=43343), [min-... e max-...](https://www.devmedia.com.br/view/viewaula.php?idcomp=43344), [Overflow](https://www.devmedia.com.br/view/viewaula.php?idcomp=43345), [Display, Opacity e Visibity](https://www.devmedia.com.br/view/viewaula.php?idcomp=43346), [Box-Sizing](https://www.devmedia.com.br/view/viewaula.php?idcomp=43347), [Box-Shadow](https://www.devmedia.com.br/view/viewaula.php?idcomp=43348)  em *CSS*. Tud isso foi estudado em [Caixas (BoxModel)](https://www.devmedia.com.br/view/viewaula.php?idcomp=43342).

## Escopo do Projeto
A rede de Streaming [HBO Max](https://www.hbomax.com/), contratou a [DevMedia](https://www.devmedia.com.br/) para desenvolver uma página simples que divulgasse a série **Superman & Lois** e eu como Desenvolvedor Front-End Júnior, fui designado para realizar está tarefa.

## Layout do Projeto
**Layout**
![Layout](https://github.com/wesleyaguiarlopes/05-missao-serie-superman-e-lois-devmedia/blob/main/layout/layout-05-missao-serie-superman-e-lois-devmedia.jpeg)

**Layout Animado**
![Layout Animado](https://github.com/wesleyaguiarlopes/05-missao-serie-superman-e-lois-devmedia/blob/main/layout/layout-05-missao-serie-superman-e-lois-devmedia.gif)

## Mais sobre o projeto

O projeto completo, pode ser acessado através dete link [Série Superman & Lois](https://www.devmedia.com.br/view/viewaula.php?idcomp=43350)

## Sobre as propriedades

~~~CSS
    elemento {
        /* Largura e altura máxima e minima */
        min-width: 500px;
        min-height: 1024px;
        max-width: 1024px;
        max-height: 2048px;

        /* Valores relativos */
        100% - de algo
        60vw - 60% da largura da ViewPort
        89vh - 89% da altura da ViewPort
        width: calc(100% - 40px);

        /* Barra de rolagem, para quando o elemento transboarda */
        overflow: scroll;
        overflow: auto;
        overflow-y: scroll;
        overflow-x: auto;

        /* Comportamento do elemento */
        display: block;
        display: inline;
        display: flex;

        /* Ocultar elementos */
        display: none; /* Libera o espaço */
        visibility: hidden; /* Oculta, mantendo o espaço */
        
        /* transparência do elemento */
        opacity: 60%;

        /* Considerar dimensionamento com base no conteúdo*/
        box-sizing: content-box;
        /* A caixa é fixa */
        box-sizing: border-box;

        /* Sombra */
        box-shadow: 10px 10px 5px 8px #cecece inset
    }
~~~