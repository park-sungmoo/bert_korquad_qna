
Colab환경에서 Tensorflow를 이용해 bert finetuning MRC korquad데이터셋으로 QnA를 구현한 코드입니다.

train,test 2개의 파일로 나누었습니다.

# bert_korquad_train.ipynb   
korquad 데이터셋 다운로드, bert에 학습, 성능확인, 가중치 저장

# bert_korquad_test.ipynb   
모델 구축, 가중치 불러오기, Context와 Question로 모델 predict, QnA 확인

참고자료:
텐서플로우2와 머신러닝으로 시작하는 자연어처리 깃허브 소스코드   
https://github.com/NLP-kr/tensorflow-ml-nlp-tf2/blob/master/7.PRETRAIN_METHOD/7.2.5.bert_finetune_KorQuAD.ipynb


KOCW AI 정보보호 서비스 챗봇 강의 동영상   
http://kocw.net/home/search/kemView.do?kemId=1379784
