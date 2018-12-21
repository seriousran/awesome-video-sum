# 기술 트렌드 파악

1. 주요 학회/학술지에 발표된 딥러닝 기반 Video Summarization 연구 논문 수
    + github repositories 조사
    + 딥러닝 기반 O/X 로 나누고, 기술 성능 향상 평가
2. 세부적 성능을 그래프로 정리
3. 논문 스터디
    1. 빠른 요약: 핵심 기여, 논문 결과 위주로 논문 당 최대 2슬라이드로 정리
    2. 세부 리뷰: 결과에 대한 타당성 검증 위주로 논문 당 최대 10 슬라드로 정리
    3. 기술 분류 및 트렌드 분석

## 기술 세분화

1. Video Summarizagion (Highlighting)
2. Key-frame extraction
+ Face Detection & Recognition
+ Visual Recognition
+ Video Transition Detection

## 1. 주요 학회/학술지에 발표된 Video Summarization 연구 논문 수

### Video Summarization 및 관련 AI 분야 주요 학회 리스트 조사
1. [CVPR (Conference on Computer Vision and Pattern Recognition)](#CVPR)
2. MM (ACM Multimedia Conference)
3. NIPS
4. SIGIR
5. ICCV (International Conference on Computer Vision)
6. ECCV (European Conference on Computer Vision)
7. ACCV (Asian Conference on Computer Vision)
8. ICMR (ACM International Conference on Multimedia Retrieval)
9. AVSS (IEEE International Conference on Advanced Video and Signal-Based Surveillance)
+ BMVC (British Machine Vision Conference) 
+ MMSP (IEEE Workshop on Multimedia Signal Processing)
+ ICIP (IEEE International Conference on Image Processing)

### 학술지 리스트 조사
1. IEEE Transactions on Multimedia (IF: 3.977)
2. IEEE Transactions on Image processing
3. IEEE Transactions on Circuits and Systems for Video Technology
4. arXiv

### CVPR
  - Gaze-enabled egocentric video summarization via constrained submodular maximization. (2015)
    - Xu, Jia, et al. 
    - Citations: 88
  - Large-scale video summarization using web-image priors. (2013)
    - Khosla, Aditya, et al.
    - Citations: 172
  - Quasi real-time summarization for consumer videos. (2014)
    - Zhao, Bin, and Eric P. Xing. 
  - Story-driven summarization for egocentric video. (2013)
    - Lu, Zheng, and Kristen Grauman.
    - Citations: 339
  - Tvsum: Summarizing web videos using titles. (2015)
    - Song, Yale, et al.
    - Citations: 126
  - Video co-summarization: Video summarization by visual co-occurrence. (2015)
    - Chu, Wen-Sheng, Yale Song, and Alejandro Jaimes. 
    - Citations: 83
  - Video summarization by learning submodular mixtures of objectives. (2015)
    - Gygli, Michael, Helmut Grabner, and Luc Van Gool.
    - Citations: 148
  - Video summarization using singular value decomposition. (2000)
    - Gong, Yihong, and Xin Liu.
    - Citations: 206
  - Discovering important people and objects for egocentric video summarization. (2012)
    - Lee, Yong Jae, Joydeep Ghosh, and Kristen Grauman. 
    - Citations: 415

### MM
  - Character-based movie summarization. (2010)
    - Sang, Jitao, and Changsheng Xu.
    - Citations: 68
  - Video summarization by curve simplification. (1998)
    - DeMenthon, Daniel, Vikrant Kobla, and David Doermann.
    - Citations: 375
  - A user attention model for video summarization. (2002)
    - Ma, Yu-Fei, et al.
    - Citations: 641

### NIPS
  - Diverse sequential subset selection for supervised video summarization. (2014)
    - Gong, Boqing, et al.
    - Citations: 145

### SIGIR
  - Automatic music video summarization based on audio-visual-text analysis and alignment. (2005)
    - Xu, Changsheng, et al. 
    - Citations: 75

### ICCV
  - Unsupervised extraction of video highlights via robust recurrent auto-encoders. (2015)
    - Yang, Huan, et al.
    - Citations: 60

### ECCV
  - Creating summaries from user videos. (2014)
    - Gygli, Michael, et al.
    - Citations: 210
  - Category-specific video summarization. (2014)
    - Potapov, Danila, et al. 
    - Citations: 175

### ACCV
  - Video summarization using deep semantic features. (2016)
    - Otani, Mayu, et al. 
    - Citations: 19

### IEEE Transactions on Multimedia
  - Multimodal saliency and fusion for movie summarization based on aural, visual, and textual attention. (2013)
    - Evangelopoulos, Georgios, et al. 
    - Citations: 123
  - Personalized abstraction of broadcasted American football video by highlight selection. (2004)
    - Babaguchi, Noboru, et al. 
    - Citations: 128
  - A generic framework of user attention model and its application in video summarization. (2005)
    - Ma, Yu-Fei, et al.
    - Citations: 497

### IEEE Transactions on Image processing
  - Automatic soccer video analysis and summarization. (2003)
    - Ekin, Ahmet, A. Murat Tekalp, and Rajiv Mehrotra. 
    - Citations: 983

### IEEE Transactions on Circuits and Systems for Video Technology
  - Video summarization and scene detection by graph modeling. (2005)
    - Ngo, Chong-Wah, Yu-Fei Ma, and Hong-Jiang Zhang.
    - Citations: 377

### arXiv 논문
  - Video Summarisation by Classification with Deep Reinforcement Learning. (2018)
    - Zhou, Kaiyang, Tao Xiang, and Andrea Cavallaro.
    - arXiv preprint arXiv:1807.03089

+ 동영상 관련
Xu, Jun, et al.
"Msr-vtt: A large video description dataset for bridging video and language."
Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2016
Citations: 176

+ 얼굴 관련
Chopra, Sumit, Raia Hadsell, and Yann LeCun.
"Learning a similarity metric discriminatively, with application to face verification."
Computer Vision and Pattern Recognition, 2005. CVPR 2005.
IEEE Computer Society Conference on. Vol. 1. IEEE, 2005.
Citations: 1322

+ 학습 관련
Maaten, Laurens van der, and Geoffrey Hinton.
"Visualizing data using t-SNE."
Journal of machine learning research 9.Nov (2008): 2579-2605.

- 마이너 학회
Li, Yujie, et al.
"Extracting key frames from first-person videos in the common space of multiple sensors."
Image Processing (ICIP), 2017 IEEE International Conference on. IEEE, 2017.
Citations: 2

Ejaz, Naveed, Irfan Mehmood, and Sung Wook Baik.
"Efficient visual attention based framework for extracting key frames from videos."
Signal Processing: Image Communication 28.1 (2013): 34-44.
Citations: 121

Ai, Xin, Yan Song, and Zechao Li.
"Unsupervised Video Summarization Based on Consistent Clip Generation."
2018 IEEE Fourth International Conference on Multimedia Big Data (BigMM). IEEE, 2018.
Citations: 0

Rajpoot, Vinay, and Sheetal Girase.
"A Study on Application Scenario of Video Summarization."
2018 Second International Conference on Electronics, Communication and Aerospace Technology (ICECA). IEEE, 2018.
Citations: 0

Kuncheva, Ludmila I., Paria Yousefi, and Jurandy Almeida.
"Comparing keyframe summaries of egocentric videos: Closest-to-centroid baseline."
Proceedings of the 7th International Conference on Image Processing Theory, Tools and Applications (IPTA 2017). 2017.
Citations: 2

Mademlis, Ioannis, Anastasios Tefas, and Ioannis Pitas.
"GREEDY SALIENT DICTIONARY LEARNING WITH OPTIMAL POINT RECONSTRUCTION FOR ACTIVITY VIDEO SUMMARIZATION."
2018 IEEE 28th International Workshop on Machine Learning for Signal Processing (MLSP). IEEE, 2018.
Citations: 0

Sun, Ke, et al.
"Learning deep semantic attributes for user video summarization."
Multimedia and Expo (ICME), 2017 IEEE International Conference on. IEEE, 2017.
Citations: 1

Tejero-de-Pablos, Antonio, et al.
"Summarization of user-generated sports video by using deep action recognition features."
IEEE Transactions on Multimedia 20.8 (2018): 2000-2011.
Citations: 1

## 2. 주요 학회/학술지에 발표된 Video Key-frame Extraction 연구 논문 수

### 이 분야의 권위자, 학교, 연구소 조사
