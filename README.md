# Review_Crawling_project 
크롤링 데이터 솔루션을 통한 데이터 수집
<br/>
<br/>
<br/>


## 1. 프로젝트명

Re.staurant(Review Restaurant)
- 네이버 식당 리뷰를 크롤링하고 성향판단해보기
  
- Tmax Tibero : TABA2기 ( 캠퍼스 SW 아카데미 지원사업) <br/>
- CCCR : 한국클라우드컴퓨팅연구조합 <br/>
- 과학기술정보통신부 <br/>
- 단국대학교
  
## 2. 프로젝트 개요
<br/>
<크롤링 데이터 솔루션을 통해 데이터 수집>
<br/><br/>
  1) &nbsp;리뷰(네이버) 키워드를 쉽게 보여주고</br>
  2) &nbsp;리뷰를 성향별로 나누어주며</br>
  3) &nbsp;누구나 손쉽게 리뷰를 판단할 수 있는 서비스 제공</br>

<br/>
 
- 프로젝트 계기
  
   - 과도한 허위 리뷰와 바이럴 마케팅으로 인한 리뷰의 객관적 판단 어려움
     
   - 서비스 대상자
     코로나 19 엔데믹 후 증가하는 여행객들을 대상으로 선정

  - 리뷰 주제
     관광 지출액 비율중 식음료의 비율이 가장 높아 제공 서비스를 식당 리뷰로 선택

    <br/>

- 문화체육관광부 여행언급량 추이 (20.02~22.08)

![image](https://github.com/Son-Hyemin/Review_Crawling_projoect/assets/120477911/5c43c572-5e02-4f5a-a301-2d985dc001ec)

- 한국관광데이터 관광 지출액 (2022.06~2023.05)<br/>
<img src="https://github.com/JUICE-JinHyeong/Review_Crawling/assets/111718162/694e0564-0e26-4a03-8dc6-76948003e951.png" width="700" height="400"/>
<br/>
<br/>
<br/>



## 3. 프로젝트 기획
<br/>

### <로드맵>
 - RoadMap<br/>
 <img src="https://github.com/JUICE-JinHyeong/Review_Crawling/assets/111718162/dc83698f-88c6-4d6a-b62a-cef1217a7824.png" width="700" height="300"/>
<br/>

### <전체 아키텍쳐>
 - System Architecture<br/>
 <img src="https://github.com/JUICE-JinHyeong/Review_Crawling/assets/111718162/e46bdcec-4a13-486a-8b2a-8d4d50da0b63.png" width="700" height="450"/>


<details>
<summary><head> Architecture 상세보기 </head></summary>

- 서버<br/>
<img src="https://github.com/JUICE-JinHyeong/Review_Crawling/assets/111718162/ec32a6ea-6b9a-469c-ae91-38c82aec9b8b.png" width="700" height="400"/>

- 데이터베이스<br/>
<img src="https://github.com/JUICE-JinHyeong/Review_Crawling/assets/111718162/9af375ba-9102-4731-a229-af36638289ea.png" width="700" height="400"/>

- 크롤링<br/>
<img src="https://github.com/JUICE-JinHyeong/Review_Crawling/assets/111718162/3bbee9fc-8edf-43fe-9588-964dc8fe2163.png" width="700" height="400"/>

- 모델<br/>
<img src="https://github.com/JUICE-JinHyeong/Review_Crawling/assets/111718162/5b975fad-3352-4d71-92b8-4ba40c57eaef.png" width="700" height="400"/>

</details>
<br/>
<br/>

## 4. 프로젝트 구성

### <개발환경>
- FrontEnd
  - React
  - Figma
- BackEnd
  - SpringBoot
- DataBase
  - Tibero6
- CD/CI/CB
  - Github, Notion
- Crawling
  - Jupyter
    python
    - Selenium
    - ChromDriver
    - Requests
    - BeautifulSoup
- 기타
  - Docker

<br/>

## 5. 프로젝트 결과물

### UI/UX
>
   1\) 검색창에 식당이름 혹은 음식 입력 시 관련 식당리스트 출력(인기검색 5위까지 확인 가능) <br/>
   2\) 식당을 선택하면 해당 식당의 상세 정보와 워드클라우드로 구현된 리뷰 키워드 확인 가능 <br/>
   3\) 리뷰 키워드 워드클라우드는 부정/중립/긍정으로 원하는 성향 선택 가능 <br/>
   4\) 워드클라우드에서 특정 키워드 선택 시 키워드가 포함된 리뷰 목록 출력 <br/>
   5\) 식당의 위치를 지도로 확인 가능
>
<details>
<summary><head> 펼치기 </head></summary>

#### 홈 화면 소개
  - home1<br/>
  <img src="https://github.com/JUICE-JinHyeong/Review_Crawling/assets/111718162/7153ae47-d9d1-460b-bfeb-972ac8e4187c" width="900" height="400"/>

#### 결과 화면 소개(워드클라우드)
  - home2<br/>
  <img src="https://github.com/JUICE-JinHyeong/Review_Crawling/assets/111718162/3cc6433f-9f8e-4e59-ac12-ccf226c394fd" width="900" height="400"/>

#### 결과화면 소개 (리뷰 성향 분류)
  - home3<br/>
  <img src="https://github.com/JUICE-JinHyeong/Review_Crawling/assets/111718162/95814414-7a96-427e-8682-63f4706a54b9" width="900" height="600"/>

### Figma 링크 (초기 기획)
https://www.figma.com/proto/EBAbsyjtL4MBG1pQRmO2Ll/4%EC%A1%B0?page-id=529%3A12536&type=design&node-id=529-14039&viewport=919%2C429%2C0.16&t=pKfsKmmK8CZdF977-1&scaling=scale-down&starting-point-node-id=529%3A14039&mode=design
</details>




<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>


