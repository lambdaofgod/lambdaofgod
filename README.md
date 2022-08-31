# About me

- Since 2017 I work as a data scientist.
- :office: My work experience can be found in my LinkedIn profile (Jakub Bartczuk).
- :mortar_board: I studied Theoretical Mathematics (BSc.) and Data Science (MSc.) at University of Wrocław.
- I am mostly focused on deep learning, especially for NLP and Computer Vision. I enjoy problems that go beyond straightforward supervised learning.
- In the free time I like to contribute to opensource projects.
- :book: When I need to take a rest from sitting at the computer I keep up with ML news and read about mathematics, linguistics and psychology.

## Projects
* In [findkit](https://github.com/lambdaofgod/findkit) I put together wrappers making working with information retrieval with vector data easier.
* :newspaper: [NewsBERT](https://github.com/lambdaofgod/pytorch_hackathon) is a RSS feeds information retrieval app that using huggingface transformers zero-shot learning feature. 

## Neural networks for searching github repositories - MSc thesis

With over 500 starred repositories searching through them became cumbersome. I did a [small project for retrieval on starred repositories](https://github.com/lambdaofgod/examples-counterexamples/blob/master/notebooks/text_mining/Github_Starred_Repositories.ipynb) which looked promising, but it is hard to gauge how useful such solution would be in practice.

In the thesis I use PapersWithCode data for information retrieval.

PapersWithCode contains links between papers and repositories that implement them. Most repositories are tagged with at least one task like "unsupervised segmentation" or "semantic parsing".

I proposed and built a system that among other things uses zero-shot learning and features extracted with Graph Neural Networks from Python files and functions dependency (call) graph. 

## Small projects
* :mag: [search huggingface models](https://huggingface.co/spaces/lambdaofgod/huggingface_explorer)
* [symmetric deep dream](https://colab.research.google.com/github/lambdaofgod/examples-counterexamples/blob/master/deepdream_with_mirroring_and_rotation.ipynb) - I added averaging over rotations to make deep dream more symmetric

## Stackexchange
Apparently [I'm top 3% at cross-validated](https://stats.stackexchange.com/users/121270/jakub-bartczuk) (stackoverflow for ml/statistics).

* [does PCA preserve linear separability?](https://github.com/lambdaofgod/examples-counterexamples/blob/master/notebooks/Separable%20data%20PCA%20nonseparable.ipynb)
* [if your scikit-learn PCA fails you probably made this mistake](https://github.com/lambdaofgod/stackexchange/blob/master/cross%20validated/Digits%20PCA.ipynb)
* [Wasserstein GAN prerequisites](https://stats.stackexchange.com/questions/384590/prerequisites-for-wasserstein-gan-autoencoder)

## Other :eyes:
* [Demystifying UMAP](https://github.com/lambdaofgod/texfiles/blob/master/umap_advanced_data_mining/main.pdf) - presentation for Advanced Data Mining seminar at University of Wroclaw.
* [manifold learning rotation equivariance on raw pixel values](https://github.com/lambdaofgod/examples-counterexamples/blob/master/notebooks/COIL20%20Manifold%20Learning.ipynb) - it seems like Isomap and UMAP partly preserve the rotational structure (for a given image, the closest image are the closest rotated one and its 180 rotation). These algorithms are not designed to do this!
* [neural nets like it's 2010 but in modern framework... RBMs in Jax](https://github.com/lambdaofgod/examples-counterexamples/blob/master/notebooks/neural_nets/RBM_Jax.ipynb)
