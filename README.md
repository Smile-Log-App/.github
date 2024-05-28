# 일기 작성 및 감정 분석 애플리케이션

애플리케이션은 프론트엔드와 백엔드로 구성되어 있으며, Next.js와 Node.js를 사용하여 개발되었습니다.

## 구성 요소

1. **Next.js 프론트엔드**
   - 일기 작성 (텍스트 에디터)
   - 제출하기 버튼 클릭 → Node.js 서버로 API 호출

2. **Node.js 백엔드**
   - Next.js 프론트엔드로부터 일기 내용 수신
   - Naver Sentiment API로 감정 분석 요청

3. **Naver Sentiment API**
   - 감정 분석 수행 후 결과를 Node.js 서버로 응답

4. **Node.js 백엔드**
   - 감정 분석 결과를 Next.js 프론트엔드로 응답

5. **Next.js 프론트엔드**
   - 감정 분석 결과 수신 및 나무로 결과값을 시각화 화면 표시

## 레포지토리 링크

- [Frontend 레포지토리](https://github.com/2024EwhaCap02/Frontend)
- [Backend 레포지토리](https://github.com/2024EwhaCap02/Backend)

프론트엔드 및 백엔드 레포지토리에 대한 자세한 내용은 각각의 링크를 클릭하여 확인하실 수 있습니다.
