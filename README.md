# covid19_crawler
주제 : 경상남도 지역별 코로나19 확진자 수 (8조)

프로젝트 내용 :

경상남도 코로나19 현황을 알려주는 사이트에서 지역별(시·군별) 확진자 수가 정리된 표를 크롤링하여,

확진자 수의 총계와 금일의 확진자 수를 두 개의 막대그래프로 나타내 비교해 볼 수 있는 프로그램을 작성하려고 한다.

지역 이름을 x축, 총 확진자 수와 금일의 확진자 수를 y축으로 하여 matplotlib를 이용해 두 개의 막대그래프로 나타낸다.

202155123 김유찬 역할 :

크롤링 - '코로나19경남' 사이트에서 제공하는 경상남도 확진자 분포도의 BeautifulSoup을 이용해 확진자 수치 정보를 담고 있는 전체 테이블을 찾아 반환 후, y축의 총 확진자 수 리스트, 금일의 확진자 수 리스트를 각각 생성한다.

그래프 - y축 리스트와 김지예가 반환한 x축 리스트를 이용해 <지역별 확진자 수의 총계> 그래프1을 제작한다. (빨간색 막대 그래프)

202155126 김지예 역할 :

크롤링 - 김유찬이 찾은 전체 테이블에서 x축의 지역 이름 리스트를 생성한다.

그래프 - <지역별 금일의 확진자 수> 그래프2를 추가적으로 제작하여 시각적으로 나타낸다. (파란색 막대 그래프)

크롤링할 사이트 URL :

http://xn--19-q81ii1knc140d892b.kr/main/main.do
