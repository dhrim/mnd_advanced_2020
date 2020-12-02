
# 교육 목표

딥러닝을 이해하고 실제 문제에 적용하여 해결할 수 있다.


<br>

# 교육 상세 목표

- 딥러닝을 이해한다.
- 딥러닝을 적용할 수 있는 문제를 이해한다.
- 딥러닝을 실 문제에 적용하는 방법을 이해한다.
- 딥러닝에 적용하기 위한 데이터 처리방법을 이해한다.
- 데이터 처리방법을 파악하고 구현할 수 있다.
- 딥러닝을 적용하여 실제 문제를 해결한다.


<br>

# 일자별 계획

## 1일차

- 인공지능 개념 및 동작 원리의 이해 : [deep_learning_intro.pptx](material/deep_learning/deep_learning_intro.pptx)
    - Perceptron, MLP, DNN 소개
    - DNN의 학습 이해
    - AI, 머신러닝, 딥러닝의 이해
    - 딥러닝 상세 기술 이해

- 딥러닝 개발 환경
- 기본 linux 명령의 이해와 실습 : [linux.md](material/linux.md)

<br>


## 2일차

- Keras 파악, 딥러닝 코드 파악 실습 : : [dnn_in_keras.ipynb](material/deep_learning/dnn_in_keras.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/dnn_in_keras.ipynb)
    - 표준 Keras 딥러닝 코드
    - 로스 보기
    - 은닉층과 노드 수
    - trian, test 데이터 분리
    - batch size와 학습
    - 데이터 수와 학습
    - normalization
    - 모델 저장과 로딩
    - 웨이트 초기값
    - 노이즈 내구성
    - GPU 설정
    - 데이터 수와 overfitting
    - overfitting 처리하기
    - callback
    - 다양한 입출력

<br>


## 3일차

- 분류기로서의 DNN
    - 속성 데이터 IRIS 분류 실습 : [dnn_iris_classification.ipynb](material/deep_learning/dnn_iris_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/dnn_iris_classification.ipynb)
- 영상 분류기로서의 DNN
    - 흑백 영상 데이터 MNIST 분류 실습 : [dnn_mnist.ipynb](material/deep_learning/dnn_mnist.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/dnn_mnist.ipynb)
    - 흑백 영상 fashion MNIST 분류 : [dnn_fashion_mnist.ipynb](material/deep_learning/dnn_fashion_mnist.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/dnn_fashion_mnist.ipynb)
- 영상 분류기로서의 CNN
    - 흑백 영상 데이터 MNIST 영상분류 : [cnn_mnist.ipynb](material/deep_learning/cnn_mnist.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/cnn_mnist.ipynb)
    - CIFAR10 컬러영상분류 : [cnn_cifar10.ipynb](material/deep_learning/cnn_cifar10.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/cnn_cifar10.ipynb)
- 분류기로서의 CNN
    - IRIS 분류 : [iris_cnn.ipynb](material/deep_learning/iris_cnn.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/iris_cnn.ipynb)

<br>


## 4일차

- Data Augmentation : [data_augmentation.ipynb](material/deep_learning/data_augmentation.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/data_augmentation.ipynb)
- VGG로 영상 분류, 전이학습 : [VGG16_classification_and_cumtom_data_training.ipynb](material/deep_learning/VGG16_classification_and_cumtom_data_training.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/VGG16_classification_and_cumtom_data_training.ipynb)
- 커스텀 데이터 VGG 데이터 분류 실습 : [real_practice_glaucoma_classification.ipynb](material/deep_learning/real_practice_glaucoma_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/real_practice_glaucoma_classification.ipynb)

<br>


## 5일차

- text 데이터의 이해
    - word embedding의 이해
    - word2vec 실습
