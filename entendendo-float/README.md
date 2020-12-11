# Entendendo float
- Ao utilizar *float* com as prorpiedades *left* e *right*, o elemento que ganha *float* recebe **um novo contexto**.
- Em seguida ele é posicionado nesse novo contexto o máximo que conseguir para o sentido que foi passado para a propriedade *float*.
- **Novo contexto** é uma camada que fica acima da camada de origem do elemento.
- Se você tiver 4 elementos utilizando a propriedade *float*, os 4 elementos utilizarão o mesmo contexto.
- Quando um elemento recebe a propriedade *float*, ele ganha um novo contexto e não está mais no contexto do elemento pai.

## Overflow: hidden
_ A propriedade *overflow: hidden* esconde qualquer elemento filho que ultrapasse o tamanho de seu pai.
- Quando o pai não tem a altura ou largura definida, ele se preocupa em levar em consideração a altura e largura dos filhos.

## Clear: left
- A propriedade *clear* é utilizada para limpar o contexto caso tenha um elemento flutuando ao lado esquerdo, direito ou ambos.
- O elemento com *dispay: inline* ganha o **comportamento de uma palavra**
- O posicionamento pode ser alterado com a propriedade *text-align*