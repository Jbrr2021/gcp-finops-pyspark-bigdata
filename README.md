# ⚡ GCP FinOps PySpark BigData - Engenharia de Dados em Escala

Neste repositório, catalogo a minha biblioteca de pipelines de dados em Big Data desenvolvidos com **PySpark** no **Google Colab**. O objetivo deste laboratório é processar volumetrias massivas de faturamento em nuvem utilizando arquitetura de computação distribuída.

## 📊 Por que PySpark em FinOps?
Quando a volumetria de logs de faturamento atinge a escala de milhões ou bilhões de linhas, ferramentas tradicionais baseadas em memória única (como o Pandas) atingem gargalos técnicos. O PySpark soluciona essa dor distribuindo a carga de processamento de forma performática entre clusters de computação.

## 📁 Catálogo de Soluções em Big Data

### ⚙️ 1. Infraestrutura e Inicialização do Cluster
*   `setup_inicializacao_pyspark_session.py`: **Pedido do Gestor:** Configurar a infraestrutura virtual de Big Data no ecossistema e inicializar de forma programática uma SparkSession distribuída e isolada para auditoria financeira.

### 🛠️ 2. Ingestão e Transformações Vetorizadas
*   `transformacao_custos_withcolumn_round_pyspark.py`: **Pedido do Gestor:** Realizar a ingestão de registros de faturamento na memória distribuída do Spark. O pipeline cria colunas dinâmicas utilizando `.withColumn()`, aplicando uma taxa de imposto internacional de 15% sobre o custo bruto com tratamento de precisão numérica (`round()`).

### 🔍 3. Filtragem de Alta Performance
*   `filtragem_custos_criticos_filter_pyspark.py`: **Pedido do Gestor:** Criar um filtro de alta criticidade sob volumetrias em escala para isolar custos anômalos. Implementação da cláusula distribuída `.filter()` para expor na tela apenas os ativos que comprometeram o orçamento acima do teto de R$ 100,00.

## 🧠 Evolução Profissional
Avançar para o ecossistema do Apache Spark consolida minha maturidade técnica no gerenciamento de Data Lakes e no desenvolvimento de pipelines de Big Data voltados à governança financeira em nuvem.
