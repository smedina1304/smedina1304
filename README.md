# smedina1304


```js
import SystemsArchitect from 'sergio1304';

class Bio extends SystemsArchitect {
  name       = 'Sergio Cozzetti Medina';
  title      = 'Systems Architect';
  company    = 'Pöyry BR | AFRY';
  location   = 'Sao Paulo, BR';
  specialist = 'Systems Integration | Microservices | Data Engineer';
}

class Skills_SAP extends SystemsArchitect {
  SAP = ['ECC', 'S4/Hana', 'PI/PO', 'MII', 'UI5', 'Netweaver'];  
}

class Skills_Dev extends SystemsArchitect {
  languages       = ['Java', 'Python', 'C/C++', 'JavaScript'];
  databases_SQL   = ['Oracle', 'MSSQL', 'MySQL' ,'PostgreSQL'];
  databases_NoSQL = ['MongoDB', 'Firebase', 'DynamoDB' ,'Neo4J'];  
}

class Skills_DataEng extends SystemsArchitect {
  flow_orchestration = ['Apache Airflow', 'Prefect'];
  big_data           = ['Hadoop', 'Spark', 'Kafka', 'KsqlDB']
  databases_SQL      = ['Oracle', 'MSSQL', 'MySQL' ,'PostgreSQL'];
  databases_NoSQL    = ['MongoDB', 'Firebase', 'DynamoDB' ,'Neo4J'];
  cloud_aws          = ['S3', 'EKS', 'EC2', 'EMR', 'RDS', 'Textract', 'Glue', 'Athena'];
  infrastructure     = ['Terraform', 'eksctl']
}


```