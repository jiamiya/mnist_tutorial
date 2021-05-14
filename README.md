# accuracy list

question|training accuracy | testing accuracy
---- | ----- | ------  
Q1|97.52 |88.20
Q2|81.75 |81.70
Q3|98.02 |86.10
Q4|90.77 |89.00
Q5|99.68 |99.19

# 网络架构
使用LeNet网络架构 (reference：https://github.com/zergtant/pytorch-handbook/blob/master/chapter3/3.2-mnist.ipynb）
（28，28） (convolution)->  (6, 24 , 24) (maxpooling) ->(6, 12, 12) (convolution) ->(16, 8, 8) (maxpooling) ->(16, 4, 4) (reshape) ->(256) (fuly connect) ->(120) (fuly connect) ->(84) (fuly connect) ->(10) (fuly connect)
