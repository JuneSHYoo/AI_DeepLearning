 
### week3
- tensor slicing
- naive method {add, product, 

### week4
#### chapter 02
- SGD -> optimizer = 'rmsprop' , 'adagrad' ,etc
- Gradient Tape method

- activation = 'relu' (보통 dense layer) , 'softmax' (보통 output layer)

- 모델링 흐름 -> 1. 데이터, 2.레이어 쌓기, 3.컴파일, 4. 핏

- Naive dense method
- Naive sequential method
- Naive batch generator

#### chapter 03
- tensor 설명, numpy와 tensor 차이 , tensor 활용 방법
- linear classifier example 
- loss 'binary crossentropy' -> two-class / 'categorical crossentropy' -> many-class / 'Mean suared error' -> regression problem 

### week5
##### chapter 04
- classifying movie review : binary clssi
- newswires : multiclas  (input one-hot encoding)
- predicting house : regression

- plot 그리는 코드

- categorical_crossentropy -> sparse_categorical_crossentropy (when labels would be casted as an int tensor)

### week6
#### chapter 05
- adding noise channel or all-zeors channels
- maniford hypothesis (lectur note p.14)

- adding Regularization
- adding dropout

### week7
##### chapter 07
- sequential model : simple stacks of layers => make and add layers at once / model.build(input shape)
- Functional API : graph-like architectures => multi input and multi output / training model by providing dict / grapjh 
- Model subclassing : 구조체 이용 => when train, training = True is important

