# Data Glossary
Brief explanations of Data terms
 
<details>
   <summary>ACID</summary>
 
  Sigla para atomicidade, consistência, isolamento e durabilidade. Conjunto de propriedades de transação em banco de dados. 

  * Atomicidade: transações por completo ou nada. Não existe parcial. Se alguma das instruções que constituem uma transação não for concluída, toda a transação falhará e o banco de dados permanecerá inalterado.Garantia contra falhas de energia, erros e travamentos.
  * Consistência: regras que não podem ser quebradas. Um dado só pode ser criado num banco se ele existir previamente de sua fonte. Não se pode criar ou perder dados.
  * Isolamento: A transação não será interferida por nenhuma outra. Um processo simultâneo não pode ver os dados em um estado inconsistente.
  * Durabilidade: as alterações feitas por uma transação ficam disponíveis de forma permanente. Uma vez confirmada, ela permanecerá confirmada, mesmo que hajam falhas do sistema.
</details>

<details>
  <summary>Análise Preditiva</summary>
 
 Aplicação de algoritmos estatísticos e de aprendizado de máquina para identificar a probabilidade de resultados futuros a partir de dados históricos.
</details>

<details>
  <summary>Arquitetura de soluções</summary>
 
</details>

<details>
  <summary>Arquitetura do projeto</summary>
 
 Caminho do dado, seguido pela camada row e depois camada ready.
</details>
 
 <details>
  <summary>Árvore de decisão</summary>
 
 Organiza e estrutura regras de classificação e decisão em formato de diagrama de árvore, com a pretenção de predizer resultados futuros.
</details>
 
<details>
  <summary>AWS</summary>
 
</details>
 
<details>
  <summary>Azure</summary>
 
</details>
 
<details>
  <summary>Banco de dados</summary>
 
 * BD relacional: SQL Server, MySQL
 * BD não relacional: Cosmos DB
</details>

<details>
  <summary>Banco de dados distribuído</summary>
 
</details>

<details>
  <summary>Banco de dados paralelo</summary>
 
</details>
 
<details>
  <summary>Base fria</summary>
 
 Oposto de base quente. Não é a base principal, a qual recebe as informações a todo instante.
</details>

<details>
  <summary>Base quente</summary>
 
 Recebe informações a todo instante, incluídas diretamente nela, mudando a todo instante. A prioridade é receber dados.
</details>

<details>
  <summary>Batch processing</summary>
 
 Armazena os dados no buffer e os processa em grupos. Utilizado em Big Data. U-SQL, Hive, Pig, Spark.
</details>

<details>
  <summary>Big data</summary>
 
</details>

<details>
  <summary>Business inteligence</summary>
 
</details>

<details>
  <summary>Cassandra</summary>
 
</details>

<details>
  <summary>Cloud</summary>
 
</details>

<details>
  <summary>Conteiner</summary>
 
</details>

<details>
 <summary>Dados</summary>
 
 * Dados estruturados: dados armazenados em estruturas bem definidas e consistentes como tabelas e planilhas com linhas, colunas e campos pré definidos eEx.: Excel, SQL.
 * Dados semi-estruturados: possuem características definidas, sendo parcialmente estruturados, mas não se limitam a uma estrutura rígida. Ex.: parquet, json, XML.
 * Dados não estruturados: não possuem estrutura nem padrão pré-definido, são dados flexíveis e dinâmicos, podendo ser compostos por diversos elementos diferentes dentro um todo. Ex.: imagem, vídeo, texto.
</details>

<details>
 <summary>Dark/Dusty Data</summary>
 
 São os dados que são coletados acidentalmente, como uma subprodução pelo uso de uma aplicação. Normalmente é um dado não estruturado e, na maioria das vezes, não chega a ser utilizado ou armazenado.
</details>

<details>
 <summary>Data Hub</summary>
 
 O local ideal para os dados centrais de uma organização. Ele permite o compartilhamento e distribuição de dados na forma de uma arquitetura hub and spoke.
</details>

<details>
  <summary>Data lake</summary>
 
 Repositório centralizado de dados brutos, mais comumente implementado numa plataforma de armazenamento baseada em nuvem. Tudo o que tem de dados, oriundos de diversas fontes, seja de qualquer tipo (relacional, não relacional, estruturado, não estruturado, etc.). 
</details>

<details>
  <summary>Data mart</summary>
 
 Coleção de dados de um processo específico de negócios. Pode ser considerado um pequeno data warehouse ou parte de um grande data warehouse, delimitando uma determinada área de assunto e oferecendo informações mais detalhadas sobre o mercado em questão.
 </details>
 
 <details>
  <summary>Data mining</summary>
 
 "Mineração de Dados". Consiste em um processo analítico projetado para explorar grandes quantidades de dados na busca de padrões consistentes e relacionamentos sistemáticos entre variáveis e, então, validá-los aplicando os padrões detectados a novos subconjuntos de dados. Se divide em três etapas: exploração, construção de modelo e validação.
 </details>

