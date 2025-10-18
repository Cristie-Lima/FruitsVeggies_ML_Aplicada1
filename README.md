# 📊 Pós-graduação em Ciência de Dados (2025/2026)  

**Escola Superior de Tecnologia da Universidade Estadual do Amazonas - EST/UEA**  
**Disciplina:** Machine Learning Aplicado I
**Professor:** Prof. Dr. Fábio Santos da Silva

📂 **Repositórios do Projeto Acadêmico no GitHub:**  
1. [fruits_vs_vegetables](https://github.com/csampaio2/fruits_vs_vegetables)  
2. [FruitsVeggies_ML_Aplicada1](https://github.com/Cristie-Lima/FruitsVeggies_ML_Aplicada1)  
📂 **Apresentação:** [Projeto Final – Classificação de Frutas, Legumes e Verduras](https://notebooksharing.space/view/cee47e5603ebbaed272c4b8905a06ba44bd21ac0e30796fdd7c4de92b96b6687#displayOptions=show-linenos%7Chide-inputs))  
📂 **Dataset:** [Fruits and Vegetables Image Recognition Dataset (KAGGLE)](https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition/data)

👩‍🎓 **Equipe:**  
- A. Cristiane R. Lima (Cristie), {acrdl.cid25@uea.edu.br}
- Claudio Cardoso Sampaio (Claudio), {ccs.cid25@uea.edu.br}

📅 **Data:** 17 de outubro de 2025  

---

# 📌 Contextualização do Projeto

# Introdução e formulação do problema

Observou-se que o objetivo consiste em **classificar imagens** de frutas, legumes e verduras em suas respectivas categorias, utilizando modelos de **aprendizado supervisionado**. Pretende-se fundamentar cada etapa no arcabouço proposto por Kelleher (2ª ed.), contemplando definição do problema, preparação dos dados, modelagem, avaliação e implantação (*deployment*) simplificada via aplicativo.

**Pergunta de pesquisa:** É possível treinar um modelo supervisionado que classifique corretamente, a partir de **atributos extraídos de imagens** (*image features*), as classes de interesse?

**Tipo de tarefa:** Classificação **multiclasse**.

**Objetivo prático:** Disponibilizar um **aplicativo interativo** (usando Streamlit) que receba uma imagem e retorne a predição do modelo.

**Desafios (se houver tempo hábil):**
- Disponibilizar outro **aplicativo interativo** usando Gradio
- Desenvolver modelo CNN para fins de _benchmarking_

---

# ⚙️ Sumário
0. Preparação dos dados — limpeza opcional vs. atualização de timestamps  
1. Ingestão de dados (três arquivos ZIP) e organização das pastas  
1.1 Criação das subpastas e verificação dos arquivos ZIP  
1.2 Estrutura esperada do diretório após a extração  
1.3 Descompactação recursiva e organização automática  
1.4 Diagnóstico da estrutura e verificação de pastas de classes  
1.5 Detecção automática das raízes de classes e contagem de imagens  
2. Preparação e engenharia de atributos (*feature engineering*)  
3. Modelagem conforme Plano de Ensino (KNN, Árvore, Regressão Logística, Random Forest, Bagging, Boosting) + MLP

    **>> Professor sugeriu focar no MLP, kNN, Random Forest pois são os mais adequados para Classificar Imagens; Equipe: fazer double-checking se embedding está sendo aplicado apropriadamente**
4. Avaliação e *benchmarking* (matriz de confusão, métricas, *cross-validation* estratificada)  
5. Empacotamento do melhor modelo e *stub* de aplicativo Streamlit  
6. Conclusões, *trade-offs* (compensações) e trabalhos futuros  
7. Referências
