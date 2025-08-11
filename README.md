# 📊  Telecom X – Parte 2: Prevendo Churn
Descrição
Este projeto tem como objetivo analisar desenvolver modelos preditivos capazes de prever quais clientes têm maior chance de cancelar seus serviços.

A empresa quer antecipar o problema da evasão, e cabe a você construir um pipeline robusto para essa etapa inicial de modelagem.<br><br>

# 🧠 Objetivos do Desafio

Preparar os dados para a modelagem (tratamento, encoding, normalização).

Realizar análise de correlação e seleção de variáveis.

Treinar dois ou mais modelos de classificação.

Avaliar o desempenho dos modelos com métricas.

Interpretar os resultados, incluindo a importância das variáveis.

Criar uma conclusão estratégica apontando os principais fatores que influenciam a evasão.

# 📁 Estrutura do Projeto<br><br>
data/ → Dataset utilizado na análise.

notebooks/ → Jupyter Notebook com a análise completa.

figures/ → Gráficos gerados para ilustrar insights.

README.md → Documentação do projeto.<br><br>

# 🔍 Análises Realizadas
<br>Foi conduzido um estudo com o objetivo de prever a evasão de clientes a partir de variáveis comportamentais, demográficas e de utilização de serviços. Para isso, dois modelos de Machine Learning foram aplicados e avaliados: Regressão Logística e Random Forest.

Na Regressão Logística, investigamos os coeficientes das variáveis, o que permitiu entender a direção e intensidade do impacto de cada fator na probabilidade de evasão. Observamos que variáveis relacionadas à utilização de serviços adicionais, tempo de permanência e tipo de contrato apresentaram relevância significativa, ajudando a identificar perfis com maior risco de saída.

No Random Forest, analisamos a importância das variáveis com base na redução de impureza nas árvores de decisão. O modelo destacou que o tempo de relacionamento com a empresa, o tipo de serviço contratado e a presença ou ausência de suporte técnico foram fatores determinantes para a previsão de evasão.

Comparando o desempenho, o Random Forest apresentou maior acurácia e capacidade de generalização em relação à Regressão Logística, indicando ser o modelo mais adequado para esta base de dados. No entanto, a Regressão Logística se mostrou valiosa para interpretação direta do impacto das variáveis.<br>

# ✅ Principais Conclusões
<br>Os resultados obtidos possibilitam não apenas prever quais clientes estão mais propensos a evadir, mas também entender os fatores que influenciam essa decisão. Com base nessas análises, podem ser implementadas ações estratégicas de retenção, como:

Ofertas personalizadas para clientes com pouco tempo de contrato.

Melhoria no suporte técnico para aumentar a satisfação.

Pacotes de serviços ajustados ao perfil de consumo identificado como de maior risco.

Esse estudo reforça a importância da análise preditiva como ferramenta de apoio à tomada de decisão e gestão da base de clientes, combinando previsões assertivas com insights práticos para ações de retenção. <br>

# 🛠️ Tecnologias Utilizadas
Python 3.x

Pandas

NumPy

Matplotlib / Seaborn

Jupyter Notebook<br><br>

# 🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.
