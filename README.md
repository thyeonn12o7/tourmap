## 디지털콘텐츠프로그래밍 기말프로젝트
### TEAM D | 국내 여행 추천 가이드 제작 (TourMap)
#### • 최종 웹 서비스 (https://teamdtourguide.netlify.app)

---------------------

### 서비스 소개
> 해당 서비스는 국내 여행의 수요 증가에 따라 국내 여행을 계획하는 사람들에게 도움이 되고자 통계청 조사에 의한 광역시도 별 인기 지역을 뽑아 관광 정보를 제공한다. 서울을 기준으로 평균 이동 소요시간 및 주요 교통편, 평균 비용 등을 함께 제공하고, 한국관광공사에서 제공하는 주요 관광지 및 맛집, 카페에 대한 정보도 간략하게 제공한다. 한정된 시간으로 인해 전국 모든 지역, 더 다양한 관광지 및 맛집 소개에 한계가 있었기에 기회가 된다면 더 다양하고 많은 정보를 제공할 수 있는 서비스로 재구성해보고 싶다.

##### • 페이지 별 소개
> 서비스는 크게 세 페이지로 구성되어 있다. "HOME" 에서는 최근 국내여행 통계에 대한 간략한 개요를 소개한다. 2022년 4월 기준 국내 여행자 수, 관광 지출액, 여행 검색건수에 대한 통계자료와 광역시도 별 방문자 수 통계를 히트맵으로 제공한다. 이외에도 22년 1월부터 4월까지의 관광객 수 변화 추이를 간단한 막대그래프로 확인할 수 있다. "ABOUT" 페이지는 팀원 소개와 더불어 서비스 소개, 서비스의 기획 과정에 대한 간단한 설명을 포함한다. 해당 서비스의 메인 페이지인 "SERVICE" 에서는 전국 지도와 함께 광역시도 별 4~5개의 여행지를 추천한다. 또한, 페이지 좌측에 위치한 국내 지도를 통해 추천되는 여행지의 위치를 파악할 수 있다. 원하는 지역의 버튼을 누르면 각 지역의 관광 정보를 제공하는 "DETAILS" 로 이동하게 된다. 각 지역 별 "DETAILS" 에서는 한국관광공사에서 제공하는 주요 관광명소 6개 및 맛집/카페 등 간략한 지역의 관광정보를 사진과 함께 제공하고 있다. 음식점 및 카페는 저작권 문제로 인해 간단한 일러스트로 대체한다.

### 서비스 기획 의도
> 한국관광공사에서 제공하는 국내 여행자 수 변화 통계에 따르면, 코로나의 안정세로 인해 국내 여행자 수가 크게 증가한 것을 알 수 있다. 따라서, 국내 여행을 계획하는 사용자의 기호에 맞게 광역시도 별 여행지를 추천하는 서비스를 기획했고, 여행지의 간단한 관광정보를 제공할 수 있도록 웹 페이지를 구성하고 제작했다. 본인의 경험에 비추어 보았을 때, 특정 지역을 선정하는 데 많은 어려움을 겪었고, 유명 관광지에 대한 정보도 뿔뿔히 흩어져 있어 하나하나 찾는데 꽤 오랜 시간을 들였던 경험이 있다. 따라서, 주요 관광정보를 한 곳에 모아 제공한다면 사용자는 더욱 편리하게 정보를 얻고, 여행을 계획할 수 있을 것이라고 기대한다.

### 서비스 제작 과정
> 특정 지역을 선정하는 데는 한국관광공사에서 제공하는 통계 자료에 의해 관광객이 가장 많이 찾는 지역을 광역시도 별로 4~5개 선정했다. 해당 지역의 주요 관광명소와 정보, 사진 등은 한국관광공사 "TOUR API"를 활용해 서비스를 제작했다. 이외의 맛집 및 유명한 카페는 직접 검색을 통해 정보를 수집하고, 저작권에 위배될 수 있는 이미지는 간단한 음식 일러스트로 대체해서 제공한다. 사용자에게 효과적으로 정보를 한 번에 제공하기 위해 많은 회의를 거쳐 와이어프레임을 확정짓고, 그에 따라 웹 서비스를 제작했다.
>> • 와이어프레임 링크 (https://whimsical.com/GDP5BATeaCuDo5ymoiZoQV)
>> 
>> • 와이어프레임 (기획안)
>> <img width="962" alt="wireframe_outline" src="https://user-images.githubusercontent.com/70498745/171349797-87a3f118-a9e9-4e0f-8d1d-f31e8be88fa4.png">
>>
>> • 와이어프레임 (최종 서비스)
>> <img width="960" alt="wireframe_final" src="https://user-images.githubusercontent.com/70498745/171349957-26b047be-3de3-49fb-9af5-7130b173d848.png">

---------------------

#### Project files
1. index.html      | 서비스 메인화면 "HOME" 구성 html
2. "pages" folder  | "ABOUT" "SERVICE" "DETAILS" 등 모든 페이지의 html 파일 폴더
3. "img" folder    | 서비스 화면 구성에 필요한 모든 img 파일 폴더
4. "design" folder | 서비스 화면 구성을 위한 각 페이지 별 css 파일 폴더
5. favicon         | 서비스의 파비콘 png 파일
 
