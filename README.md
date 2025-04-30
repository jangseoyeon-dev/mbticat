# 🐾 MBTI Cat Matcher

당신의 **MBTI 성격 유형**에 따라 가장 잘 어울리는 고양이를 추천해주는 서비스입니다!  
성격 유형을 기반으로 귀엽고 개성 넘치는 고양이들과 연결되는 재미를 느껴보세요.  

## 🌟 소개

**MBTI Cat Matcher**는 사용자의 MBTI 유형을 입력받아, 해당 성격과 어울리는 고양이 품종 또는 특징을 가진 고양이를 추천하는 웹 서비스입니다.

- 16가지 MBTI 성격 유형을 기반으로 한 고양이 추천
- 각 고양이에 대한 설명, 이미지, 성격 정보 제공
- 직관적인 UI로 간편한 사용성

## 🛠️ 기술 스택

- **Frontend**: React (CRA 기반)
- **UI 프레임워크**: Bootstrap, React-Bootstrap
- **스타일링**: Styled-components
- **라우팅**: React Router v6
- **테스트**: Testing Library (React, Jest, User Event)
- **기타**: Web Vitals

## 📸 주요 기능

| 기능               | 설명 |
|------------------|------|
| MBTI 선택         | 사용자가 자신의 MBTI를 선택 |
| 고양이 추천       | 해당 MBTI에 맞는 고양이 정보 출력 |
| 고양이 상세 정보   | 고양이 사진, 특징, 성격 등 보여주기 |
| 카카오톡 공유하는 기능  | 결과 내용을 카카오톡으로 공유 기능 제공 |
| 반응형 디자인     | 모바일/PC 환경에서 최적화된 UI 제공 |

## 🐱 예시 결과

- **ISTJ** → 브리티시 쇼트헤어: 조용하고 침착한 성격
- **ENFP** → 벵갈: 활동적이고 호기심 많은 성격
- **INFJ** → 러시안블루: 신비롭고 독립적인 분위기

## 📂 프로젝트 구조 (예시)

```
src/
├── components/
│   └── KakaoShareButton.jsx
├── pages/
│   ├── Home.jsx
│   ├── Question.jsx
│   ├── Result.jsx
├── App.js
└── index.js
```

## 🚀 시작 방법

```bash
# 1. 저장소 클론
git clone https://github.com/your-username/catmbti.git

# 2. 의존성 설치
npm install

# 3. 로컬 서버 실행
npm start
```
