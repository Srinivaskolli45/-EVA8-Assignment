Step1:

Target:
My target is to get the base network with less than 10000 parameters and achieve accuracy around 99%
in 15 epochs

Result:
1. Total params: 9,956
2. Training accuracy: 99.44 %
3. Test accuracy: 99.46 %

Analysis:
1. With 8 covolutional layer and batch normalization network is showing quite stable
training and testing result
2. I have not observed any overfitting/underfitting sympton in network  nand not much devaitaion between training and testing result
3. With this the target is achieved
4. Estimated Total Size (MB): 0.47
5. Now need to think on  to reduve params and accuracy


Step2:
Target:
My target is to get the base network with ~ 9000 parameters and achieve accuracy around 99%
in 15 epochs

Result:
1. Total params: 9,026
2. Training accuracy: 99.44 %
3. Test accuracy: 99.43 %

Analysis:
1. With 7 covolutional layer, and added padding at intial stage of convolution layers and batch normalization network is showing quite stable
training and testing result
2. I have not observed any overfitting/underfitting sympton in network  and not much devaitaion between training and testing result
3. With this the target is achieved
4. Estimated Total Size (MB): 0.58  and total size is increased beacuse of padding at  intial convolution layers
5. Now need to think on  to reduve params and accuracy


Step3:
Target:
My target is to get the base network with ~ 9000 parameters and achieve accuracy around 99%
in 15 epochs

Result:
1. Total params: 9,026
2. Training accuracy: 99.45 %
3. Test accuracy: 99.46 %

Analysis:
1. With 7 covolutional layer and batch normalization network is showing quite stable
training and testing result
2.Increased the learning rate from 0.001 to 0.002 for learnining quickely
2. I have not observed any overfitting/underfitting sympton in network  and not much devaitaion between training and testing result
3. With this the target is achieved
4. Estimated Total Size (MB): 0.45
5. Now need to think on  to reduce params and accuracy

