# Few-shot learning
#### Why focus on few-shot learning? 
>The connection between few-shot learning, knowledge transfer between different modalities and online learning are key aspects of future ML research. Imagine reinforcement learners designed as a single machine learning system that can solve thousands or millions of tasks, and _can draw from the experience in solving these tasks to learn to automatically solve_ **new tasks**. 

The following project follows the methods of [ProtoTypical Networks](https://arxiv.org/pdf/1703.05175.pdf) (Snell, Swersky, Zemel) for few-shot classification on the OmniGlot dataset.

![Prototypes](https://cdn-images-1.medium.com/max/1600/0*-eiNihLUkhMd4QJg.) 
> [ProtoNets](https://arxiv.org/pdf/1703.05175.pdf) offer an intuitive solution to the few-shot problem that exonerates us from the complexity of meta-learning and other bespoke architectures 


![Gaussians](http://stanford.edu/~sfort1/gauss1.png)
> Improved classification on the Omniglot dataset by making the distance metric dependent on covariance of barycenters calculated within class. [Gaussian Prototypical Nets]() achieve state of the art performance with relative simplicity compared to [Graph Neural Nets](https://openreview.net/pdf?id=BJj6qGbRW).