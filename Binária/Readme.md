# Redes Neurais artificiais: Classificação binária
## Projeto: Identificação de tumores de câncer


### Problema

Esse projeto tem como objetivo realizar uma classificação binária de um diagnóstico médico, se o tumor é cancerígeno ou não. Temos como base de treinamento um dataframe com 30 aspectos de tumores e seus respectivos resultados. Com isso somos capazes de determinar a partir de uma entrada se o tumor é benigno ou não.

### Arquivos

Treinamento da rede neural com divisão da base entre treinamento e testes

    breast_cancer_simple.py

Treinamento da rede neural cruzada, onde todos os dados são treinados e testados

    breast_cancer_crusade.py

Trienamento para encontrar os melhores parâmetros

    breast_cancer_tuning.py

Treinamento cruzado com os melhores parâmetros encontrados

    breast_cancer_melhor_configuracao.py

Salvando a rede neural com os pesos e bias ajustados

    breast_cancer_salvar.py

Carregando o treinamento da base

    breast_cancer_carregar.py

Verificação da base para um registro externo a base

    breast_cancer_um_registro.py
