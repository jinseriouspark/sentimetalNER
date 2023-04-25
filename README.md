# Sentimental NER 모델 생성

진행 순서

1. 데이터 수집 및 전처리 
    크롤링 / 공개 자료 
2. 분류 모델 생성 및 주요 키워드 수집 : (키워드 - 감정)
    크롤링 데이터로 감정 분류
3. 개인 글 수집 
    API
4. 개인 글 속 키워드 별 감정 태깅
5. 엔티티 기반 결과 반환
    - 요약통계로 제공
    - 워드클라우드로 제공