- RNN
    - RNN의 이해 : [deep_learning_intro.pptx](material/deep_learning//deep_learning_intro.pptx)
    - CNN, RNN을 사용한 영화 평가 데이터 IMDB 분류 실습 :  : [rnn_text_classification.ipynb](material/deep_learning/rnn_text_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/rnn_text_classification.ipynb)
    - RNN을 사용한 흑백 영상 데이터 MNIST 분류 : [mnist_rnn.ipynb](material/deep_learning/mnist_rnn.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/mnist_rnn.ipynb)
- IMDB 사례를 통한 오버피팅 처리하기 : [treating_overfitting_with_imdb.ipynb](material/deep_learning/treating_overfitting_with_imdb.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/treating_overfitting_with_imdb.ipynb)
- 강화학습 이해하기 : [deep_learning_intro.pptx](material/deep_learning//deep_learning_intro.pptx)
- 알파고 이해하기 : [understanding_ahphago.pptx](material/deep_learning/understanding_ahphago.pptx)

<br>


## 6일차

- Keras Function API  : [functional_api.ipynb](material/deep_learning/functional_api.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/functional_api.ipynb)

- 영상 분할(Segementation)
    - U-Net을 사용한 영상 분할 실습 : [unet_segementation.ipynb](material/deep_learning/unet_segementation.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/unet_segementation.ipynb)
    - M-Net을 사용한 영상 분할 실습 : [mnet_segementation.ipynb](material/deep_learning/mnet_segementation.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/mnet_segementation.ipynb)
    - U-Net을 사용한 컬러 영상 분할 실습 : [unet_segementation_color_image.ipynb](material/deep_learning/unet_segementation_color_image.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/unet_segementation_color_image.ipynb)


- AutoEncoder
    - AutoEncoder 실습 : [autoencoder.ipynb](material/deep_learning/autoencoder.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/autoencoder.ipynb)
    - 디노이징 AutoEncoder : [denoising_autoencoder.ipynb](material/deep_learning/denoising_autoencoder.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/denoising_autoencoder.ipynb)
    - Super Resolution : [mnist_super_resolution.ipynb](material/deep_learning/mnist_super_resolution.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/mnist_super_resolution.ipynb)
    - 이상 탐지 : [anomaly_detection_using_autoencoder.ipynb](material/deep_learning/anomaly_detection_using_autoencoder.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/anomaly_detection_using_autoencoder.ipynb)

<br>


## 7일차

- 물체 탐지
   - 물체 탐지의 이해
   - YOLO의 이해
   - YOLO 적용 방법 실습 : [object_detection.md](material/deep_learning/object_detection.md)

<br>


## 8일차


- GAN
    - GAN의 이해 : [deep_learning_intro.pptx](material/deep_learning//deep_learning_intro.pptx), 
    - GAN을 사용한 MNIST 학습 실습 : [wgan_gp_mnist.ipynb](material/deep_learning/wgan_gp_mnist.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/wgan_gp_mnist.ipynb)
    - Conditional GAN의 이해 : 
    - Cycle GAN의 이해 : [cycle_gan.pdf](material/deep_learning/cycle_gan.pdf)


- 다양한 적용
    - 얼굴 탐지 실습 : [Face_Recognition.ipynb](material/deep_learning/Face_Recognition.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/Face_Recognition.ipynb)
    - 얼굴 감정 분류 실습 : [face_emotion_classification.ipynb](material/deep_learning/face_emotion_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/face_emotion_classification.ipynb)
    - 얼굴 탐지 실습 : [track_faces_on_video_realtime.ipynb](material/deep_learning/track_faces_on_video_realtime.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/track_faces_on_video_realtime.ipynb)
    - 화재 영상 분류 실습 : [Fire.tar.gz](material/deep_learning/Fire.tar.gz), [spatial_envelope_static_8outdoorcategories.tar.gz](material/deep_learning/spatial_envelope_static_8outdoorcategories.tar.gz)

<br>


## 9일차

- 실데이터 실습 #1
    - wafer map 영상 분류 : [real_practice_classify_semiconductor_wafermap.ipynb](material/deep_learning/real_practice_classify_semiconductor_wafermap.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/semiconductor_ai_2020/blob/main/material/deep_learning/real_practice_classify_semiconductor_wafermap.ipynb)
    - 속성 데이터 예측 : [real_practice_predict_semiconductor_attribute.ipynb](material/deep_learning/real_practice_predict_semiconductor_attribute.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/semiconductor_ai_2020/blob/main/material/deep_learning/real_practice_predict_semiconductor_attribute.ipynb)
    - 속성 데이터 분류 : [real_practice_classify_semiconductor_attribute.ipynb](material/deep_learning/real_practice_classify_semiconductor_attribute.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/semiconductor_ai_2020/blob/main/material/deep_learning/real_practice_classify_semiconductor_attribute.ipynb)
    - 시계열 데이터 예측 : [real_practice_timeseries_weathrer_forecaseting.ipynb](material/deep_learning/real_practice_timeseries_weathrer_forecaseting.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/semiconductor_ai_2020/blob/main/material/deep_learning/real_practice_timeseries_weathrer_forecaseting.ipynb)
    - 시계열 데이터 분류 : [real_practice_classify_semiconductor_time_series_data.ipynb](material/deep_learning/real_practice_classify_semiconductor_time_series_data.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/semiconductor_ai_2020/blob/main/material/deep_learning/real_practice_classify_semiconductor_time_series_data.ipynb)

<br>


## 10일차


- 포즈 추출 실습 : [pose_extraction_using_open_pose.ipynb](material/deep_learning/pose_extraction_using_open_pose.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/pose_extraction_using_open_pose.ipynb)
    - 사용 템플릿 : [open_pose_using_template.ipynb](material/deep_learning/open_pose_using_template.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/open_pose_using_template.ipynb)

- ...

<br>


# 기타

교육환경, numpy, pandas, matplot
- 교육 환경 : [env.md](material/env.md)
- numpy : 데이터 로딩, 보기, 데이터 변환, 형태 변경 : [library.md](material/library.md)
- pandas, matplot : [ibrary.md](material/library.md)

기타 자료
- [의학논문 리뷰](https://docs.google.com/presentation/d/1SZ-m4XVepS94jzXDL8VFMN2dh9s6jaN5fVsNhQ1qwEU/edit)
- GCP에 VM 생성하고 Colab 연결하기 : [create_GCP_VM.pdf](material/deep_learning/create_GCP_VM.pdf)
- 흥미로운 딥러닝 결과 : [some_interesting_deep_learning.pptx](material/deep_learning/some_interesting_deep_learning.pptx)
- yolo를 사용한 실시간 불량품 탐지 : https://drive.google.com/file/d/194UpsjG7MyEvWlmJeqfcocD-h-zy_4mR/view?usp=sharing
- YOLO를 사용한 자동차 번호판 탐지 : https://drive.google.com/file/d/1jlKzCaKj5rGRXIhwMXtYtVnx_XLauFiL/view?usp=sharing
- GAN을 사용한 생산설비 이상 탐지 : [anomaly_detection_using_gan.pptx](material/deep_learning/anomaly_detection_using_gan.pptx)
- 이상탐지 동영상 : [drillai_anomaly_detect.mp4](material/deep_learning/drillai_anomaly_detect.mp4)
- 훌륭한 논문 리스트 : https://github.com/floodsung/Deep-Learning-Papers-Reading-Roadmap
- online CNN 시각화 자료 : https://poloclub.github.io/cnn-explainer/
- GradCAM : [grad_cam.ipynb](material/deep_learning/grad_cam.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/grad_cam.ipynb)
- AUC 그리기 :  [draw_auc_with_mnist_cnn.ipynb](material/deep_learning/draw_auc_with_mnist_cnn.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/mnd_advanced_2020/blob/master/material/deep_learning/draw_auc_with_mnist_cnn.ipynb)
- 서버 설치 기록 : [2019-10-17_setup_server.pdf](material/env/2019-10-17_setup_server.pdf)
- GCP에 VM 생성하고 Colab 연결 : [GCP_VM_and_Colab.pdf](material/env/GCP_VM_and_Colab.pdf)
- TensorFlow 홈 tutorial에서 스타일 변환 : https://www.tensorflow.org/tutorials/generative/style_transfer?hl=ko


<br>

# 교육에 사용된 외부 자료
- bynamic robotics 1 : https://www.youtube.com/watch?v=_sBBaNYex3E
- bynamic robotics 2 : https://www.youtube.com/watch?v=94nnAOZRg8k
- cart pole : https://www.youtube.com/watch?v=XiigTGKZfks
- bidirectional RNN : https://towardsdatascience.com/understanding-bidirectional-rnn-in-pytorch-5bd25a5dd66
- alphago architecture : https://medium.com/applied-data-science/alphago-zero-explained-in-one-diagram-365f5abf67e0
- u-net architecture : https://machinelearningmastery.com/how-to-implement-pix2pix-gan-models-from-scratch-with-keras/
- upsampling : https://kharshit.github.io/blog/2019/02/15/autoencoder-downsampling-and-upsampling
- Denseness architecture : https://hoya012.github.io/blog/DenseNet-Tutorial-1/
- K-fold cross validation : https://m.blog.naver.com/PostView.nhn?blogId=dnjswns2280&logNo=221532535858&proxyReferer=https:%2F%2Fwww.google.com%2F
- M-net architecture : https://hzfu.github.io/proj_glaucoma_fundus.html  
- yolo 적용 예 블로그 : https://nero.devstory.co.kr/post/pj-too-real-03/
- GAN 위조 지폐 : http://mrkim.cloudy.so/board_KBEq62/175378
- GAN paper : https://arxiv.org/pdf/1406.2661.pdf
- Gan paper count : https://blog.naver.com/PostView.nhn?blogId=laonple&logNo=221201915691
- Conditional gan face generation example. https://github.com/Guim3/IcGAN
- Pinpointing example : https://www.geeks3d.com/20180425/nvidia-deep-learning-based-image-inpainting-demo-is-impressive/ 
- 동영상 스타일 변환 : https://www.youtube.com/watch?v=Khuj4ASldmU
- 얼굴 감정 인식 예 : http://www.astronomer.rocks/news/articleView.html?idxno=86084
- Papers with code : https://paperswithcode.com/
  

<br>


# 딥러닝 활용을 위한 지식 구조

```
Environment
    jupyter
	colab
	usage
		!, %, run
    GCP virtual machine
linux
	ENV
	command
		cd, pwd, ls
		mkdir, rm, cp
		head, more, tail, cat
	util
		apt
		git, wget
		grep, wc, tree
		tar, unrar, unzip
	gpu
		nvidia-smi

python
	env
		python
			interactive
			execute file
		pip
	syntax
        variable
        data
            tuple
            list
            dict
            set
        loop
        if
        comprehensive list
        function
        class
	module
		import

libray
    numpy
        load
        op
        shape
        slicing
        reshape
        axis + sum, mean
    pandas
        load
        view
        to numpy
    matplot
        draw line graph
        scatter
        show image

Deep Learning
    DNN
        concept
            layer, node, weight, bias, activation
            cost function
            GD, BP
        data
            x, y
            train, validate, test
            shuffle
        learning curve : accuracy, loss
        tunning
            overfitting, underfitting
            regularization, dropout, batch normalization
            data augmentation
        Transfer Learning
    type
        supervised
        unsupervised
        reinforcement
    model
        CNN
            varnilla, VGG16
        RNN
        GAN
    task
        Classification
        Object Detection
        Generation
	Segmentation
	Pose Extraction
	Noise Removing
	Super Resolution
	Question answering
	Auto Captioning
        target : text/image

TensorFlow/Keras
    basic frame
        data preparing
            x, y
            train, valid, test
            normalization
            ImageDataGenerator
        fit
        evaluate
        predict
    model
        activation function
        initializer
    tuning
        learning rate
        regularier
        dropout
        batch normalization
    save/load
    compile
        optimizer
        loss
        metric
```

 
