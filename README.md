# Neural-Style-Transfer-pytorch

Pytorch implementation of [Image Style Transfer Using Convolutional Neural Networks](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf). It is my first paper implementation so it would be quite awkward. I recommend you use it only for the reference. The [Tutorial Code](https://pytorch.org/tutorials/advanced/neural_style_tutorial.html) was very helpful for me to complete my code.


## Architecture
(Figure 2.) Style transfer algorithm.
![Neural-Style-Transfer](https://github.com/symoon94/Neural-Style-Transfer-pytorch/blob/master/assets/nst_model.png)


## Usage
To train a model with images you want to merge:

    $ python train.py --c_weight=1 --s_weight=100000 --content_img='images/dancing.jpg' --style_img='images/picasso.jpg' --size=128 --steps=300


## Result
![Result1](https://github.com/symoon94/Neural-Style-Transfer-pytorch/blob/master/assets/result1.png)
![Result2](https://github.com/symoon94/Neural-Style-Transfer-pytorch/blob/master/assets/result2.png)
![Result3](https://github.com/symoon94/Neural-Style-Transfer-pytorch/blob/master/assets/result3.png)


## Author
Sooyoung Moon / [@symoon94](https://twitter.com/?lang=ko)
