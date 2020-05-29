# Awesome Video Summarization [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> _A curated list of the __Video Summarization__ subject which is a computer science using machine learning and deep learning_ <br/>
> _동영상 자동 요약에 관한 큐레이션 - 머신러닝과 딥러닝 단계까지_<br/>
> _关于自动视频摘要的管理 - 使用机器学习和深度学习_

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [About Video-sum](#about-video-sum)
- [Codes](#codes)
- [Datasets](#datasets)
- [Publications](#publications)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## About Video-sum

Video summaries are one of the most important topics which you can browse large collections of videos faster and have more efficient content indexing and access. Basically, this research area consists of automatically generating short video summaries, which can be static summaries or dynamic summaries. Static video summaries consist of a series of key frames extracted from the original video, while dynamic video summaries consist of a series of shots and are created taking into account similarities or domain-specific relationships between all video shots.

### Major components

1. Key-frame extraction
    1. Using visual features
        1. Corner Feature
        2. Face Detection & Recognition
    2. Using video skimming
2. Scene change detection (=Video Transition Detection)

## Codes

- [VASNet](https://github.com/ok1zjf/VASNet)
  - Video Summarization with Attention
  - Python, PyTorch
- [Vis-DSS](https://github.com/Pratik08/vis-dss)
  - An Open-Source toolkit for Visual Data Selection and Summarization
  - C++, caffe

## Datasets

- [TREC Video](https://trecvid.nist.gov/)
- [SumMe](https://gyglim.github.io/me/vsum/index.html#benchmark)
- [TvSum](https://github.com/yalesong/tvsum)

## Publications

- Mingyang Ma, Shaohui Mei, Shuai Wan, Junhui Hou, Zhiyong Wang, David Dagan Feng, Video summarization via block sparse dictionary selection, Neurocomputing, 2020.
- Yujia Zhang, Michael C Kampffmeyer, Xiaoguang  Zhao, Min Tan, DTR-GAN: dilated temporal relational adversarial network for video summarization, ACM TURC, 2019.
- Tsu-Jui Fu, Shao-Heng Tai, Hwann-Tzong Chen, Attentive and Adversarial Learning for Video Summarization, WACV, 2019.
- Mayu Otani, Yuta Nakashima, Esa Rahtu, Janne Heikkilä, Rethinking the Evaluation of Video Summaries, CVPR, 2019.
- Yair Shemer, Daniel Rotman, Nahum Shimkin, ILS-SUMM: Iterated Local Search for Unsupervised Video Summarization, 2019.
- Meng, Jingjing, et al., Video summarization via multi-view representative selection, IEEE Transactions on Image processing, 2018.
- Venkatagiri, Radha, et al, "Impact of Software Approximations on the Resiliency of a Video Summarization System," 2018 48th Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN). IEEE, 2018.
- Xu, Baohan, et al, "Heterogeneous knowledge transfer in video emotion recognition, attribution and summarization," IEEE Transactions on Affective Computing 9.2 (2018): 255-270.
- Sijia Cai, Wangmeng Zuo, Larry S. Davis, Lei Zhang, Weakly-supervised Video Summarization using Variational Encoder-Decoder and Web Prior, ECCV, 2018.
- Zhang, Ke, Kristen Grauman, and Fei Sha., Retrospective Encoders for Video Summarization, ECCV, 2018.
- Li, Yandong, et al., How Local is the Local Diversity? Reinforcing Sequential Determinantal Point Processes with Dynamic Ground Sets for Supervised Video Summarization, 2018.
- Mohamed Elfeki, Aidean Sharghi, Srikrishna Karanam, Ziyan Wu, Ali Borji, Multi-Stream Dynamic Video Summarization, 2018.
- Rishabh Iyer, Pratik Dubal, Kunal Dargan, Suraj Kothawade, Rohan Mahadev, Vishal Kaushal, Vis-DSS: An Open-Source toolkit for Visual Data Selection and Summarization, 2018.
- Huawei Wei, Bingbing Ni, Yichao Yan, Huanyu Yu, Xiaokang Yang, Chen Yao, Video Summarization via Semantic Attended Networks, AAAI, 2018.
- Mademlis, Ioannis, Anastasios Tefas, and Ioannis Pitas, GREEDY SALIENT DICTIONARY LEARNING WITH OPTIMAL POINT RECONSTRUCTION FOR ACTIVITY VIDEO SUMMARIZATION, MLSP, 2018.
- Jiri Fajtl, Hajar Sadeghi Sokeh, Vasileios Argyriou, Dorothy Monekosso, Paolo Remagnino, Summarizing Videos with Attention, 2018.
- Zhou, Kaiyang, Tao Xiang, and Andrea Cavallaro, Video Summarisation by Classification with Deep Reinforcement Learning, 2018.
- Yuan, Yitian, et al., Video Summarization by Learning Deep Side Semantic Embedding, IEEE Transactions on Circuits and Systems for Video Technology, 2017.
- Hamza, Rafik, et al, "Secure video summarization framework for personalized wireless capsule endoscopy," Pervasive and Mobile Computing 41 (2017): 436-450.
- Wu, Jiaxin, et al, "A novel clustering method for static video summarization," Multimedia Tools and Applications 76.7 (2017): 9625-9641.
- Mahasseni, Behrooz, Michael Lam, and Sinisa Todorovic, Unsupervised video summarization with adversarial lstm networks, CVPR, 2017.
- Plummer, Bryan A., Matthew Brown, and Svetlana Lazebnik, Enhancing video summarization via vision-language embedding, CVPR, 2017.
- Arun Balajee Vasudevan, Michael Gygli, Anna Volokitin, Luc Van Gool, Query-adaptive Video Summarization via Quality-aware Relevance Estimation, ICCV, 2017.
- Li, Yujie, et al., Extracting key frames from first-person videos in the common space of multiple sensors, ICIP, 2017.
- Sun, Ke, et al., Learning deep semantic attributes for user video summarization, ICME, 2017.
- Zhong Ji, Kailin Xiong, Yanwei Pang, Xuelong Li, Video Summarization with Attention-Based Encoder-Decoder Networks, 2017.
- Kaiyang Zhou, Yu Qiao, Tao Xiang, Deep Reinforcement Learning for Unsupervised Video Summarization with Diversity-Representativeness Reward, 2017.
- Zhang, Shu, Yingying Zhu, and Amit K. Roy-Chowdhury, Context-Aware Surveillance Video Summarization, IEEE Transactions on Image processing, 2016.
- Xu, Jun, et al, "Msr-vtt: A large video description dataset for bridging video and language," Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 2016.
- Zhang, Ke, et al., Summary transfer: Exemplar-based subset selection for video summarization, CVPR, 2016.
- Yao, Ting, Tao Mei, and Yong Rui., Highlight detection with pairwise deep ranking for first-person video summarization, CVPR, 2016.
- Meng, Jingjing, et al., From keyframes to key objects: Video summarization by representative object proposal selection, CVPR, 2016.
- Zhang, Ke, et al., Video summarization with long short-term memory, ECCV, 2016.
- Sharghi, Aidean, Boqing Gong, and Mubarak Shah., Query-focused extractive video summarization, ECCV, 2016.
- Otani, Mayu, et al., Video summarization using deep semantic features, ACCV, 2016.
- Sigari, Mohamad-Hoseyn, Hamid Soltanianzadeh, and Hamid Reza Pourreza, Fast highlight detection and scoring for broadcast soccer video summarization using on-demand feature extraction and fuzzy inference, International Journal of Computer Graphics, 2015.
- Lee, Yong Jae, and Kristen Grauman, Predicting important objects for egocentric video summarization, International Journal of Computer Vision, 2015.
- Mei, Shaohui, et al., Video summarization via minimum sparse reconstruction, Pattern Recognition, 2015.
- Zhang, Luming, et al, "An Effective Video Summarization Framework Toward Handheld Devices," IEEE Trans. Industrial Electronics 62.2 (2015): 1309-1316.
- Ou, Shun-Hsing, et al, "On-line multi-view video summarization for wireless video sensor network," IEEE Journal of Selected Topics in Signal Processing 9.1 (2015): 165-179.
- Xu, Jia, et al., Gaze-enabled egocentric video summarization via constrained submodular maximization, CVPR, 2015.
- Song, Yale, et al., Tvsum: Summarizing web videos using titles, CVPR, 2015.
- Chu, Wen-Sheng, Yale Song, and Alejandro Jaimes, Video co-summarization: Video summarization by visual co-occurrence, CVPR, 2015.
- Gygli, Michael, Helmut Grabner, and Luc Van Gool., Video summarization by learning submodular mixtures of objectives, CVPR, 2015.
- Yang, Huan, et al., Unsupervised extraction of video highlights via robust recurrent auto-encoders, ICCV, 2015.
- Chakraborty, Shayok, Omesh Tickoo, and Ravi Iyer, Adaptive keyframe selection for video summarization, WACV, 2015.
- Viguier, Raphael, et al., Automatic video content summarization using geospatial mosaics of aerial imagery, ISM, 2015.
- Taigman, Yaniv, et al. "Deepface: Closing the gap to human-level performance in face verification." CVPR, 2014.
- Lu, Shiyang, et al., A bag-of-importance model with locality-constrained coding based feature learning for video summarization, IEEE Transactions on Multimedia, 2014.
- Tavassolipour, Mostafa, Mahmood Karimian, and Shohreh Kasaei, Event detection and summarization in soccer videos using bayesian network and copula, IEEE Transactions on Circuits and Systems for Video Technology, 2014.
- Zhao, Bin, and Eric P. Xing, Quasi real-time summarization for consumer videos, CVPR, 2014.
- Gong, Boqing, et al., Diverse sequential subset selection for supervised video summarization, NIPS, 2014.
- Gygli, Michael, et al., Creating summaries from user videos, ECCV, 2014.
- Potapov, Danila, et al., Category-specific video summarization, ECCV, 2014.
- Mehmood, Irfan, Muhammad Sajjad, and Sung Wook Baik, "Video summarization based tele-endoscopy: a service to efficiently manage visual data generated during wireless capsule endoscopy procedure," ?, 2014.
- Evangelopoulos, Georgios, et al., Multimodal saliency and fusion for movie summarization based on aural, visual, and textual attention, IEEE Transactions on Multimedia, 2013.
- Ejaz, Naveed, Irfan Mehmood, and Sung Wook Baik, "Efficient visual attention based framework for extracting key frames from videos," Signal Processing: Image Communication 28.1 (2013): 34-44.
- Khosla, Aditya, et al., Large-scale video summarization using web-image priors, CVPR, 2013.
- Lu, Zheng, and Kristen Grauman, Story-driven summarization for egocentric video, CVPR, 2013.
- Ejaz, Naveed, Tayyab Bin Tariq, and Sung Wook Baik, "Adaptive key frame extraction for video summarization using an aggregation mechanism," Journal of Visual Communication and Image Representation 23.7 (2012): 1031-1040.
- Almeida, Jurandy, Neucimar J. Leite, and Ricardo da S. Torres, "Vison: Video summarization for online applications," Pattern Recognition Letters 33.4 (2012): 397-409.
- Wang, Meng, et al., Event driven web video summarization by tag localization and key-shot identification, IEEE Transactions on Multimedia, 2012.
- Lee, Yong Jae, Joydeep Ghosh, and Kristen Grauman, Discovering important people and objects for egocentric video summarization, CVPR, 2012.
- Fu, Yanwei, et al., Multi-view video summarization. IEEE Transactions on Multimedia, 2010.
- Sang, Jitao, and Changsheng Xu., Character-based movie summarization, MM, 2010.
- Sivic, Josef, Mark Everingham, and Andrew Zisserman. "“Who are you?”-Learning person specific classifiers from video," CVPR, 2009.
- Chen, Bo-Wei, Jia-Ching Wang, and Jhing-Fa Wang, A novel video summarization based on mining the story-structure and semantic relations among concept entities, IEEE Transactions on Multimedia, 2009.
- Maaten, Laurens van der, and Geoffrey Hinton, "Visualizing data using t-SNE," Journal of machine learning research 9.Nov (2008): 2579-2605.
- You, Junyong, et al., A multiple visual models based perceptive analysis framework for multilevel video summarization, IEEE Transactions on Circuits and Systems for Video Technology, 2007
- Mundur, Padmavathi, Yong Rao, and Yelena Yesha, "Keyframe-based video summarization using Delaunay clustering," International Journal on Digital Libraries 6.2 (2006): 219-232.
- Gianluigi, Ciocca, and Schettini Raimondo, "An innovative algorithm for key frame extraction in video summarization," Journal of Real-Time Image Processing 1.1 (2006): 69-88.
- Cernekova, Zuzana, Ioannis Pitas, and Christophoros Nikou, Information theory-based shot cut/fade detection and video summarization, IEEE Transactions on Circuits and Systems for Video Technology, 2006.
- Chopra, Sumit, Raia Hadsell, and Yann LeCun, "Learning a similarity metric discriminatively, with application to face verification,"
Computer Vision and Pattern Recognition, CVPR 2005.
- Ngo, Chong-Wah, Yu-Fei Ma, and Hong-Jiang Zhang, Video summarization and scene detection by graph modeling, IEEE Transactions on Circuits and Systems for Video Technology, 2005.
- Li, Zhu, Guido M. Schuster, and Aggelos K. Katsaggelos, MINMAX optimal video summarization, IEEE Transactions on Circuits and Systems for Video Technology, 2005.
- Ma, Yu-Fei, et al., A generic framework of user attention model and its application in video summarization, IEEE Transactions on Multimedia, 2005.
- Xu, Changsheng, et al., Automatic music video summarization based on audio-visual-text analysis and alignment, SIGIR, 2005.
- Fonseca, Pedro Miguel, and Fernando Pereira,  "Automatic video summarization based on MPEG-7 descriptions," Signal Processing: Image Communication 19.8 (2004): 685-699.
- Babaguchi, Noboru, et al., Personalized abstraction of broadcasted American football video by highlight selection, IEEE Transactions on Multimedia, 2004.
- Tjondronegoro, Dian, Yi-Ping Phoebe Chen, and Binh Pham, Highlights for more complete sports video summarization, IEEE Multimedia, 2004.
- Ekin, Ahmet, A. Murat Tekalp, and Rajiv Mehrotra, Automatic soccer video analysis and summarization, IEEE Transactions on Image processing, 2003.
- Ngo, Chong-Wah, Yu-Fei Ma, and Hong-Jiang Zhang, Automatic video summarization by graph modeling, ICCV, 2003.
- Yu, Bin, et al., Video summarization based on user log enhanced link analysis, MM, 2003.
- Ma, Yu-Fei, et al., A user attention model for video summarization, MM, 2002.
- Gong, Yihong, and Xin Liu, Video summarization with minimal visual content redundancies, ICIP, 2001.
- Doulamis, Anastasios D., Nikolaos D. Doulamis, and Stefanos D. Kollias, "A fuzzy video content representation for video summarization and content-based retrieval," Signal Processing 80.6 (2000): 1049-1067.
- Gong, Yihong, and Xin Liu, Video summarization using singular value decomposition, CVPR, 2000.
- Nam, Jeho, and Ahmed H. Tewfik, Dynamic video summarization and visualization, MM, 1999.
- DeMenthon, Daniel, Vikrant Kobla, and David Doermann, Video summarization by curve simplification, MM, 1998.
- Vasconcelos, Nuno, and Andrew Lippman, Bayesian modeling of video editing and structure: Semantic features for video summarization and browsing, ICIP, 1998.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Chanran Kim has waived all copyright and
related or neighboring rights to this work.
