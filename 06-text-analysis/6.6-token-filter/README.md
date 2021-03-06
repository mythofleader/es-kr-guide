---
description: >-
  이 문서의 허가되지 않은 무단 복제나 배포 및 출판을 금지합니다. 본 문서의 내용 및 도표 등을 인용하고자 하는 경우 출처를 명시하고
  김종민(kimjmin@gmail.com)에게 사용 내용을 알려주시기 바랍니다.
---

# 6.6 토큰 필터 - Token Filter

  토크나이저를 이용한 텀 분리 과정 이후에는 분리된 각각의 텀 들을 지정한 규칙에 따라 처리를 해 주는데 이 과정을 담당하는 것이 **토큰 필터**입니다. 토큰 필터는 `filter` _**\(token\_filter가 아닙니다!\)**_ 항목에 배열 값으로 나열해서 지정합니다. 하나만 사용하더라도 배열 값으로 입력해야 하며 나열된 순서대로 처리되기 때문에 순서를 잘 고려해서 입력해야 합니다.

  토큰 필터 역시 종류가 상당히 많고 계속 업데이트 되기 때문에 이 책에서는 자주 사용되는 토큰 필터 위주로 살펴보겠습니다. [공식 도큐먼트](https://www.elastic.co/guide/en/elasticsearch/reference/current/analysis-tokenfilters.html)에서 내가 필요로 하는 토큰 필터가 있는지 종종 들러서 살펴보시기 바랍니다.

