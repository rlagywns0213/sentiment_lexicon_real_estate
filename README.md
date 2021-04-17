# 자연언어 처리 기법을 사용한 부동산 지수 예측 모형 (Creative Overall Design 2021-1)
* 작성자 : 김효준

## 1. 연구 목적

- 본 연구의 목적은 인터넷 뉴스에 자연 언어 처리 기법을 적용하여 부동산 지수 예측 모형을 수립하는 것
- 최종적으로 자연 언어 처리 기법을 이용한 부동산 지수 예측 모형을 수립하기 위해 이전의 텍스트 마이닝 및 머신러닝 기법을 사전 작업으로서 수행

## 2. 연구 주요내용

### 2.1 부동산 지수 상방/횡보/하방 시 빈출 단어 조합 도출 및 감성 지수 산출

#### □ Algorithm 1
```python
 Input. A corpus from naver news data K = {x1, x2, ….. xk}
 Output. Words score about all noun corpus
 Method. Initialize word score to 0. And consider rise rates and fall rates about spi rate of change.

1 for x in K :
2	Word_score = 0
3	for i in spi_list:
4		If k in spi_up:
5		    word_score = word_score + fall rates about spi rate of change
6		else k in spi_down:
7		    word_score = word_score – rise rates about spi rate of change
 ```

#### □ Algorithm 2

![image](https://user-images.githubusercontent.com/28617444/115106190-4cf97c80-9f9e-11eb-9bb8-5582318ca1c8.png)

### 2.2 머신러닝 기법에 텍스트 마이닝 결과 변수 추가하여 예측력 향상 여부 확인

### 2.3 자연 언어 처리 기법을 이용한 예측 모형

## 3. 본 연구의 예상 방향성 및 Flowchart

![image](https://user-images.githubusercontent.com/28617444/115106206-65699700-9f9e-11eb-80dc-c81ac73cb0d1.png)
