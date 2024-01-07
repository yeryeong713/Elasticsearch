## Elasticsearch 주요 용어
> 원본 데이터 > Indexing(색인) > [index, indicies(인덱스)] > Search(검색) > 사용자

- Indexing(색인)
  - 데이터가 검색될 수 있는 구조로 변경하기 위해 **원본 문서를 검색어 토큰들으로 변환**하여 저장하는 과정

- Index(인덱스)
  - Indexing 과정을 거친 결과물, 또는 Indexing 된 **데이터가 저장되는 저장소**
  - Elasticsearch에서 도큐먼트들의 **논리적인 집합을 표현하는 단위**
 
- Search(검색)
  - Index에 들어있는 **검색어 토큰들을 포함하고 있는 문서**를 찾아가는 과정
     
- Query(질의)
  - 사용자가 원하는 문서를 찾거나 집계 결과를 출력하기 위해 **검색 시 입력하는 검색어 또는 검색 조건**

## Elasticsearch / 관계형 DB 용어 차이

| Elasticsearch     | 관계형 DB          |
| ----------------- | ------------------ |
| Index             | Database           |
| Shard             | Partition          |
| Type              | Table              |
| Field             | Column             |
| Document          | Row                |
| Mapping           | Schema             |
| Query DSL or KQL  | SQL                |
