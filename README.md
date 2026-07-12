<div align="center">

# 👋 Hi, I'm Dongseop Kim

### 생성형 AI를 백엔드 API와 모바일 서비스에 연결하는 신입 개발자입니다.

사용자의 요구사항을 실제 기능으로 구현하고,
AI 응답을 검증하여 안정적인 서비스로 만드는 과정에 관심이 있습니다.

<br/>

<a href="https://github.com/dongseop9907">
  <img src="https://img.shields.io/badge/GitHub-dongseop9907-181717?style=flat-square&logo=github&logoColor=white"/>
</a>

</div>

<br/>

## 🙋 About Me

* TypeScript 기반의 서버리스 백엔드와 AI 서비스 연동을 공부하고 있습니다.
* Gemini를 활용한 개인 맞춤형 운동 추천 API를 개발했습니다.
* React Native와 Supabase를 활용해 운동·식단 관리 기능을 구현했습니다.
* AI 결과를 그대로 사용하는 것이 아니라 입력값 검증과 안전성 검사, fallback 처리를 적용했습니다.

<br/>

## 🛠 Tech Stack

### Main Stack

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hono-E36002?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white"/>
</p>

### AI & Computer Vision

<p>
  <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/YOLO-111F68?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
</p>

### Other Experience

<p>
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
</p>

<br/>

## 🚀 Featured Projects

### 🏋️ AI Exercise Recommendation Worker

사용자의 신체 정보, 운동 목표, 통증 부위와 운동 환경을 분석하여
개인 맞춤형 운동 계획을 생성하는 서버리스 백엔드 API입니다.

**주요 구현 내용**

* Cloudflare Workers와 Hono를 활용한 운동 추천 API 구현
* Zod를 활용한 사용자 입력값 검증
* Gemini 기반 운동 계획 생성
* 통증 부위와 제외 운동을 검사하는 안전성 검증 로직 구현
* AI 응답이 조건을 위반하거나 생성에 실패할 경우 rule-based 계획으로 전환
* 추천 결과를 Supabase 데이터베이스에 저장

**Tech Stack**

`TypeScript` `Cloudflare Workers` `Hono` `Gemini` `Zod` `Supabase`

🔗 [Repository](https://github.com/dongseop9907/Exercise_AI_Worker)

---

### 📅 Workout & Meal Calendar

AI가 생성한 운동 및 식단 계획을 날짜별로 제공하고,
사용자가 수행 상태와 달성률을 관리할 수 있도록 구현한 React Native 애플리케이션입니다.

**주요 구현 내용**

* Supabase에 저장된 AI 추천 계획 조회
* 7일간의 운동 및 식단 계획을 날짜별로 매핑
* 운동과 식단의 세부 항목별 완료 상태 관리
* 휴식일을 포함한 운동 완료율과 주간 종합 달성률 계산
* 날짜별 운동 난이도와 사용자 컨디션 기록
* 운동·식단·휴식·완료 상태를 색상으로 구분하여 시각화

**Tech Stack**

`React Native` `Expo` `TypeScript` `Supabase`

🔗 [Repository](https://github.com/dongseop9907/Calendar)

---

### ⛳ Golf Ball Detector

YOLO 객체 탐지 모델을 활용하여 이미지와 영상 속 골프공을 탐지하는
컴퓨터 비전 프로젝트입니다.

**주요 구현 내용**

* 골프공 이미지 데이터 라벨링 및 학습 데이터 구성
* Ultralytics YOLO 모델 학습
* 이미지와 영상에 대한 골프공 탐지 기능 구현
* 학습 결과 및 탐지 결과 시각화

**Tech Stack**

`Python` `YOLO` `Ultralytics` `OpenCV`

🔗 [Repository](https://github.com/dongseop9907/GolfBallDetector)

<br/>

## 🌱 Currently Improving

* Vitest를 활용한 API 및 안전성 검증 로직 테스트
* Supabase Auth와 JWT 기반 사용자 인증
* GitHub Actions를 활용한 자동 빌드 및 테스트
* React Native 컴포넌트 구조와 상태 관리 개선

<br/>

## 📫 Contact

* GitHub: [dongseop9907](https://github.com/dongseop9907)
