# 재난지원금에 대한 보수성향 신문사와 진보성향 신문사의 사설 비교분석-평가어 체계를 기반으로

<b>A comparative study of conservative and progressive editorials on COVID-19 relief fund based on appraisal theory</b>   

### 1. Abstract
This paper aims to compare and analyze conservative and progressive editorials on COVID-19 relief funds based on appraisal theory of Martin and White (2005). The study is twofold: one is to classify editorials by positive/negative/neutral stance. As a result, it is found that conservative editorials mostly show negative stance while more than half of progressive editorials show positive stance. The other is to analyze appraisals represent attitude and graduation in the editorials. As a result, attitude appraisal in both conservative and progressive editorials can be classified into subjects of COVID-19 relief funds. For graduation appraisal, adverb ‘또(tto), again’ emphasizes negative appraisal in both conservative and progressive editorials.

### 2. File explanation

#### Crawling
한국언론진흥재단 빅데이터 분석 시스템 사이트인 빅카인즈(https://www.bigkinds.or.kr/v2/news/index.do) 에서 재난지원금을 키워드로 한 신문사설을 크롤링한 뒤 데이터가 본문전체를 제공하지 않기 때문에 별도로 제작한 크롤링코드입니다. 각 신문사(조선일보, 중앙일보, 경향신문, 한겨레)마다 제목과 본문의 신문기사를 수집하였고 각 신문사 홈페이지마다 제목과 본문을 나타내는 html태그가 다르기 때문에 별도의 코드로 변환하여 제작하였습니다.  
- 주의사항: python selenium으로 크롤링을 진행합니다. selenium은 webdriver라는 api를 통해 chrome 등의 브라우저를 제어하고 이를 위해서는 자신의 컴퓨터가 현재 사용하는 버전의 chrome driver를 함께 설치해주어야합니다. 사용하고 있는 chrome의 버전정보는 여기(chrome://version/)에서 확인할 수 있고, 이에 맞는 chrome드라이버를 오른쪽의 링크(https://chromedriver.chromium.org/downloads)를 통해 다운로드 받으시길 바랍니다. 현 레포지토리에서 다운받은 chrome driver는 95.0버전입니다.

#### Data
excel에서 사설 제목과 본문에 '재난지원금'이라는 키워드가 나타나는 경우 문자열을 다른 색으로 변환하는 매크로를 활용해 불필요한 데이터를 정제하였습니다. 또한, 그 중에서도 재난지원금에 대한 평가가 잘 드러나는 신문사설을 선별한 데이터입니다. 보수성향 사설과 진보성향 사설 모두 76개이며 해당 파일들은 재난지원금에 대한 긍정/부정/중립 평가와 평가가 잘 드러나는 표현들에 색표시(긍정 파랑, 부정 빨강, 중립 강조)를 완료한 최종데이터입니다. 
