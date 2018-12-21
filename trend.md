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
2. [MM (ACM Multimedia Conference)](#MM)
3. [NIPS](#NIPS)
4. [SIGIR](#SIGIR)
5. [ICCV (International Conference on Computer Vision)](#ICCV)
6. [ECCV (European Conference on Computer Vision)](#ECCV)
7. [ACCV (Asian Conference on Computer Vision)](#ACCV)
8. [ICMR (ACM International Conference on Multimedia Retrieval)](#ICMR)
9. [AVSS (IEEE International Conference on Advanced Video and Signal-Based Surveillance)](#AVSS)
+ BMVC (British Machine Vision Conference) 
+ MMSP (IEEE Workshop on Multimedia Signal Processing)
+ ICIP (IEEE International Conference on Image Processing)

### 학술지 리스트 조사
1. [IEEE Transactions on Multimedia (IF: 3.977)](#ieee-transactions-on-multimedia)
2. [IEEE Transactions on Image processing (IF: 5.071)](#ieee-transactions-on-image-processing)
3. [IEEE Transactions on Circuits and Systems for Video Technology (IF: 3.558)](#ieee-transactions-on-circuits-and-systems-for-video-technology)
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
    - Citations: 119
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
  - Video summarization using singular value decomposition. (2000)
    - Gong, Yihong, and Xin Liu. 
    - Citations: 206
  - Video summarization by learning submodular mixtures of objectives. (2015)
    - Gygli, Michael, Helmut Grabner, and Luc Van Gool.
    - Citations: 148
  - Summary transfer: Exemplar-based subset selection for video summarization. (2016)
    - Zhang, Ke, et al.
    - Citations: 74
  - Highlight detection with pairwise deep ranking for first-person video summarization. (2016)
    - Yao, Ting, Tao Mei, and Yong Rui.
    - Citations: 77
  - From keyframes to key objects: Video summarization by representative object proposal selection. (2016)
    - Meng, Jingjing, et al. 
    - Citations: 39
  - Unsupervised video summarization with adversarial lstm networks. (2017)
    - Mahasseni, Behrooz, Michael Lam, and Sinisa Todorovic.
    - Citations: 48
  - Enhancing video summarization via vision-language embedding. (2017)
    - Plummer, Bryan A., Matthew Brown, and Svetlana Lazebnik. 
    - Citations: 23


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
  - Video summarization based on user log enhanced link analysis. (2003)
    - Yu, Bin, et al.
    - Citations: 112
  -  Dynamic video summarization and visualization. (1999)
    - Nam, Jeho, and Ahmed H. Tewfik.
    - Citations: 74

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
  - Automatic video summarization by graph modeling. (2003)
    - Ngo, Chong-Wah, Yu-Fei Ma, and Hong-Jiang Zhang.
    - Citations: 121

### ECCV
  - Creating summaries from user videos. (2014)
    - Gygli, Michael, et al.
    - Citations: 210
  - Category-specific video summarization. (2014)
    - Potapov, Danila, et al. 
    - Citations: 175
  - Video summarization with long short-term memory. (2016)
    - Zhang, Ke, et al.
    - Citations: 127
  - Retrospective Encoders for Video Summarization. (2018)
    - Zhang, Ke, Kristen Grauman, and Fei Sha.
    - Citations: 2
  - Query-focused extractive video summarization. (2016)
    - Sharghi, Aidean, Boqing Gong, and Mubarak Shah. 
    - Citations: 29
  - How Local is the Local Diversity? Reinforcing Sequential Determinantal Point Processes with Dynamic Ground Sets for Supervised Video Summarization. (2018)
    - Li, Yandong, et al. 
    - CitationsL 42

### ACCV
  - Video summarization using deep semantic features. (2016)
    - Otani, Mayu, et al. 
    - Citations: 19

### ICIP
  - Bayesian modeling of video editing and structure: Semantic features for video summarization and browsing. (2998)
    - Vasconcelos, Nuno, and Andrew Lippman. 
    - Citations: 114
  - Video summarization with minimal visual content redundancies. (2001)
    - Gong, Yihong, and Xin Liu.
    - Citations: 61

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
  - Event driven web video summarization by tag localization and key-shot identification. (2012)
    - Wang, Meng, et al. 
    - Citations: 203
  - Multi-view video summarization. (2010)
    - Fu, Yanwei, et al. 
    - Citations: 135
  - A novel video summarization based on mining the story-structure and semantic relations among concept entities. (2009)
    - Chen, Bo-Wei, Jia-Ching Wang, and Jhing-Fa Wang.
    - Citations: 124
  - A bag-of-importance model with locality-constrained coding based feature learning for video summarization. (2014)
    - Lu, Shiyang, et al. 
    - Citations: 52

### IEEE Multimedia
  - Highlights for more complete sports video summarization. (2004)
    - Tjondronegoro, Dian, Yi-Ping Phoebe Chen, and Binh Pham.


### IEEE Transactions on Image processing
  - Automatic soccer video analysis and summarization. (2003)
    - Ekin, Ahmet, A. Murat Tekalp, and Rajiv Mehrotra. 
    - Citations: 983
  - Video summarization via multi-view representative selection. (2018)
    - Meng, Jingjing, et al.
    - Citations: 4
  - "Context-Aware Surveillance Video Summarization. (2016)
    - Zhang, Shu, Yingying Zhu, and Amit K. Roy-Chowdhury. 
    - Citations 15


### IEEE Transactions on Circuits and Systems for Video Technology
  - Video summarization and scene detection by graph modeling. (2005)
    - Ngo, Chong-Wah, Yu-Fei Ma, and Hong-Jiang Zhang.
    - Citations: 377
  - Information theory-based shot cut/fade detection and video summarization. (2006)
    - Cernekova, Zuzana, Ioannis Pitas, and Christophoros Nikou.
    - Citations: 341
  - A multiple visual models based perceptive analysis framework for multilevel video summarization. (2007)
    - You, Junyong, et al.
    - Citations: 134
  - MINMAX optimal video summarization. (2005)
    - Li, Zhu, Guido M. Schuster, and Aggelos K. Katsaggelos. 
    - Citations: 122
  - Video Summarization by Learning Deep Side Semantic Embedding. (2017)
    - Yuan, Yitian, et al. 
    - Citations: 6
  - Event detection and summarization in soccer videos using bayesian network and copula.
    - Tavassolipour, Mostafa, Mahmood Karimian, and Shohreh Kasaei. (2014)
    - Citations: 49

### International Journal of Computer Graphics
  - Fast highlight detection and scoring for broadcast soccer video summarization using on-demand feature extraction and fuzzy inference. (2015)
    - Sigari, Mohamad-Hoseyn, Hamid Soltanianzadeh, and Hamid Reza Pourreza. 
    -Citations: 8

### International Journal of Computer Vision
  - Predicting important objects for egocentric video summarization. (2015)
    - Lee, Yong Jae, and Kristen Grauman.
    - Citations: 79

### Pattern Recognition
  - Video summarization via minimum sparse reconstruction. (2015)
    - Mei, Shaohui, et al.
    - Citations: 86

### arXiv 논문
  - Video Summarisation by Classification with Deep Reinforcement Learning. (2018)
    - Zhou, Kaiyang, Tao Xiang, and Andrea Cavallaro.
    - arXiv preprint arXiv:1807.03089

### IEEE Transactions on Affective Computing
Xu, Baohan, et al. 
"Heterogeneous knowledge transfer in video emotion recognition, attribution and summarization."
IEEE Transactions on Affective Computing 9.2 (2018): 255-270.

### Signal Processing
Doulamis, Anastasios D., Nikolaos D. Doulamis, and Stefanos D. Kollias.
"A fuzzy video content representation for video summarization and content-based retrieval."
Signal Processing 80.6 (2000): 1049-1067.

### Signal Processing: Image Communication

Ejaz, Naveed, Irfan Mehmood, and Sung Wook Baik.
"Efficient visual attention based framework for extracting key frames from videos."
Signal Processing: Image Communication 28.1 (2013): 34-44.
Citations: 121

Fonseca, Pedro Miguel, and Fernando Pereira.
"Automatic video summarization based on MPEG-7 descriptions."
Signal Processing: Image Communication 19.8 (2004): 685-699.
Citations: 36

### International Journal on Digital Libraries
Mundur, Padmavathi, Yong Rao, and Yelena Yesha.
"Keyframe-based video summarization using Delaunay clustering."
International Journal on Digital Libraries 6.2 (2006): 219-232.
Citations: 241

### Journal of Real-Time Image Processing
Gianluigi, Ciocca, and Schettini Raimondo.
"An innovative algorithm for key frame extraction in video summarization."
Journal of Real-Time Image Processing 1.1 (2006): 69-88.
Citations: 186

### Journal of Visual Communication and Image Representation
Ejaz, Naveed, Tayyab Bin Tariq, and Sung Wook Baik.
"Adaptive key frame extraction for video summarization using an aggregation mechanism."
Journal of Visual Communication and Image Representation 23.7 (2012): 1031-1040.
Citations: 126

### Pattern Racognition Letters
Almeida, Jurandy, Neucimar J. Leite, and Ricardo da S. Torres.
"Vison: Video summarization for online applications."
Pattern Recognition Letters 33.4 (2012): 397-409.
Citations: 112

### IEEE Trans. Industrial Electronics
Zhang, Luming, et al.
"An Effective Video Summarization Framework Toward Handheld Devices."
IEEE Trans. Industrial Electronics 62.2 (2015): 1309-1316.
Citations: 60

### IEEE Journal of Selected Topics in Signal Processing
Ou, Shun-Hsing, et al.
"On-line multi-view video summarization for wireless video sensor network."
IEEE Journal of Selected Topics in Signal Processing 9.1 (2015): 165-179.

### IEEE/IFIP International Conference on Dependable Systems and Networks
Venkatagiri, Radha, et al. 
"Impact of Software Approximations on the Resiliency of a Video Summarization System."
2018 48th Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN). IEEE, 2018.

### Pervasive and Mobile Computing
Hamza, Rafik, et al.
"Secure video summarization framework for personalized wireless capsule endoscopy."
Pervasive and Mobile Computing 41 (2017): 436-450.

### Multimedia Tools and Applications
Wu, Jiaxin, et al.
"A novel clustering method for static video summarization."
Multimedia Tools and Applications 76.7 (2017): 9625-9641.

### Journal of medical systems
Mehmood, Irfan, Muhammad Sajjad, and Sung Wook Baik. 
"Video summarization based tele-endoscopy: a service to efficiently manage visual data generated during wireless capsule endoscopy procedure." (2014)
Citations: 33

### 동영상 관련
Xu, Jun, et al.
"Msr-vtt: A large video description dataset for bridging video and language."
Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2016
Citations: 176

### 얼굴 관련
Chopra, Sumit, Raia Hadsell, and Yann LeCun.
"Learning a similarity metric discriminatively, with application to face verification."
Computer Vision and Pattern Recognition, 2005. CVPR 2005.
IEEE Computer Society Conference on. Vol. 1. IEEE, 2005.
Citations: 1322

### 학습 관련
Maaten, Laurens van der, and Geoffrey Hinton.
"Visualizing data using t-SNE."
Journal of machine learning research 9.Nov (2008): 2579-2605.

### 마이너 학회
Li, Yujie, et al.
"Extracting key frames from first-person videos in the common space of multiple sensors."
Image Processing (ICIP), 2017 IEEE International Conference on. IEEE, 2017.
Citations: 2

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

Vasconcelos, Nuno, and Andrew Lippman.
"A spatiotemporal motion model for video summarization."
Computer Vision and Pattern Recognition, 1998. Proceedings.
1998 IEEE Computer Society Conference on. IEEE, 1998.
Citations: 87

Salehin, Md Musfequs, and Manoranjan Paul.
"Fusion of Foreground Object, Spatial and Frequency Domain Motion Information for Video Summarization."
Pacific-Rim Symposium on Image and Video Technology. Springer, Cham, 2015.
Citations: 7

Chakraborty, Shayok, Omesh Tickoo, and Ravi Iyer.
"Adaptive keyframe selection for video summarization."
Applications of Computer Vision (WACV), 2015 IEEE Winter Conference on. IEEE, 2015.
Citations: 25

Viguier, Raphael, et al.
"Automatic video content summarization using geospatial mosaics of aerial imagery."
Multimedia (ISM), 2015 IEEE International Symposium on. IEEE, 2015.
Citations: 4

## 2. 주요 학회/학술지에 발표된 Video Key-frame Extraction 연구 논문 수

### 이 분야의 권위자, 학교, 연구소 조사
