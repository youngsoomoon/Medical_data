# :mag:공공데이터 분석 - 전국 의료기관
[:earth_asia: 공공데이터 포털](https://www.data.go.kr/index.do) 에서 전국 의료기관 상가 정보데이터를 받아와 분석 및 시각화한 프로젝트입니다.
* 공공데이터 로드 후 결측치 파악/ 중복제거/ 색인하기
* 전국 및 특정 지역에 위치한 의료기관을 scatter를 이용하여 시각화
* folium라이브러리를 이용한 시각화

## 개발환경

```
🔶 Jupyter
    🐼  Pandas
    🧮  Numpy
    📊  matplotlib
    📊  seaborn
    🌏  folium
📤 의료기관정보.csv
```

## :page_facing_up:공공데이터 로드 후 결측치 파악/ value_counts()/ 색인하기
### 공공데이터 로드
39개의 컬럼으로 이루어진 9만여개의 엑셀파일을 데이터 프레임으로 로드

![image](https://user-images.githubusercontent.com/74235867/116038369-55d80580-a6a4-11eb-9844-67233aeb6917.png)

### 결측치 제거
결측치가 많은 상위 9개의 컬럼을 추출 후 삭제
![image](https://user-images.githubusercontent.com/74235867/116038611-9fc0eb80-a6a4-11eb-9aa7-632804de91e7.png)

### :bar_chart:value_counts() - 그룹화된 요약값 보기
![image](https://user-images.githubusercontent.com/74235867/116038775-d72f9800-a6a4-11eb-8b9f-c17bf7a02c2e.png)

### 여러 조건으로 색인하기
![image](https://user-images.githubusercontent.com/74235867/116038795-e0b90000-a6a4-11eb-9e40-d79f330121b2.png)

## :earth_asia:scatter를 이용하여 서울 의료기관 시각화
![image](https://user-images.githubusercontent.com/74235867/116038934-0e9e4480-a6a5-11eb-9a80-41bbc48f9c62.png)

## :earth_asia:scatter를 이용하여 전국 의료기관 시각화
![image](https://user-images.githubusercontent.com/74235867/116038969-1827ac80-a6a5-11eb-8574-aa47aa02884b.png)

## :earth_asia:folium 라이브러리를 사용하여 시각화
![image](https://user-images.githubusercontent.com/74235867/116039020-2970b900-a6a5-11eb-93b7-ae23c14291f7.png)
