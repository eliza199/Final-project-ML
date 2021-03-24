This is a repository for final project on Skolkovo Machine Learning course.

Here we provided some examples of neural style transfer task using pretrained on ImageNet VGG-19 net.

Also we provided multiple style transfer - a problem, where we transfer style from two input style pictures to content with some weights.

Examples of results of model:

![image](https://user-images.githubusercontent.com/80292602/112242727-7e13b500-8c5d-11eb-8a86-b1f7233be5f5.png)

![image](https://user-images.githubusercontent.com/80292602/112242842-a13e6480-8c5d-11eb-8727-8713b265c667.png)

The main contributions of this report are as follows:
\begin{itemize}
\item Collected datasets of content images and style reference images.
\item Implemented Gram matrix and applied it to Multi-transfer style
\item Implemented loss function from paper for preserving content of one image and get a good approximation of the styles of both style images
\item Implemented another style and content loss functions and considered obtained results.
\item Considered some GANs alghorithms.
\item Reproduced the experiment with a smaller neural network for the purpose of operating in a limited resources mode.
\end{itemize}
