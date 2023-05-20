# NIAS-IA-Contradictory-My-Dear-Watson
Duas abordagens de NLP para a competição de aprendizado disponível no Kaggle, sendo um modelo usando somente os dados disponíveis e outro aplicando um modelo pré-treinado

## Primeira Abordagem SCORE = 0.52319
A primeira abordagem utiliza a tradução do google tradutor para resolver o problema de multilinguagens. As traduções foram feitas para o inglês por causa da maior quantidade de dados dessa língua. Após isso, os textos são convertidos em números pelo TFIDF e aplicados em um modelo lgbm para classificação.

## Segunda abordagem SCORE = 0.8974
Foi aplicado um modelo pré-treinado assim como em https://www.kaggle.com/code/sambitmukherjee/watson-2-a-set-of-baselines. Vale ressaltar que esse modelo foi treinado com banco de dados externo e sua alta eficácia pode ser resultado de haver dados do teste do kaggle presentes no treinamento.
