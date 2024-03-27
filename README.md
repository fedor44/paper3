# paper3

** openai 이용 뉴스 데이터 감성 분석

** 0, 1, 2 비율 확인 

** 아래 데이터 로드
1. pd.read_csv('/content/drive/MyDrive/paper/financial_news_with_sentiment_1000.csv')
2. pd.read_csv('/content/drive/MyDrive/paper/auditor_sentiment_only.csv')

** 위 데이터 합치는 작업 함

** 아래 데이터 로드 후 GPT로 감성 분석 그리고 몇 개가 틀린지 확인 (95.5% 동일)
1. load_dataset('financial_phrasebank', 'sentences_allagree')

** GPT-4(gpt-4-0125-preview)로 financial_news 감성 분석
