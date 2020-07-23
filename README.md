# Neural-Image-Captioning-for-Visually-Impaired

1. Even though state-of-the-art models that describe the contents of an image have been proposed, very few of them have been applied for use, in end-to-end solutions for aiding the visually impaired. 

2. A visually impaired person can take pictures of his surroundings, which can be used to generate captions. When these are converted to audio they get a better sense of their surroundings. 

3. In this project, we use a Deep Recurrent Architecture, which uses CNN to extract image features and an LSTM which generates a caption from these feature vectors. The model is trained to maximize the likelihood of the target description given the training image. We obtain a BLEU Score of 38.1 (higher is better) on Flickr8k dataset, generating highly descriptive captions that can potentially improve the lives of visually impaired people.

### References:

[1] O. Vinyals, A. Toshev, S. Bengio, and D. Erhan. Show and tell: A neural image caption generator. arXiv preprint arXiv:1411.4555, 2014.

[2] Andrej Karpathy, Li Fei-Fei. 2015. Deep visual-semantic alignments for generating image descriptions. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 3128–3137.A.

[3] Kelvin Xu, Jimmy Ba, Ryan Kiros, Kyunghyun Cho, Aaron C. Courville, Ruslan Salakhutdinov, Richard S. Zemel, and Yoshua Bengio. 2015. Show, Attend and Tell: Neural Image Caption Generation with Visual Attention. arXiv preprint arXiv:1502.03044, 2015.
