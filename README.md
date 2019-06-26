# Association learning
This is research of testing association learning in animals behavior using CNNs on self created dataset with 4 classes (pizza, hotdog, burger, pasta)).
Idea of research is to check ability of cnn to learn associations from images. We've trained model to classify pizza/pasta as class 1 and burger/hotdog as class 2. At the same time we've trained model to define pizza and burger as classes 3 and 4. The goal is to check after learning, will the model define pasta and hotdog as classes 3 and 4 respectively or not?
Results showed that at validation dataset, model pasta and hotdog classifies correctly(3 and 4) 77% cases. 

Dataset consists of 2000 images (500 per each class). Model - pretrained ResNet18
