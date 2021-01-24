# Análise de preços de casas

A análise exploratória dos dados está sendo feita com base no curso [Python do Zero ao DS](https://www.youtube.com/playlist?list=PLZlkyCIi8bMprZgBsFopRQMG_Kj1IA1WG), ministrado pelo cientista de dados [Meigarom Lopes](https://br.linkedin.com/in/meigarom).

Os dados podem ser encontrados [neste link](https://www.kaggle.com/harlfoxem/housesalesprediction) e dizem respeito aos preços das casas de King County nos Estados Unidos entre os anos de 2014 e 2015.

<p><center><img width=500 src="https://image.freepik.com/vetores-gratis/agencia-imobiliaria-fluxograma-isometrico-e-clientes-casas-para-venda-e-aluguel-de-ilustracao-vetorial_1284-30401.jpg"></center>
<small><center><a href="https://br.freepik.com/vetores/projeto">Projeto vetor criado por macrovector - br.freepik.com</a></center></small></p>

## Problema de negócio

A House Rocket é uma plataforma digital que tem como modelo de negócio, a compra e a venda de imóveis usando tecnologia.

Você é um Data Scientist contrato pela empresa para ajudar a encontrar as melhores oportunidades de negócio no mercado de imóveis. O CEO da House Rocket gostaria de maximizar a receita da empresa encontrando boas oportunidades de negócio.

Sua principal estratégia é comprar boas casas em ótimas localizações com preços baixos e depois revendê-las posteriormente à preços mais altos. Quanto maior a diferença entre a compra e a venda, maior o lucro da empresa e portanto maior sua receita.

Entretanto, as casas possuem muitos atributos que as tornam mais ou menos atrativas aos compradores e vendedores e a localização e o período do ano também podem influenciar os preços.

A explicação completa pode ser encontrada no site [Seja um Data Scientist](https://sejaumdatascientist.com/os-5-projetos-de-data-science-que-fara-o-recrutador-olhar-para-voce/).

## Dicionários das variáveis
- `id` - número de identificação do imóvel
- `date` - data de venda do imóvel
- `price` - preço de venda do imóvel
- `bedrooms` - número de quartos
- `bathrooms` - número de banheiros, sendo 0.5 referente aos banheiros sem chuveiro (lavabo)
- `sqft_living` - metragem (em pé quadrado) da área interna do imóvel
- `sqft_lot` - metragem (em pé quadrado) do terreno
- `floors` - número de andares
- `waterfront` - se o imóvel tem vista para o mar (0: não, 1: sim)
- `view` - diz respeito à qualidade da vista do imóvel (0 a 4)
- `condition` - diz respeito à condição do imóvel (1 a 5)
- `grade` - trata da construção e design do imóvel (1-3: baixa qualidade, 7: qualidade média, 11-13: alta qualidade)
- `sqft_above` - metragem (em pé quadrado) do espaço interno que está acima do nível do solo
- `sqft_basement` - metragem (em pé quadrado) do espaço interno que está abaixo do nível do solo
- `yr_built` - ano de construção do imóvel
- `yr_renovated` - ano de reforma do imóvel
- `zipcode` - CEP do imóvel
- `lat` - latitude
- `long` - longitude
- `sqft_living15` - média da metragem (em pé quadrado) da área interna do imóvel dos 15 vizinhos mais próximos
- `sqft_lot15` - média da metragem (em pé quadrado) do terreno dos 15 vizinhos mais próximos
