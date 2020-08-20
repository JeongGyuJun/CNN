## [CNN(Convolutional Neural Network)](https://github.com/JeongGyuJun/CNN/blob/master/CNN.md)

##### - paper(model, attention, Image Processing etc...) review
###### 문제가 될 경우 삭제하겠습니다.

1. [Very deep convolutional networks for large-scale image recognition](https://github.com/JeongGyuJun/CNN/blob/master/VGG16.md)

=> 대량의 이미지 분류에 대한 깊은 신경망의 표현하는 깊이가 분류 정확도에 이롭다는 것을 입증함.

2. [Deep Residual Learning for Image Recognition](https://github.com/JeongGyuJun/CNN/blob/master/ResNet.md)

=> 네트워크가 깊어질수록 problem of vanishing/exploding gradients)가 발생하는 문제점을 해결하고자 Residual 네트워크을 이용함.

3. [Densely connected convolutional networks](https://github.com/JeongGyuJun/CNN/blob/master/DenseNet.md)

=> ResNet의 skip connection과 다른 Dense connectivity라고 불리는 입력값을 계속해서 출력값의 채널 방향으로 합쳐주는 방법으로 특징 보존, gradient vanishing 문제 해결, 비용 절감의 장점을 가짐. 

4. [Efficientnet: Rethinking model scaling for convolutional neural networks](https://github.com/JeongGyuJun/CNN/blob/master/EfficientNet.md)

=> scale-up(depth, channel width, resolution) 세 가지 요소에 대한 compound scaling을 적절하게 구성함으로써 컨볼루션 네트워크의 성능을 높이고자 함.

5. [Mobilenets: Efficient convolutional neural networks for mobile vision applications](https://github.com/JeongGyuJun/CNN/blob/master/MobileNet.md)

=> 모델의 크기 및 시간을 절감하기 위해 약간의 정확도를 상쇄함으로써 width, resolution multiplier을 조작하여 작고 빠른 MobileNet을 구성함.

6. [Squeeze-and-Excitation Networks](https://github.com/JeongGyuJun/CNN/blob/master/Squeeze-and-Excitation_Net.md)

=> Squeeze&Excitation이라는 연산 작업으로 정보의 압축 & 재조정을 효율적으로 실시하여 네트워크의 표현력을 향상시키기 위해 설계함.

7. [CBAM: Convolutional block attention module](https://github.com/JeongGyuJun/CNN/blob/master/Convolution_block_attention_module.md)

=> Channel & Spatial 두 가지 모듈로 Attention 기반 기능 개선을 적용하고 오버헤드를 작게 유지하면서 성능 향상을 가져옴.

8. [A Comprehensive Overhaul of Feature Distillation](https://github.com/JeongGyuJun/CNN/blob/master/A_Comprehensive_Overhaul%20of_Feature_Distillation.md)

=>  Knowledge Distillation 분야의 연구로 teacher 네트워크의 knowledge를 student 네트워크로 옮겨서 차이를 줄이는 방법으로 모델 사이즈가 작고 비용 면에서 효율적으로 구성하여 가벼운 기기에서 딥러닝 모델이 돌아갈 수 있도록 함.

9. [Assemble_CNN](https://github.com/JeongGyuJun/CNN/blob/master/Assembled_CNN.md)

10. [Learning in the Frequency Domain](https://github.com/JeongGyuJun/CNN/blob/master/Learning%20in%20the%20Frequency%20Domain.md)

=> Digital Signal Processing의 영감을 받아 주파수 영역에서의 학습 방법을 제안함으로써 영상 정보의 보존성과 향상된 정확도를 달성하는 것을 보여줌.

11. [U-net: Convolutional networks for biomedical image segmentation](https://github.com/JeongGyuJun/CNN/blob/master/U_Net.md)

=> 일반적으로 Image Segmentation 작업으로 Contracting, Expanding path 구조를 사용하여 Data Augmentation을 활용함으로써 Biomedical Segmentation Application에서 좋은 성능을 보임. 

12. [Fully Convolutional Networks for Semantic Segmentation](https://github.com/JeongGyuJun/CNN/blob/master/FCN.md)

=> 기존 Image Classification에서 우수한 성능을 보인 Convolutional Neural Network 기반 모델의 fully connected layer를 1 x 1 convolution 변경하여 공간 정보의 위치를 유지할 수 있게 되어 장면 이해 성능을 높임으로써 로봇 비전, 자율 주행의 영상 부분에 적용 가능 할 수 있게함.

13. [Feature Pyramid Networks for Object Detection]()

=> 

14. [You only look once: Unified, real-time object detection](https://github.com/JeongGyuJun/CNN/blob/master/FPN.md)

=> Bottom-up, Top-down pathway, lateral connection 단계를 거쳐서 다양한 스케일의 객체를 찾기 위한 방법으로 비용과 속도 그리고 정확도의 향상을 가져올 수 있었음. 

15. [YOLO(You Only Look Once)](https://github.com/JeongGyuJun/CNN/blob/master/YOLO.md)

=> 현재의 detection system은 분류기에 detection 역할을 하도록 재설정하는 방식으로 object detection을 위해서, 시스템은 객체를 분류기가 받아 테스트 이미지 내에서 다양한 위치와 크기를 표현함.

16. [Grad-CAM:
Visual Explanations from Deep Networks via Gradient-based Localization](https://github.com/JeongGyuJun/Convolution_Neural_Network_Papers/blob/master/Grad_CAM.md)

=> Grad-CAM이깊은 신경망에서의 예측이 적절한 신뢰를 구성할 수 있도록 사용자를 돕거나, 훈련되지 않은 사용자가 동일한 예측을 할 때 강한 깊은 신경망의 기능을 약한 깊은 신겨망에서 성공적으로 식별할 수 있도록 도와주며 '모델이 문제를 얼마나 잘 해결하고 있는가'를 확인하는 지표로서 동작함.
