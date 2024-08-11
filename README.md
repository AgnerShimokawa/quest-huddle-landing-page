## Tabela de Conteúdo

- [Visão Geral](#visao-geral)
  - [O Desafio](#o-desafio)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Meu Processo](#meu-processo)
  - [Built with](#built-with)
  - [O que aprendi](#o-que-aprendi)


## <h2 id="visao-geral">Visão Geral</h2>

### <h3 id="o-desafio">O Desafio</h3>

O desafio foi criar uma página com header, body e footer utilizando o flex que fosse responsivo, tendo um layout diferente para desktop e mobile.

### Screenshot

Versão Desktop 1920x1080
![](./src/design/Screenshot%202024-08-11%20234421.png)
Versão Mobile 375x685

![](./src/design/Screenshot%202024-08-12%20000219.png)

### Links

- URL da solução no GitHUb: [Link GitHub](https://github.com/AgnerShimokawa/quest-huddle-landing-page)
- URL do site live: [Link do site](https://agnershimokawa.github.io/quest-huddle-landing-page/)

## <h2 id="meu-processo">Meu Processo</h2>

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### <h3 id="o-que-aprendi">O que aprendi</h3>

Nesse projeto aprendi que para usar o PerfectPixel, é necessário usar a mesma resolução em que a imagem foi crriada para ter medidas mais exatas. Como minha resolução por padrão é de 1920x1080, não conseguia acertar as medidas na hora de criar, então tive que mudar a resolução para 1440x900. No entanto, como não pude terminar o projeto em um dia, e acabei voltando a resolução para o padrão, quando voltei a trabalhar no projeto, continuei tirando as medidas com a resolução errada, deixando tudo desequilibrado, quando percebi e mudei a resolução, o progresso que tinha feito estava todo descentralizado. Com isso resolvi fazer o projeto praticamente a olho e usando porcentagem para que os elementos se ajustassem com o tamanho da tela.

Outra coisa foi, como deixar o tamanho das fontes relativas ao tamanho ou resolução da tela, usando:

```css
.main .main-container .main-text h2 {
   font-size: calc(1.7vw + 1.7vh);
}
```

Com isso o tamanho da fonte é calculado de acordo com o viewport da tela. Isso foi muito útil uma vez que inicialmente, a imagem era responsiva, diminuindo o tamanho conforme a tela fosse diminuindo, e os texto não, isso criava um desequilibro na tela como um todo, e gerava side scrolls desnecessários.
Porém o grau, ou velocidade com que a imagem e os textos diminuíam não era rápido o bastante para deixar a página responsiva em todos os tamanhos, com isso foi necessário criar algumas media queries a mais, fazendo ajustes para que a página pudesse ser visualemnte agradável com qualquer resolução.

Foi um projeto um pouco complexo no sentido de responsividade com qualquer resolução, o momento em que algo ficava estranho ao ir diminuindo a tela chegava a ser frustante, porém lembrando tudo que já foi ensinado, voltando nos resumos, e pesquisando "será que dá pra fazer isso?", ajudou muito para que conseguisse o resultado final. É provável que a solução para esse desafio seja algo muito mais simples, mas esse foi o jeito "mais fácil" que encontrei para resolver.
