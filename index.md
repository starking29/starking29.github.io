# AWS:REINVENT 2021

세션 선택시 가장 우선으로 생각했던 것
- 나의 AWS 수준에 맞는가?
- 나의 영어레벨에 맞는가?
- 현재 나의 업무에 어울리는가?

결론
- 100, 200 같은 낮은 난이도 (난이도는 100~400 까지 100단위로 있음) 
- 개발자들이 발표하는 것 
- Lambda, serverless, front-end 등등의 주제 위주

## LAB: Building a RESTful API using serverless on AWS
- 1시간 반동안 직접 aws를 이용해 프로그래밍을 해볼 수 있는 세션
- 노트북이나 AWS 계정을 따로 준비할 필요가 없음
- breakout 세션은 웬만하면 기다리다 들어가서 들을 수 있지만 LAB 세션은 자리가 정해져 있으므로 예약이 필수

![Alt text](/images/lab003.jpg)
이번 LAB의 개요를 알리고 중간중간 설명이 필요한 단계에서 설명해주는 진행자가 있음.

주요 미션은...
1. DynamoDB를 이용해서 테이블 생성하기
2. 파이썬으로 디비로부터 데이터를 읽고 쓰는 lambda function 작성하기
3. API gateway를 만들어 노출하고 lambda function과 연결하기
4. API gateway에 lambda authorizer 이용하여 인증 적용하기

![Alt text](/images/lab001.jpg)

![Alt text](/images/lab002.jpg)
도우미들이 많이 있어서 모르는거 물어보면 됨.

또는 막히는 곳에서 옆자리 보면 비슷한 문제로 고민하고 있음. 그사람이 도우미 불러서 물어보고 답 얻으면 같이 따라서 진행...




파이썬 소스도 다 제공되고, 웬만하면 모든 사람들이 좋은 결과를 얻고 나갈수 있음

무엇보다 가이드 문서가 너무너무 잘 작성되어 있음!!!

## Breakout Session: Accelerate front-end web and mobile development with AWS Amplify

amplify 개발자가 amplify 로 어플리케이션을 만들어 보면서 설명하는 세션
![Alt text](/images/amplify003.png)
![Alt text](/images/amplify002.png)

- amplify로 build(데이터 모델링/백엔드부터 프론트앤드 까지 개발), ship(배포), scale(사용자 요구에 따른 확장)을 한번에!

![Alt text](/images/amplify001.png)

- 빠르고 쉽게 풀스텍 개발을 하여 웹사이트를 띄울수 있다!
- react, vue, angular, nextjs, react native... 인기있는 원하는 모든 framework 지원!
- 오프라인 모드를 지원하는 Data storage 지원
- 서버사이드 랜더링도 지원 (amplify 라이브러리)
- 간편한 CI/CD 세팅
- map, AI/ML 같은 기능을 붙이기도 용이함 (시연당시에는 Aplify geo를 통해 맵나오는 걸 보여줌)
- Amplify Studio : https://sandbox.amplifyapp.com/


## 그 밖에..

인기있는 세션은 overflow 라고 적힌 세션이 하나씩 더 생기는데 실시간 영상으로 볼 수 있는 상영관에서 보는 방식 (한 방에 3개의 화면)

![Alt text](/images/overflow.jpg)

키노트나 리더쉽 세션 같은 큰 규모의 세션은 번역기가 마련되어 있음.

![Alt text](/images/translation001.jpg)

![Alt text](/images/translation002.jpg)
