# Modelo híbrido de aprendizado de máquina para extração de características em imagens de radiografia de tórax

## Abstract
O diagnóstico de doenças com imagens e auxílio de sistemas computacionais de Inteligência Artificial vêm sendo desenvolvidos e aplicados em vários contextos clínicos. A Indústria 4.0 tem um papel fundamental nesse processo, pesquisas recentes demostram que transferência de aprendizado de redes neurais convolucionais pré-treinadas como ResNet-50, VGG-16 e Inception podem contribuir significamente no resultado das predições para classificação de imagens. Contudo, na maioria das vezes o treinamento de redes neurais requer um custo computacional considerável. Este artigo propõe aplicar um método rápido e eficiente baseado em algoritmos de aprendizado de máquina para modelagem preditiva de imagens de radiogradia de tórax de pacientes saudaveis e com pneumonia. O trabalho consiste em aplicar a ResNet-50 para extração de características, posteriormente reduzir a dimenssão das variáveis preditoras com análise de componentes principais e aplicar o modelo Random Forest para classifcar as imagens. Algoritmos genéticos foram utilizados para otimizar os parâmetros do modelo. Os resultados dessa metodologia permitiu alcançar valores de desempenho comparáveis aos adotados por arquiteturas robustas de redes neurais. O classificador Random Forest alcançou 93\%, 79\%, 88\% de ROC-AUC nos conjuntos de treino, teste e validação, respectivamente

## How to cite
OLIVEIRA, R. M. A. ; FIGUEIREDO, C. R. ; FARIAS, P. C. M. A. ; SANT?ANNA, ÂNGELO M. O. . Modelo híbrido de aprendizado de máquina para extração de características em imagens de radiografia de tórax. In: XVI Brazilian Congress on Computational Intelligence, 2023, Salvador. CBIC23. São Paulo: SBIC, 2023. v. 1. p. 1-8

# Dataset
Kermany, Daniel; Zhang, Kang; Goldbaum, Michael (2018), “Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification”, Mendeley Data, V2, doi: 10.17632/rscbjbr9sj.2.

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
