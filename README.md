### 사전 학습된 3가지 이미지 캡셔닝 기술 모델을 fine-tuning하여 성능을 비교, 분석

#### 이미지 캡셔닝 : CNN이나 vision Transformer를 이용한 컴퓨터 비전과 자연어 처리를 결합해 이미지에 적절한 설명을 생성하는 기술입니다. Cnn 모델의 경우, 여러 layer를 거치며 이미지로부터 특징을 추출하여 벡터에 저장합니다. viT 모델은, 이미지를 여러개의 patch로 나누고 그 패치를 flatten처리하여 선형 임베딩을 형성합니다. 이 벡터들로부터 텍스트 정보를 저장하고, 자연어 처리 단계에서 human text로 변환합니다.

#### 데이터셋 : FLICKR8k

#### 사용한 모델
1. ResNet-101 + LSTM
2. swin transformer + GPT2
3. InceptionV3 + LSTM
