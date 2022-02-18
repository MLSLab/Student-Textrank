# Student-Textrank
학생들 공부자료 - text rank

## 1. 핵심키워드 추출하기
#### 1-1. 파일 읽기
#### 1-2. 문장 Tokenize 하기
#### 1-3. 단어 index 만들기
#### 1-4. word 그래프 만들기
그래프를 구현하는데에는 co-occcurrence 행렬을 사용한다.<br>
co-occcurrence(동시출현)는 한 문장, 문단 또는 텍스트 단위에서 같이 출현한 단어이다.<br>
#### 1-5. 그래프에 PageRank 적용
<img width="426" alt="스크린샷 2021-06-02 오후 7 38 05" src="https://user-images.githubusercontent.com/32845598/120466550-2a9ab180-c3da-11eb-9e87-8d4b0faa6d7d.png">


<br>
<br>

## 2. 핵심문장 추출하기
#### 2-1. 파일 읽기
#### 2-2. 단어 tokenize 후, 단어 index 만들기
#### 2-3. 문장 그래프를 만들기
<img width="600" alt="스크린샷 2021-06-02 오후 7 38 05" src="https://user-images.githubusercontent.com/32845598/120467382-1905d980-c3db-11eb-985c-9ebb84659866.png">
<img width="600" alt="스크린샷 2021-06-02 오후 7 38 05" src="https://user-images.githubusercontent.com/32845598/120467528-3c308900-c3db-11eb-9710-111968d04222.png">

#### 2-4. 문장 그래프을 pagerank에 적용하기
<img width="426" alt="스크린샷 2021-06-02 오후 7 38 05" src="https://user-images.githubusercontent.com/32845598/120466550-2a9ab180-c3da-11eb-9e87-8d4b0faa6d7d.png">