<details>
  <summary>Data warehouse</summary>
 
 Um sistema de gerenciamento de dados que armazena-os de forma organizada. Extrai, centraliza e consolida grandes quantidades de dados de diferentes fontes dentro de uma organização, onde ficam disponíveis para consultas e análises. Inclui banco de dados relacional, solução de ETL, ferramenta de analytics. Não exclui a utilização do data lake.
</details>

<details>
  <summary>Databricks</summary>
 
</details>

<details>
  <summary>Dataset</summary>
 
</details>

<details>
  <summary>ETL (CONTINUAR)</summary>
 
 Sigla para Extract, Trasform e Load. O processo de migração de dados que extrai, transforma e carrega os dados em várias zonas para que os usuários de negócios extraiam seu valor. Pega os dados na base quente e envia para a base fria. 
</details>

<details>
  <summary>Grafo</summary>
 
</details>

<details>
  <summary>IaaS</summary>
 
</details>

<details>
  <summary>Json</summary>
 
 Notação de dados primitivos. Apenas texto, número e booleano.
</details>

<details>
  <summary>Labeled Data</summary>
 
 São os dados rotulados como metadados, ou "tags", que ajudam a pesquisar os dados posteriormente. Os dados rotulados são usados para ensinar aos algoritmos de aprendizagem de máquina o que queremos que eles procurem.
</details>

<details>
  <summary>Metadados</summary>
 
 Dados que são informações estruturadas que auxiliam na descrição, identificação, etc. de outros dados.
</details>

<details>
  <summary>Mineração de dados</summary>
 
</details>

<details>
  <summary>Modelagem de dados</summary>
 
</details>

<details>
  <summary>MongoDB</summary>
 
</details>

<details>
  <summary>NoSQL</summary>
 
Documentos com todas as informações correlacionadas à principal (estruturas de LOGs, aplicações analíticas para BI). Usado para Big Data. Ex.: MongoDB, Hbase, Cassandra, Neo4J, REDIS, MemcacheD, Amazon DynamoDB, CosmosDB.
</details>

<details>
  <summary>OLAP (Online Analytical Processing)</summary>
 
 Trata da capacidade de analisar grandes volumes de informações nas mais diversas perspectivas dentro de um Data Warehouse. Também dá suporte a ferramentas analíticas.
</details>

<details>
  <summary>OLTP (Online Transaction Processing)</summary>
 
 Sistemas que se encarregam de registrar todas as transações contidas em uma determinada operação organizacional.
</details>

<details>
  <summary>Pandas</summary>
 
 Biblioteca de Python voltada a ciência de dados.
</details>

<details>
  <summary>Paralelismo</summary>
 
</details>

<details>
  <summary>Parquet</summary>
 
</details>

<details>
  <summary>Particionamento</summary>
 
</details>

<details>
  <summary>Pipeline</summary>
 
Pipelines são fluxos onde a entrada de um dado é processado e enviado para outro processo, cada processo executa uma tarefa específica que contribui para um objetivo maior (task).
</details>

<details>
  <summary>Python</summary>
 
</details>

<details>
  <summary>R</summary>
 
</details>

<details>
  <summary>Redes neurais</summary>
 
 Algoritmos computacionais que simulam células neurais conectadas entre si, capazes de aprender em ciclos de análise e reconhecimento de padrões, apoiando novos ciclos e decisões.
</details>

<details>
  <summary>Schema</summary>
 
</details>

<details>
  <summary>Sistemas distribuídos</summary>
 
</details>

<details>
  <summary>Spark</summary>
 
 Voltado a Big Data e Engenharia de Dados.
</details>

<details>
  <summary>SQL</summary>
 
 Sigla para Structure Query Language (Linguagem estruturada de consulta). Dados bem estruturados e amarrados, aplicações gerenciais.
 
 * .agg():
 * .pivot():
 * Chave estrangeira:
 * Chave primária:
 * Cliente:
 * Coalesce:
 * Shuffle:
</details>

<details>
  <summary>SQL Server Management Studio (SSMS)</summary>
 
 Interface gráfica para consulta de dados.
</details>

<details>
  <summary>Streaming data</summary>
 
 Processamento do dado no momento exato em que chega.
</details>

<details>
  <summary>Tupla</summary>
 
Uma linha (registro) numa tabela de BD relacional.
</details>

<details>
 <summary>Wrangling</summary>
 
 É o processo pelo qual você transforma e mapeia dados brutos em um formato mais útil para análise. Pode envolver escrita de código para capturar, filtrar, limpar, combinar e agregar dados de diversas fontes.
 </details>
 
 
