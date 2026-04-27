# 홍길동의 자기소개

경기도 고양시 · 일산직업능력개발원 · 2025.04.27 작성
***
>"코드 한 줄이 세상을 바꿀 수 있다고 믿는 사람입니다."
>> ㅡ 열심히 하겠습니다!
***
## 1. 소개

안녕하세요! 저는 웹 개발과 오픈소스에 관심이 많은 개발자입니다. 처음 ```Hello, World!```를 출력하던 날부터 개발이 제 일상이 됐어요.

낯선 것에 도전하는 걸 좋아하고, 배운 걸 꼭 기록으로 남기는 습관이 있어요. <s>처음엔 귀찮았지만</s> 지금은 없으면 안 되는 루틴이에요.
***
## 2. 기술 스택

### 잘 다루는 것
 - HTML/CSS ㅡ 웹 페이지 구조와 스타일링
 - Python ㅡ 데이터 분석, 간단한 자동화
 - Git ㅡ 버전 관리, 협업
 - SQL ㅡ 데이터베이스 기초

### 배우는 중
#### 프론트엔드
 - *JavaScript* ㅡ 기초 완료
 - *React* ㅡ 컴포넌트 공부 중
 - *TypeScript* ㅡ 입문 단계

#### 백엔드
 - *Node.js* ㅡ 기초 공부 중
 - *Django* ㅡ 토이 프로젝트 경험
 - *Docker* ㅡ 개념 파악 중
***

## 3. 프로젝트

### 🌐 날씨 알리미 웹앱 [^1]
Python과 OpenWeatherMap API를 이용해 만든 날씨 조회 서비스예요.

```Python
# 날씨 API 호출 예시
import requests

def get_weather(city):
    url = f"https://api.openweathermap.org/data/2.5/weather?q={city}"
    response = requests.get(url)
    return response.json()

data = get_weather("Seoul")
print(f"현재 기온: {data['main']['temp']}°C")
```
- 개발 기간: 2024.09 ~ 2024.10 <b>(6주)</b>
- 사용 기술: ```Python```, ```Flask```, ```HTML/CSS```
- GitHub: [깃허브바로가기](https://github.com/nickname0112)

### 📝 마크다운 블로그 [^2]
마크다운으로 글을 쓰면 <b>자동으로 HTML로 변환</b>해주는 블로그 엔진이에요.
***
## 4. 활동 이력



<!--
**nickname0112/nickname0112** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
