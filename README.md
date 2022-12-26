# python_semi_one
## 세미 프로젝트 명
- 김치왜함
## 세미 프로젝트 주제
1. 비트코인, 이더리움, 위믹스 토큰의 가격 및 거래량의 일별 자료를 통해 비트코인 과의 상관관계를 알아보고자 함.
2. 3개년 치 (2020-10-26 ~ 2022-12-26) 의 자료를 investing.com 의 과거 데이터 다운로드를 통해 자료 수집.
3. 데이터 전처리 후 matplotlib를 통해 각종 도표로 데이터 확인 진행.

## 스케쥴 진행
### 2022-12-26(월)
1. 데이터 다운로드 후 pandas 통해 각각 데이터 프레임 생성 (bit_origin, eth_origin, wemix_origin)
2. bit_origin df 데이터 전처리(bit_copy) -> NaN값 처리, 데이터형 변환, 단위 변환 등
3. 환율(월평균매매기준율) 적용하여 KRW 컬럼 추가 (서울외국환중개 자료 이용)
4. bit_krw 데이터프레임 작업 완료

### 2022-12-27(화)
1. eth_origin 및 wemix_origin 데이터 전처리
2. bit_copy 그래프 생성 (matplotlib) 테스트

### 2022-12-28(수)
1. matplotlib 통해 전체 그래프 생성

### 2022-12-29(목)
1. 발표 자료 작성

### 2022-12-30(금)
1. 발표 진행