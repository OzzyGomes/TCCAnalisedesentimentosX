Análise de Sentimentos na Rede Social X: Um Estudo com NLP
Descrição do Projeto
Este repositório contém os dados e resultados da pesquisa intitulada "Análise de Sentimentos na Rede Social X: Um Estudo com NLP", realizada como parte de um Trabalho de Conclusão de Curso (TCC). A análise de sentimentos em redes sociais, especialmente no X (antigo Twitter), se destaca como uma ferramenta essencial para compreender as percepções do consumidor.

O estudo investiga a eficácia de três modelos de Processamento de Linguagem Natural (NLP) na análise de sentimentos de tweets em português:

Regressão Logística
XGBoost
BERT
A pesquisa enfrentou desafios linguísticos e computacionais, utilizando dados de tweets de grandes marcas brasileiras, coletados por meio da API do X, e aplicou rigorosos métodos de pré-processamento para alcançar resultados precisos e confiáveis.

Resumo dos Resultados
Regressão Logística: Acurácia de 77%
XGBoost: Acurácia de 74,43%
BERT: Acurácia de 86%
Os resultados revelaram que, enquanto o BERT oferece uma capacidade superior para capturar nuances linguísticas, o XGBoost se mostrou uma alternativa eficaz, equilibrando desempenho e custo.

Gráficos e Resultados
Os gráficos a seguir apresentam as análises de desempenho dos modelos de machine learning utilizados no estudo. Cada gráfico ilustra as métricas de performance (como acurácia, matriz de confusão e curvas ROC) de acordo com o modelo e a marca analisada.

Bradesco
BERT:
Regressão Logística:
XGBoost:
Burger King Brasil
BERT:
Regressão Logística:
XGBoost:
Petrobras
BERT:
Regressão Logística:
XGBoost:
Estrutura do Repositório
O repositório está organizado da seguinte maneira:

mathematica
Copiar código
├── Bradesco BERT.png
├── Bradesco Regressão Logística.png
├── Bradesco XGBoost.png
├── BurgerKing Regressão Logística.png
├── BurgerKingBR (1).csv
├── BurgerKingBR BERT.png
├── BurgerKingBR XGBoost.png
├── Petrobras BERT.png
├── Petrobras Regressão Logística.png
├── Petrobras XGBoost.png
Tecnologias Utilizadas
Python: Para construção dos modelos de aprendizado de máquina.
sklearn: Biblioteca utilizada para a implementação dos modelos de Regressão Logística e XGBoost.
Transformers (Hugging Face): Usado para o modelo BERT.
Matplotlib e Seaborn: Para visualização de gráficos.
API do X: Para coleta de dados de tweets.
Pandas e NumPy: Para manipulação de dados.
Palavras-chave
Análise de Sentimentos
Processamento de Linguagem Natural (NLP)
Regressão Logística
XGBoost
BERT
Mídias Sociais
Língua Portuguesa
Percepção do Consumidor
Pré-processamento de Dados
Aprendizado de Máquina
Como Contribuir
Sinta-se à vontade para clonar este repositório, explorar os dados e os modelos utilizados, e contribuir com melhorias ou sugestões.
