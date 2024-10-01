<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>
    <h1>Análise de Sentimentos na Rede Social X: Um Estudo com NLP</h1>
    <h2>Descrição do Projeto</h2>
    <p>Este repositório contém os dados e resultados da pesquisa intitulada <strong>"Análise de Sentimentos na Rede Social X: Um Estudo com NLP"</strong>, realizada como parte de um Trabalho de Conclusão de Curso (TCC). A análise de sentimentos em redes sociais, especialmente no X (antigo Twitter), se destaca como uma ferramenta essencial para compreender as percepções do consumidor. </p>
    <p> O estudo investiga a eficácia de três modelos de Processamento de Linguagem Natural (NLP) na análise de sentimentos de tweets em português: </p>
    <ul>
        <li><strong>Regressão Logística</strong></li>
        <li><strong>XGBoost</strong></li>
        <li><strong>BERT</strong></li>
    </ul>
    <p>A pesquisa enfrentou desafios linguísticos e computacionais, utilizando dados de tweets de grandes marcas brasileiras, coletados por meio da API do X, e aplicou rigorosos métodos de pré-processamento para alcançar resultados precisos e confiáveis. </p>
    <h3>Resumo dos Resultados</h3>
    <ul>
        <li><strong>Regressão Logística</strong>: Acurácia de 77%</li>
        <li><strong>XGBoost</strong>: Acurácia de 74,43%</li>
        <li><strong>BERT</strong>: Acurácia de 86%</li>
    </ul>
    <p> Os resultados revelaram que, enquanto o BERT oferece uma capacidade superior para capturar nuances linguísticas, o XGBoost se mostrou uma alternativa eficaz, equilibrando desempenho e custo.</p>
    <h2>Gráficos e Resultados</h2>
    <p> Os gráficos a seguir apresentam as análises de desempenho dos modelos de machine learning utilizados no estudo. Cada gráfico ilustra as métricas de performance (como acurácia, matriz de confusão e curvas ROC) de acordo com o modelo e a marca analisada.</p>
<h3>Bradesco</h3>
    <ul>
        <li><strong>BERT</strong>: <img src="./Bradesco BERT.png" alt="Bradesco BERT" /></li>
        <li><strong>Regressão Logística</strong>: <img src="./Bradesco Regressão Logística.png" alt="Bradesco Regressão Logística" /></li>
        <li><strong>XGBoost</strong>: <img src="./Bradesco XGBoost.png" alt="Bradesco XGBoost" /></li>
    </ul>
    <h3>Burger King Brasil</h3>
    <ul>
        <li><strong>BERT</strong>: <img src="./BurgerKingBR BERT.png" alt="Burger King BERT" /></li>
        <li><strong>Regressão Logística</strong>: <img src="./BurgerKing Regressão Logística.png" alt="Burger King Regressão Logística" /></li>
        <li><strong>XGBoost</strong>: <img src="./BurgerKingBR XGBoost.png" alt="Burger King XGBoost" /></li>
    </ul>
    <h3>Petrobras</h3>
    <ul>
        <li><strong>BERT</strong>: <img src="./Petrobras BERT.png" alt="Petrobras BERT" /></li>
        <li><strong>Regressão Logística</strong>: <img src="./Petrobras Regressão Logística.png" alt="Petrobras Regressão Logística" /></li>
        <li><strong>XGBoost</strong>: <img src="./Petrobras XGBoost.png" alt="Petrobras XGBoost" /></li>
    </ul>
    <h2>Estrutura do Repositório</h2>
    <pre>
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
    </pre>
    <h2>Tecnologias Utilizadas</h2>
    <ul>
        <li><strong>Python</strong>: Para construção dos modelos de aprendizado de máquina.</li>
        <li><strong>sklearn</strong>: Biblioteca utilizada para a implementação dos modelos de Regressão Logística e XGBoost.</li>
        <li><strong>Transformers (Hugging Face)</strong>: Usado para o modelo BERT.</li>
        <li><strong>Matplotlib</strong> e <strong>Seaborn</strong>: Para visualização de gráficos.</li>
        <li><strong>API do X</strong>: Para coleta de dados de tweets.</li>
        <li><strong>Pandas</strong> e <strong>NumPy</strong>: Para manipulação de dados.</li>
    </ul>
    <h2>Palavras-chave</h2>
    <ul>
        <li>Análise de Sentimentos</li>
        <li>Processamento de Linguagem Natural (NLP)</li>
        <li>Regressão Logística</li>
        <li>XGBoost</li>
        <li>BERT</li>
        <li>Mídias Sociais</li>
        <li>Língua Portuguesa</li>
        <li>Percepção do Consumidor</li>
        <li>Pré-processamento de Dados</li>
        <li>Aprendizado de Máquina</li>
    </ul>
    <h2>Como Contribuir</h2>
    <p>
        Sinta-se à vontade para clonar este repositório, explorar os dados e os modelos utilizados, e contribuir com melhorias ou sugestões.
    </p>
</body>
</html>
