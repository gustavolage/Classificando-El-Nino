# Classificando-El-Nino

Autores: Bernardo Barreto, Giovanni Silva e Gustavo Lage.
Instituto de Ciências Matemáticas e de Computação - USP (São Carlos)

Objetivo: Classificar futuros acontecimentos do evento climático El Niño.

Esse é um projeto que engloba três diferentes áreas de modelagem de dados, as redes complexas que serviu para entender o comportamento e influências dos pontos no globo e assim criar o banco de dados a ser utilizado nas modelagens de aprendizado de dados supervisionado para classificação e também previsão por séries temporais. 

Nossa iniciativa foi baseada em um artigo muito interessante que abordou bem o tema com essa proposta: Classifying El Niño-Southern Oscillation Combining Network Science and Machine Learning(https://ieeexplore.ieee.org/abstract/document/9042254).

Por meio das ferramentas presentes no campo das redes complexas, para caracterização as redes criadas, como o grau médio ⟨⟨k⟩⟩, transitividade(τ), Eigenvector centralities (Ev), e outras mais, tentamos criar um modelo de classificação que pudesse prever futuros eventos climéticos a partir da estrutura e relação das redes complexas geradas. 

Também tivemos a ideia de realizar uma abordagem diferente, utilizando a análise de séries temporais para tentar prever futuros eventos de El Niño.

O banco de dados que utilizaremos aqui, foi gerado na primeira etapa do projeto (creating_complex_networks) e consiste apenas das datas e dos ONI values observados, i.e., a temperatura média registrada para os próximos 3 meses na faixa representada acima, o calculo feito desse index para esse estudo difere um pouco do que é tido por centrais climáticas, uma vez que o intuito disto é prever futuros acontecimentos. Para exemplo, no momento em que escrevo isto, no dia 05/12/2022, o ONI value seria referente à Jan/2023, Fev/2023 e Mar/2023.

Abaixo segue um link, com o site da National Weather Service (NWS) em que é atualizado todo mês esse indicador, mas em relação aos 3 meses passados. https://origin.cpc.ncep.noaa.gov/products/analysis_monitoring/ensostuff/ONI_v5.php
