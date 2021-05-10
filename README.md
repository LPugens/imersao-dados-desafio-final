# Deep Drug-Discovery 💊
Desenvolvendo uma rede neural para insights na área de drug-discovery.

🛑 **Disclaimer para aqueles que virem este repositório fora do contexto da competição: Eu não tenho nenhuma formação na área de ciências biológicas. As análises e conclusões apresentadas devem ser consideradas com esta informação em mente**

## Origem dos Dados 🧫
Estes dados vem de um laboratório de pesquisa farmacêutica que busca identificar novos compostos (drogas) com carcterísticas celulares desejadas.

[Este arigo da Science](https://www.nature.com/articles/nrd.2017.232.pdf?origin=ppub) é uma fonte rápida e inestimável de conhecimento que traz um levantamento do estado da arte na área de drug-discovery.
![Laboratório](https://raw.githubusercontent.com/LPugens/imersao-dados-desafio-final/main/fig1_Laborat%C3%B3rio.jpg)

No [Notebook 01 - Origem dos dados](https://github.com/LPugens/imersao-dados-desafio-final/blob/main/Notebooks/01_Origem_dos_Dados.ipynb) nós temos uma análise mais detalhada da origem dos dados que nós temos disponíveis.

## Análise Quantitativa 📊
Analisamos alguns dados estatísticos e identificamos algumas anormalidades nos dados que podem impactar nos resultados obtidos.

![Correlation](https://raw.githubusercontent.com/LPugens/imersao-dados-desafio-final/main/fig4_correlation.png)

[Notebook 02 - Análise Quantitativa](https://github.com/LPugens/imersao-dados-desafio-final/blob/main/Notebooks/02_An%C3%A1lise_Quantitativa.ipynb)

## Identificação de MoAs com Deep Learning 🤖➡💊
Neste trabalho, vamos tentar explorar os dados de drug-discovery fornecidos para obter novo insights e trazer novas ferramentas computacionais para os pesquisadores desta área.

![Deep Learning](https://raw.githubusercontent.com/LPugens/imersao-dados-desafio-final/main/fig3_deep_learning.jpg)

Para isso, tento utilizar Redes Neurais - Algoritmos de Machine Learning que estão dominando todas as áreas de aplicações de IA - para identificar os MoAs através dos dados extraídos automaticamente dos experimentos (ativação genétoca e taxa de sobrevivência celular).

No notebook [Notebook 03 - Deep Learning](https://github.com/LPugens/imersao-dados-desafio-final/blob/main/Notebooks/03_DeepLearning.ipynb) são testadas desde as técnicas mais simples, técnicas com Dropout, Early Stopping e **[Debiasing](http://introtodeeplearning.com/AAAI_MitigatingAlgorithmicBias.pdf)** dos dados.

## Conclusões
A aplicação escolhida foi uma das tarefas mais desafiadoras e relevantes que pode ser extraída destes dados.

Utilizando os métodos mencionados, nenhum deles fez grande efeito nos resultado geral de acurácia, que ficou em geral em torno de 12% no conjunto de teste.

![curva de aprendizado](https://raw.githubusercontent.com/LPugens/imersao-dados-desafio-final/main/fig6_LearningCurve.jpg)

No futuro, estes resultados podem ser melhorados através de dois métodos:
1. integração de mais dados, como por exemplo a estrutura genética das drogas pode ser transformada em um embedding através de trabalhos com [este](https://arxiv.org/abs/1805.09076), que analisa as moléculas como grafos de conexão.

![molecula](https://raw.githubusercontent.com/LPugens/imersao-dados-desafio-final/main/fig7_molecule.jpg)

2. Outras técnicas de pre-processamento que se apliquem melhor ao domínio.
