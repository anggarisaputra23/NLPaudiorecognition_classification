# NLPaudiorecognition_classification
This repository would escort you to a project which use finetuned pre-trained model to recognize and classify audio file.

## Introduction
Speech recognition is a methodologies and technologies that enable the recognition and translation of spoken language into text by computers. It is also known as automatic speech recognition (ASR). ASR help human for interacting to computer by gives the machine to understand what was said and its speech patterns, speaking styles, dialects, accents and phrases.

## Problem
How to recognize sentences from multilingual audio recordings and understand the intent

## Solution
Establishing machine learning model from pre-trained model, such as whisper and wave2vec2) and using minds14 dataset to finetune the model.

## Dataset used
The dataset used are resourced from the paper by Gerz et al. termed MInDS-14. The dataset contains multilingual and cross-lingual intent detection from spoken data. The dataset includes 14 intents that were identified in a commercial e-banking system. Each intent is associated with spoken examples across 14 distinct language varieties.

Language Varieties:
0: cs-CZ : Czech language used in the Czech Republic
1: de-DE : German language used in Germany 
2: en-AU : English language used in Australia
3: en-GB : English language used in the United Kingdom
4: en-US : English language used in the United States
5: es-ES : Spanish language used in Spain
6: fr-FR : French language used in France
7: it-IT : Italian language used in Italy
8: ko-KR : Korean language used in South Korea
9: nl-NL : Dutch language used in the Netherlands
10: pl-PL : Polish language used in Poland
11: pt-PT : Portuguese language used in Portugal
12: ru-RU : Russian language used in Russia
13: zh-CN : Mandarin Chinese language used in mainland China

Intent Varieties:
0: abroad
1: address
2: app_error
3: atm_limit
4: balance
5: business_loan
6: card_issues
7: cash_deposit
8: direct_debit
9: freeze
10: high_value_payment
11: joint_account
12: latest_transactions
13: pay_bill

## Summary of the results 
1. Text Classification

![image](https://github.com/user-attachments/assets/b9cf0209-c450-405a-a72a-f08140fe701e)

3. Audio Recognition

![image](https://github.com/user-attachments/assets/d2e859ba-0dce-4c7d-8150-e4598f315c51)

## Inference
![image](https://github.com/user-attachments/assets/5b002c47-7d22-4d5d-9468-e976a79bfaff)





