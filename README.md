# Encontrando doadores para a CharityML

O projeto faz parte do curso Engenheiro de Machine Learning

![alt text](https://github.com/vyniciuss/enron_machine_learning/blob/master/enron.jpg)

## Visão Geral do Projeto

Neste projeto, apliquei técnicas de aprendizagem supervisionada e raciocínio analítico sobre os dados coletados pelo censo dos Estados Unidos para ajudar a CharityML (uma instituição de caridade fictícia) a identificar as pessoas com maior probabilidade de doar à causa deles. Primeiro, foi feito uma exploração para saber como os dados do censo são gravados. Em seguida, apliquei uma série de transformações e técnicas de pré-processamento para manipular os dados e organizá-los em um formato com o qual precisei trabalhar. Depois, avaliei vários modelos de aprendizagem supervisionada de minha escolha sobre os dados, para definir qual é o mais adequado para a solução. Depois disso, otimizei o modelo selecionado e o apresentei para os avaliadores da Udacity como sua solução para a CharityML.

### Dados

O conjunto de dados do censo consiste em 32.000 registros, sendo que cada registro possui 13 atributos. Este conjunto de dados é uma versão modificada do que foi publicado no artigo *"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid",* de Ron Kohavi. Você pode encontrar este artigo [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf), com o conjunto de dados original hospedado em [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income).

**Atributos**
- `age`: Idade
- `workclass`: Classe trabalhadora (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
- `education_level`: Nível de educação (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
- `education-num`: Número de anos de estudo concluídos
- `marital-status`: Estado civil (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
- `occupation`: Ocupação profissional (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
- `relationship`: Status de relacionamento (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
- `race`: Raça (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
- `sex`: Sexo (Female, Male)
- `capital-gain`: Ganhos de capital monetário
- `capital-loss`: Perdas de capital monetário
- `hours-per-week`: Média de horas trabalhadas por semana
- `native-country`: País de origem (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)

**Variável-alvo**
- `income`: Classe de renda (<=50K,>50K)</=50K,>

Este projeto requer **Python 3.6** e as seguintes bibliotecas Python instaladas:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [Matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

Você também precisará ter software instalado para rodar e executar um [iPython Notebook](http://ipython.org/notebook.html)
