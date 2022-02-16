# MBTI_classification

Dataset by Zeyad Khalid (Kaggle)

https://www.kaggle.com/zeyadkhalid/mbti-personality-types-500-dataset


## 데이터셋 구조
- Columns : 'attribute', 'type'
- 속성 : attribute
- 타켓 : type
- 모두 문자열 데이터

목표 : 16가지 클래스 분류

###### 문자열 처리 시급...
###### 선택지
###### &nbsp;&nbsp;&nbsp; - 단어 Tokenize
###### &nbsp;&nbsp;&nbsp; - 각 단어 column 취급

##### 데이터 상태
###### - 관사, 조사 등의 불용어는 제거 된 상태임
###### - 표제어만 남음
###### - 설명란에는 전처리가 되어 모두 500단어로 구성되었다고 하지만, 실제로는 1~2개 정도 오차가 있음
###### - 패딩을 하든 해야함

###### (각 단어 column화 시도중)
###### - 중복단어 문제
###### - 순서 상관여부 확인해야함

