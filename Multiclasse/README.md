# Redes Neurais artificiais: Classificação multiclasse
## Projeto: Identificação de Íris

<p align="center">
    <img src="./imagens/Flores_de_Íris.png" width="600px">
</p>


### Problema

Esse projeto tem como objetivo realizar uma classificação multiclasse de uma base de flores, temos 3 tipos de resultados possíveis que são: Íris Setosa, Íris virginica, Íris versicolor. Temos como base de treinamento um dataframe com 4 aspectos da flor e seus respectivos resultados. Com isso somos capazes de treinar a rede neural.

### Arquivos

Treinamento da rede neural com divisão da base entre treinamento e testes

    iris_simple.py

Treinamento da rede neural cruzada, onde todos os dados são treinados e testados

    iris_crusade.py

Treinamento para encontrar os melhores parâmetros

    iris_tuning.py

Salvando, carregando e testando a rede neural com um parâmetro externo 

    iris_salvar_carregar_classificar.py
