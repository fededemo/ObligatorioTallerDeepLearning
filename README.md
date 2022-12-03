# ObligatorioTallerDeepLearning

El objetivo de esta tarea fue evaluar nuestros conocimientos sobre Deep Learning mediante la implementación de un research paper: [Generative Adversarial Networks (GANs)](https://arxiv.org/abs/1406.2661).

En este trabajo obligatorio presentamos todas las premisas solicitadas en los requerimientos:
- Correcta implementación de una red GAN.
- Variedad de modelos desde la red simple, pasando por la red simple con pesos iniciales hasta la implementación compleja de una red DCGAN.
- Entrenamiento y generación usando los distintos datasets planteados: MNIST, FashionMNIST y CIFAR10.

Partiendo de 3 arquitecturas base (simple, simple con pesos y DCGAN) las mismas fueron entrenadas con los datasets mencionados anteriormente logrando buenos resultados. Cabe destacar que para el caso de CIFAR10 las arquitecturas base fueron modificadas para tomar en cuenta las particularidades del data set: 3 canales RGB (*MNIST es escala de grises por lo tanto es 1 canal) y tamaño de imágen 32x32 píxeles (28x28 en el caso de los otros datasets).



