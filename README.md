# Elasticsearch
- Apache Lucene(아파치 루씬) 기반의 Java 오픈소스 **분산 검색 엔진**
- **대량의 데이터**를 신속하게 거의 실시간(Near Real Time)으로 **저장, 검색, 분석** 할 수 있음
- Elasticsearch는 검색을 위해 단독으로 사용되기도 하며 ELK Stack으로 사용되기도 함

## ELK(Elasticsearch, Logstash, Kibana) Stack이란?
Log 및 데이터 분석 도구

 - **Logstash**   
   다양한 sorce(DB, csv파일)의 **로그 데이터를 수집, 집계**하여 Elasticsearch로 전달

 - **Elasticsearch**   
   Logstash로부터 받은 **데이터를 검색 및 집계**하여 필요한 관심 있는 정보를 획득

 - **Kibana**   
   Elasticsearch의 검색을 통해 **데이터를 시각화 및 모니터링**

   ![ELK Stack](https://github.com/yeryeong713/Elasticsearch/assets/88486391/302834ca-7c0f-4fe0-bfdb-0d691bfa4b2c)

## Elasticsearch 특징
- 분산시스템 (distributed system)
- 높은 가용성 (High Availabilty)
- Multi Tenancy
- Scale out
- Schema Free
- Json Document & Restful API
- 실시간 분석 (Near Real Time)
