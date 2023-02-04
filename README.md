# Efficient Deep Learning-based Sentence Boundary Detection in Legal Text
 [[paper]](https://aclanthology.org/2022.nllp-1.18/) [[dataset]](https://github.com/jsavelka/sbd_adjudicatory_dec)
 <br> <br>
 *This repo is is the official Implementation of "Efficient Deep Learning-based Sentence Boundary Detection in Legal Text" which was presented at EMNLP2022.* </br></br>
 The code for each model can be found in [NeuralNetworks](https://github.com/NLLP-ML/SBD/tree/main/NeuralNetworks) folder.
# Benchmark

<img src="https://user-images.githubusercontent.com/57902078/216748530-4c7a4e29-50f7-4fba-839c-d0dad1aa7b24.png "  width="800" height="500" />
<img src="https://user-images.githubusercontent.com/57902078/216748615-178b505b-e5c1-496d-8b11-bd4ec530b60e.png "  width="850" height="500" />

<p float="left">
<img src="https://user-images.githubusercontent.com/57902078/216748722-f6e22545-fba4-4b71-8312-7c241e30c17d.png"  width="550" height="450" />
<img src="https://user-images.githubusercontent.com/57902078/216748570-1bb3575b-7f7f-4ed8-9c81-c75d155f1895.png "  width="430" height="450" />
</p>

# Citation

```
@inproceedings{sheik-etal-2022-efficient,
    title = "Efficient Deep Learning-based Sentence Boundary Detection in Legal Text",
    author = "Sheik, Reshma  and
      T, Gokul  and
      Nirmala, S",
    booktitle = "Proceedings of the Natural Legal Language Processing Workshop 2022",
    month = dec,
    year = "2022",
    address = "Abu Dhabi, United Arab Emirates (Hybrid)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.nllp-1.18",
    pages = "208--217",
    abstract = "A key component of the Natural Language Processing (NLP) pipeline is Sentence Boundary Detection (SBD). Erroneous SBD could affect other processing steps and reduce performance. A few criteria based on punctuation and capitalization are necessary to identify sentence borders in well-defined corpora. However, due to several grammatical ambiguities, the complex structure of legal data poses difficulties for SBD. In this paper, we have trained a neural network framework for identifying the end of the sentence in legal text. We used several state-of-the-art deep learning models, analyzed their performance, and identified that Convolutional Neural Network(CNN) outperformed other deep learning frameworks. We compared the results with rule-based, statistical, and transformer-based frameworks. The best neural network model outscored the popular rule-based framework with an improvement of 8{{\%} in the F1 score. Although domain-specific statistical models have slightly improved performance, the trained CNN is 80 times faster in run-time and doesn{'}t require much feature engineering. Furthermore, after extensive pretraining, the transformer models fall short in overall performance compared to the best deep learning model.",
}

```
