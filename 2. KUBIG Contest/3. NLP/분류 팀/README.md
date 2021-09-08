# 뉴스 인사이드 아웃: 뉴스 제목을 통한 다중 감성 분석

KUBIG NLP Contest: 텍스트 분류팀

발표 자료: [뉴스 제목을 통한 다중 감성 분석 (뉴스 인사이드 아웃)](https://drive.google.com/file/d/1bucqCjD_aoZwdxMxOLmzfuwqFOrq2tX1/view?usp=sharing)

## 😘 뉴스 인사이드 아웃
+ **Members:** 13기 김현지, 13기 박주영

+ **팀 노션:** [뉴스 인사이드 아웃 팀 노션](https://blue-tendency-b6e.notion.site/KUBIG-NLP-CONTEST-b1be28028c124cf6b931ad2c233aa4b6)

## 🔍 분석 주제
> 뉴스 제목을 보고, 독자들의 반응 예측해보기
+ 네이버 뉴스 독자들은 해당 뉴스 기사에 대해 '좋아요, 훈훈해요, 슬퍼요, 화나요, 후속기사 원해요'의 총 5가지의 감정표현을 할 수 있다.
+ 본 프로젝트에서는 뉴스 데목을 통해 이러한 독자들의 반응을 예측해보고자 한다.

## 🖥 프로세스
**1. 데이터 수집:** 네이버 뉴스 기사 크롤링 
      
      각 뉴스별 헤드라인 제목, 반응별 공감수 수집
      
**2. 데이터 전처리:** 라벨링, 불용어 제거, 토큰화, 패딩

**3. 모델링:**

    3-1) 자료의 불균형 문제 해결: SMOTE, class weight, focal loss
    
    3-2) 모델: KoBERT, LSTM, RF, SVM, NB, LR
    
**4. 결과 분석**
