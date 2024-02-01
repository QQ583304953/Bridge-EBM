An attempt to generate new bridge types from latent space of energy-based model

Hongjun Zhang

Wanshi Antecedence Digital Intelligence Traffic Technology Co., Ltd, Nanjing, 210016, China

Abstract：Use energy-based model for bridge-type innovation. The loss function is explained by the game theory, the logic is clear and the formula is simple and clear. Thus avoid the use of maximum likelihood estimation to explain the loss function and eliminate the need for Monte Carlo methods to solve the normalized denominator. Assuming that the bridge-type population follows a Boltzmann distribution, a neural network is constructed to represent the energy function. Use Langevin dynamics technology to generate a new sample with low energy value, thus a generative model of bridge-type based on energy is established. Train energy function on symmetric structured image dataset of three span beam bridge, arch bridge, cable-stayed bridge, and suspension bridge to accurately calculate the energy values of real and fake samples. Sampling from latent space, using gradient descent algorithm, the energy function transforms the sampling points into low energy score samples, thereby generating new bridge types different from the dataset. Due to unstable and slow training in this attempt, the possibility of generating new bridge types is rare and the image definition of generated images is low.
Keywords: generative artificial intelligence; bridge-type innovation; energy-based model; latent space; deep learning

http://arxiv.org/abs/2401.17657

Based on the Python3.10, TensorFlow2.10, and Keras2.10

从基于能量的模型隐空间中生成新桥型的尝试

张洪俊

（万世先行数智交通科技有限公司，南京210016）

摘要：使用基于能量的模型进行桥型创新。采用博弈的思想阐述损失函数，逻辑清晰，公式简洁明了,从而避免采用最大似然估计法解释损失函数，也不需要蒙特卡洛方法求解归一化分母。假设桥型总体服从玻尔兹曼分布，构建神经网络来表示能量函数。使用Langevin dynamics 技术生成一个低能量分的新样本，从而建立基于能量的桥型生成式模型。采用对称结构的三跨梁式桥、拱式桥、斜拉桥、悬索桥图像数据集，训练能量函数，使其能够正确地计算出真实样本、虚假样本的能量值。从隐空间中采样，运用梯度下降算法，让能量函数将采样点变换为低能量分数的样本，从而生成不同于训练数据集的新桥型。由于本次尝试存在训练不稳定、训练缓慢的问题，导致生成的新桥型可能性稀少、生成的图像清晰度偏低。

关键词：生成式人工智能；桥型创新；基于能量的模型；隐空间；深度学习


