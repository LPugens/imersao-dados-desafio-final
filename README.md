# Deep Drug-Discovery 💊
Developing a neural network for insights in the drug-discovery field.

🛑 **Disclaimer:** I am in no way, shape, or form, an specialist in drug-discovery. I am only exploring this drug-discovery dataset.

## Data Source 🧫
This dataset comes from an pharmaceutic research lab. It represents an atempt to identify new drug compounds with the desired organic effects.

[Este arigo da Science](https://www.nature.com/articles/nrd.2017.232.pdf?origin=ppub) is an great source of state-of-the-art research in drug-discovery.
![Laboratório](https://raw.githubusercontent.com/LPugens/imersao-dados-desafio-final/main/fig1_Laborat%C3%B3rio.jpg)

In [Notebook 01 - Data source](https://github.com/LPugens/imersao-dados-desafio-final/blob/main/Notebooks/01_Origem_dos_Dados.ipynb) we have a detailed analysis of the dataset origin.

## Quantitative Analysis 📊
We have analysed some statistical data and identified some abnormalities in the data which can impact our results.

![Correlation](https://raw.githubusercontent.com/LPugens/imersao-dados-desafio-final/main/fig4_correlation.png)

[Notebook 02 - Análise Quantitativa](https://github.com/LPugens/imersao-dados-desafio-final/blob/main/Notebooks/02_An%C3%A1lise_Quantitativa.ipynb)

## Identifying MoAs through Deep Learning 🤖➡💊
In the main focus of this project, we will try to explore the drug-discovery dataset to find insights and make available a new tool the the drug-discovery researchers.

![Deep Learning](https://raw.githubusercontent.com/LPugens/imersao-dados-desafio-final/main/fig3_deep_learning.jpg)

To this end, we utilize Neural Networks - Machine learning algorithms that are dominating most areas of AI - to predict MoAs through the features in the dataset (genetic activation and cell survivability).

In [Notebook 03 - Deep Learning](https://github.com/LPugens/imersao-dados-desafio-final/blob/main/Notebooks/03_DeepLearning.ipynb), we test a range of Deep Learning techniques, from the simple to the more complex, including Dropout, Early Stopping, PCAs and **[Debiasing](http://introtodeeplearning.com/AAAI_MitigatingAlgorithmicBias.pdf)** of the data.

## Conclusions

[comment]: <> (A aplicação escolhida foi uma das tarefas mais desafiadoras e relevantes que pode ser extraída destes dados.)

[comment]: <> (Utilizando os métodos mencionados, nenhum deles fez grande efeito nos resultado geral de acurácia, que ficou em geral em torno de 12% no conjunto de teste.)

[comment]: <> (![curva de aprendizado]&#40;https://raw.githubusercontent.com/LPugens/imersao-dados-desafio-final/main/fig6_LearningCurve.jpg&#41;)

[comment]: <> (No futuro, estes resultados podem ser melhorados através de dois métodos:)

[comment]: <> (1. integração de mais dados, como por exemplo a estrutura genética das drogas pode ser transformada em um embedding através de trabalhos com [este]&#40;https://arxiv.org/abs/1805.09076&#41;, que analisa as moléculas como grafos de conexão.)

[comment]: <> (![molecula]&#40;https://raw.githubusercontent.com/LPugens/imersao-dados-desafio-final/main/fig7_molecule.jpg&#41;)

[comment]: <> (2. Outras técnicas de pre-processamento que se apliquem melhor ao domínio.)
