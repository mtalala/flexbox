O flexbox é um módulo de layout CSS que ajuda a criar alinhamentos e redistribuir os elementos pertencentes a um contâiner.
Nesta atividade, para começar a utilizá-lo, foi necessária a seguinte propriedade:

```
display: flex;
```

Com o objetivo de atribuir a página um visual responsivo, foi utilizada uma propriedade para alinhar os elementos ao centro da tela:

```
justify-content: center;
```

Foi utilizada, com o mesmo objetivo, a propriedade "wrap" que molda os elementos na página, encaixando-os, e consequentemente mudando temporáriamente suas ordens:

```
flex-wrap: wrap;
```

Por default,a ordem dos elementos se inicia na posição (order:0), mas o design de nossa página se baseia na alternância entre imagens, então a ordem
foi alterada de forma que o elemento 1 (order:0) manteve sua posião, e o elemento 10 (order:9) se tornou o segundo elemento do contâiner.
Destaca-se uma informação importante: só é possível utilizar esta propriedade em elementos aos quais já foi dado o "display:flex;".
