This is a repository for final project on Skolkovo Machine Learning course.

Here we provided some examples of neural style transfer task using pretrained on ImageNet VGG-19 net.

Also we provided multiple style transfer - a problem, where we transfer style from two input style pictures to content with some weights.

Examples of results of model:

![image](https://user-images.githubusercontent.com/80292602/112242727-7e13b500-8c5d-11eb-8a86-b1f7233be5f5.png)

![image](https://user-images.githubusercontent.com/80292602/112243189-35103080-8c5e-11eb-8e86-37968f944af2.png)

![image](https://user-images.githubusercontent.com/80292602/112243214-3fcac580-8c5e-11eb-960a-137363c713e8.png)

![image](https://user-images.githubusercontent.com/80292602/112243225-45c0a680-8c5e-11eb-8a69-57be38fcf162.png)

The main contributions of this project:
1.Collected datasets of content images and style reference images.
2.Implemented Gram matrix and applied it to Multi-transfer style
3.Implemented loss function from paper for preserving content of one image and get a good approximation of the styles of both style images
4.Implemented another style and content loss functions and considered obtained results.
5.Considered some GANs alghorithms.
6.Reproduced the experiment with a smaller neural network for the purpose of operating in a limited resources mode.
