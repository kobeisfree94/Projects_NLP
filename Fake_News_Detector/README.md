# Fake News Detector

**Background**

작년에 딜로이트에서 진행한 스터디에서 Fake News가 뉴스 구독자들에게 얼마나 큰 문제가 됬는지 분석한 리포트가 있었습니다. (Source: https://www2.deloitte.com/us/en/insights/industry/technology/study-shows-news-consumers-consider-fake-news-a-big-problem.html)
소셜미디어를 통한 뉴스 매채를 접하는 사람들이 증가 하면서 Fake News문제는 더 심각해 젔습니다. 

실제로 이 리포트에서는 미국에서 2020년 대선 당시 Fake News로 인한 대중의 불신이 대략 44%였고 대략적으로 84%에 사람들이 신뢰가 되는 매채에서 뉴스를 보려고 한다고 하며 Fake News의 심각성을 강조 했습니다. 

![image](https://user-images.githubusercontent.com/60637777/184073743-a6882687-3f44-47df-bdaa-1f25e3cdfc9c.png)

그런 측면에서 Fake News를 딥러닝을 활용해 Fake/Real 분류/진단을 하는 모델을 개발 하게 됐습니다. 


**1. Project Objective**
- Classify Fake News from Real News
___
**2. Project Process**
- Load Data --> Data Preprocessing -—> Check Stopwords --> Utilized Porter Stemmer to Extract Root Words --> LSTM —> Evaluate/Compare
___
**3. Data & EDA**
- Kaggle
- Data Shape (20800,5)
___
**4. Model**
- LSTM
![Screen Shot 2022-08-12 at 16 00 12](https://user-images.githubusercontent.com/60637777/184301525-e91619c7-be5f-4adc-9cc7-49fec42da43a.png)

**5. Conclusions**

![Screen Shot 2022-08-12 at 16 01 48](https://user-images.githubusercontent.com/60637777/184301784-d41be81c-abc1-4cee-ab8e-8ebdcf8d769f.png)
![Screen Shot 2022-08-12 at 16 02 00](https://user-images.githubusercontent.com/60637777/184301814-39416ce5-8038-44b7-ba4f-340f337f554a.png)

*- The model's performance/accuracy was 0.9127 and the loss was 0.2180*

