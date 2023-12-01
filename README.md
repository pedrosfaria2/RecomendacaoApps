# 📱 Análise de apps da App Store e Google Play 📱

##  Motivação
Suponhamos que nós criamos apps gratuitos para dispositivos móveis que ganham dinheiro com propagandas dentro deles. O nosso lucro depende diretamente do número de usuários que baixam e usam nossos apps. Além disso, temos um cenário no qual queremos testar o app em uma plataforma para ver se ele é viável. Se ele for bem sucedido, vamos então aprimorar mais o app e depois lançá-lo na outra plataforma. Com base nisso, é possível achar perfis de aplicativos que o público gosta e pode nos atender?

## Sobre o projeto
Neste projeto, nós usamos dados parciais das lojas de aplicativos, que foram obtidos no site [Kaggle](https://www.kaggle.com/). Você pode fazer o download dos dados [aqui](https://www.kaggle.com/datasets/ramamet4/app-store-apple-data-set-10k-apps) para a App Store e [aqui](https://www.kaggle.com/datasets/lava18/google-play-store-apps/data) para a Google Play.

Neste projeto, nós exploramos possíveis respostas para as seguintes questões:

Quais são os gêneros que têm mais aplicativos nas duas lojas?
- Nesses gêneros com mais oferta de aplicativos, quais costumam ser as preferências dos usuários?
- Que critérios podemos usar com os dados disponíveis para entendermos quais categorias os usuários gostam mais?
- Aplicativos de sucesso e de grandes empresas podem enviesar esses dados? Como eles afetam nossa análise?
- Com base nas questões anteriores, é possível fazer recomendação de perfis de aplicativos que atendem nosso cenário hipotético inicial?
- Alguma dessas recomendações era esperada? Alguma dessas recomendações não era esperada?

O projeto foi dividido em duas etapas:

### 1) Limpeza e filtragem:
Nesta etapa, nós limpamos e filtramos os dados para remover erros, duplicatas, aplicativos em outros idiomas e aplicativos pagos.

### 2) Análise dos dados:
Nesta etapa, nós analisamos os dados para entender os perfis dos aplicativos mais populares em cada loja. Nós calculamos as proporções de aplicativos por gênero e as médias de instalação e avaliação por gênero.

## Conclusão:

Neste projeto, nós investigamos e encontramos perfis de aplicativos móveis gratuitos da App Store e da Google Play que são bem aceitos pelos usuários. Nosso objetivo era auxiliar nas decisões sobre o desenvolvimento de aplicativos, levando em conta que nossa fonte de renda são propagandas dentro dos aplicativos.

Para isso, usamos dados de amostras de ambas as lojas e aplicamos técnicas de limpeza, filtragem e análise dos dados. Também usamos o sistema ASCII para lidar com caracteres especiais nos nomes dos aplicativos e calculamos a média de instalações e avaliações por gênero e categoria.

Nossas principais recomendações foram:

- Jogos: são muito populares em ambas as lojas e se encaixam no propósito de manter os usuários por muito tempo, aumentando a quantidade de anúncios exibidos. Podemos explorar diferentes gêneros e estilos de jogos, desde que sejam divertidos e envolventes.

- Livros e referências: são populares na Google Play e têm potencial na App Store. Podemos pensar em fazer uma mídia digital de alguma obra popular ou trabalhar em bibliotecas ou reprodutores de livros e audiolivros. Também podemos incluir recursos extras, como guias ou mapas para games, dicionários ou tradutores. Esses aplicativos costumam manter os usuários por bastante tempo enquanto consomem o conteúdo, gerando mais anúncios.
