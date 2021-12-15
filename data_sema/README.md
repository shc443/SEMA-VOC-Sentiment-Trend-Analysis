## [SEMA Group] TABSA(Target Aspect Based Sentiment Analysis) for SEMA VOC Sentiment Trend Analysis


    
TABSA involves target topic extraction **and** target sentiment classification. 
The most of the exiting methods aims to identify either target topics or general polarity over the input text, not both. In this project, we utilize KLUE RoBERTa-base model with BCE Loss for solving TABSA issues as multiclass classification problem 
    with 8 classes of VOC, (진료경험, 주차, 시설/환경, 직원, 대기시간, 시스템, 의료진, 예약/접수/수납)
    and 2 sentiment level (긍정, 부정)

