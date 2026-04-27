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

연도|활동|내용|결과
:---:|:---|:---|:---:|
2025|교내 해커톤|AI 기반 학습 도우미 개발|🥇대상
2024|오픈소스 기여|문서 번역 & 버그 수정 PR|✅머지됨
2024|코딩 동아리|웹개발팀 팀장, 스터디 운영|👑팀장
2023|정보처리기사|필기 & 실기 합격|📜취득
***
## 5. 올해 목표
#### 🟣 단기 목표 (상반기) 
- [x] GitHub 잔디 100일 채우기
- [x] 첫 개인 프로젝트 배포하기
- [x] 오픈소스 첫 기여 성공
- [ ] React 토이 프로젝트 완성하기
- [ ] 알고리즘 문제 100개 풀기

#### 🔵 장기 목표 (하반기)
- [ ] 포트폴리오 사이트 배포
- [ ] 개발 블로그 게시글 30개 작성
***

## 6. 좋아하는 것들
1. ☕ 카페에서 혼자 코딩하기 ㅡ *특히 비 오는 날*
2. 📚 기술 블로그 읽기
   * [velog.io](https://velog.io/) ㅡ 한국 개발자 커뮤니티
   * [Medium](https://medium.com/) ㅡ 영문 기술 아티클
   * [dev.to](https://dev.to/) ㅡ 글로벌 개발자 커뮤니티
3. 😸 고양이 영상 보기 <b>(생산성 향상에 과학적으로 도움됨)</b>
4. ✈️ 새로운 도시 탐방하기 ㅡ 올해 목표는 런던!
***
## 연락하기
프로젝트 협업, 스터디 제안, 질문 뭐든 환영해요!
채널|주소|응답 속도
:---|:---|:---:
📧 이메일|[email@email.com](https://google.com)|24시간 이내
🐙 GitHub|[github.com/nickname0112](https://github.com/nickname0112)|상시 확인
✍️ 블로그|[velog.io/@email](https://velog.io/)|주 2회 업데이트
💼 Linkedln|[linkedin.com/in/email](https://kr.linkedin.com/)|48시간 이내
> 같이 성장하는 개발자가 되고 싶어요. 언제든 환영해요!

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
