# ProjetoAirbnbRio

<div>
<img src="http://img.shields.io/static/v1?label=STATUS&message=%20FINALIZADO&color=GREEN&style=for-the-badge"/>
</div>
<div>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/f06aea2585a5ebb7c97ff88c1e3ec42fe92502fbd897abe4bf2e56eb7039e1aa/68747470733a2f2f63646e2e69636f6e2d69636f6e732e636f6d2f69636f6e73322f3131322f504e472f3531322f707974686f6e5f31383839342e706e67"><img src="https://camo.githubusercontent.com/f06aea2585a5ebb7c97ff88c1e3ec42fe92502fbd897abe4bf2e56eb7039e1aa/68747470733a2f2f63646e2e69636f6e2d69636f6e732e636f6d2f69636f6e73322f3131322f504e472f3531322f707974686f6e5f31383839342e706e67" alt="python" width="40" height="40" data-canonical-src="https://cdn.icon-icons.com/icons2/112/PNG/512/python_18894.png" style="max-width: 100%;"></a></p>
</div>

### Ferramenta de Previsão de Preço de Imóvel para pessoas comuns.
### Contexto

No Airbnb, qualquer pessoa que tenha um quarto ou um imóvel de qualquer tipo (apartamento, casa, chalé, pousada, etc.) pode ofertar o seu imóvel para ser alugado por diária.

Você cria o seu perfil de host (pessoa que disponibiliza um imóvel para aluguel por diária) e cria o anúncio do seu imóvel.

Nesse anúncio, o host deve descrever as características do imóvel da forma mais completa possível, de forma a ajudar os locadores/viajantes a escolherem o melhor imóvel para eles (e de forma a tornar o seu anúncio mais atrativo)

Existem dezenas de personalizações possíveis no seu anúncio, desde quantidade mínima de diária, preço, quantidade de quartos, até regras de cancelamento, taxa extra para hóspedes extras, exigência de verificação de identidade do locador, etc.

### Nosso objetivo

Construir um modelo de previsão de preço que permita uma pessoa comum que possui um imóvel possa saber quanto deve cobrar pela diária do seu imóvel.

Ou ainda, para o locador comum, dado o imóvel que ele está buscando, ajudar a saber se aquele imóvel está com preço atrativo (abaixo da média para imóveis com as mesmas características) ou não.

### O que temos disponível, inspirações e créditos

As bases de dados foram retiradas do site kaggle: https://www.kaggle.com/allanbruno/airbnb-rio-de-janeiro

Elas estão disponíveis para download abaixo da aula (se você puxar os dados direto do Kaggle pode ser que encontre resultados diferentes dos meus, afinal as bases de dados podem ter sido atualizadas).

Caso queira uma outra solução, podemos olhar como referência a solução do usuário Allan Bruno do kaggle no Notebook: https://www.kaggle.com/allanbruno/helping-regular-people-price-listings-on-airbnb

Você vai perceber semelhanças entre a solução que vamos desenvolver aqui e a dele, mas também algumas diferenças significativas no processo de construção do projeto.

- As bases de dados são os preços dos imóveis obtidos e suas respectivas características em cada mês.
- Os preços são dados em reais (R$)
- Temos bases de abril de 2018 a maio de 2020, com exceção de junho de 2018 que não possui base de dados

### Expectativas Iniciais

- Acredito que a sazonalidade pode ser um fator importante, visto que meses como dezembro costumam ser bem caros no RJ
- A localização do imóvel deve fazer muita diferença no preço, já que no Rio de Janeiro a localização pode mudar completamente as características do lugar (segurança, beleza natural, pontos turísticos)
- Adicionais/Comodidades podem ter um impacto significativo, visto que temos muitos prédios e casas antigos no Rio de Janeiro

Vamos descobrir o quanto esses fatores impactam e se temos outros fatores não tão intuitivos que são extremamente importantes.


<div>
<p>Confira o passo a passo do codigo em <a href="https://github.com/Rafael-Lee1/ProjetoAirbnbRio.git" target="_blank" rel="noopener noreferrer">Solução Airbnb Rio.py</a>.</p>
</div>



