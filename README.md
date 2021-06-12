# KoBERT Emotion Classification for KoGPT2 chatbot

KoGPT2 chatbot에서 생성된 답변에 감정을 분류한다면 결과가 어떻게 나올지 시도 

1. [EC_data](https://github.com/forallx94/EC_data.git) : 여러 한국어 감정 분류 데이터를 하나로 통합
2. [KoGPT2-chatbot](https://github.com/forallx94/KoGPT2-chatbot) : 통합된 데이터를 질문으로 하여 답변 데이터 생성
3. KoBERT_EC : 통합된 데이터를 Train data set 으로 하여 KoBERT Emotion Classification 훈련 해당 결과를 이용하여 KoGPT2-Chatbot의 감정 분류 진행

Colab을 이용하여 훈련 및 성능 평가 진행

repo : https://github.com/afnf33/emoTale