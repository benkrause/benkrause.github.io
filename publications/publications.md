<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://cdn.rawgit.com/jpswalsh/academicons/master/css/academicons.min.css">
<style>
body
{
    width: 100%;
    height: 100%;
    margin: 0px;
    padding: 0px;
    overflow-x: hidden;
}
.navbar {
    overflow: hidden;
    background-color: #333;
    position: fixed; /* Set the navbar to fixed position */
    top: 10000; /* Position the navbar at the top of the page */
    width: 200%; /* Full width */
}
.navbar {
  overflow: hidden;
  background-color: #333;
  position: fixed;
  top: 0;
  width: 100%;
}

.navbar a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.navbar a:hover {
  background: #ddd;
  color: black;
}

.main {
  padding: 16px;
  margin-top: 30px;
  height: 1500px; /* Used in this example to enable scrolling */
}

p{
    margin-top: 10px;
    margin-bottom: 10px;
    margin-right: 10px;
    margin-left: 130px;
}
h3{
    margin-top: 10px;
    margin-bottom: 10px;
    margin-right: 100px;
    margin-left: 100px;
}
h2{
    margin-top: 10px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: 100px;
}
h4{
    margin-top: 10px;
    margin-bottom: 0px;
    margin-right: 10px;
    margin-left: 110px;
}
</style>

<div class="navbar">
  <a href="../">Home</a>
  <a href="../about">About</a>
  <a href="../blog">Blog</a>
  <a href="../publications">Publications</a>
  <a href="../contact">Contact</a>
  <a class="active" href="https://github.com/benkrause" style="float:right;"><i class="fa fa-github"></i></a>
  <a class="active" href="https://scholar.google.com/citations?user=ONNif60AAAAJ&hl=en&authuser=1" style="float:right; "><i class="ai ai-google-scholar-square ai-1"></i></a>  
<link rel="icon" href="https://benkrause.github.io/favicon.ico">
</div>

</head>
<p style="margin-top:200px;">

</p>

##Publications  &nbsp; <a class="active" href="https://scholar.google.com/citations?user=ONNif60AAAAJ&hl=en&authuser=1" style="float:center; "><i class="ai ai-google-scholar-square ai-1"></i></a>



####[Dynamic Evaluation](https://arxiv.org/abs/1709.07432)
Dynamic evaluation is a method for gradient based adaptation to sequence history that can exploit re-occurring sequential patterns. I explored and developed dynamic evaluation methodology to improve the state-of-the-art at several commonly benchmarked character and word-level language modeling tasks. The main paper was published at ICML 2018.

Krause, B., Kahembwe, E., Murray, I., & Renals, S. (2018). [Dynamic Evaluation of Neural Sequence Models](http://proceedings.mlr.press/v80/krause18a/krause18a.pdf). ICML 2018.

I had follow up work that showed that dynamic evaluation could give significant improvements to strong Transformer language models

Krause, B., Kahembwe, E., Murray, I., & Renals, S. (2019). [Dynamic Evaluation of Transformer Language models](https://arxiv.org/abs/1709.07432).

My PhD thesis includes the papers mentioned here, plus work I did using dynamic evaluation to improve polyphonic music prediction. It also goes into far more detail about the intuition of why dynamic evaluation works well, and studies optimizers in a dynamic evaluation setting, where standard optimizers often struggle.

Krause, B. [Flexible Neural Architectures for Sequence Modeling](https://era.ed.ac.uk/bitstream/handle/1842/37088/Krause2020.pdf)

####[Multiplicative LSTM](https://arxiv.org/abs/1609.07959)

Multiplicative long short-term memory (mLSTM) is recurrent neural network architecture designed primarily for sequence modeling. mLSTM combines a [multiplicative RNN](http://www.cs.toronto.edu/~jmartens/docs/RNN_Language.pdf) and an LSTM. A large mLSTM was [used by Open AI](https://blog.openai.com/unsupervised-sentiment-neuron/) in their early work on unsupervised learning with language models. This mLSTM could be seen as the precursor to the GPT, GPT-2, GPT-3 series (or at least that's how I like to see it :) )

Krause, B., Lu, L., Murray, I., & Renals, S. (2016). [Multiplicative LSTM for sequence modelling](https://arxiv.org/abs/1609.07959). arXiv:1609.07959.

####[Taylorized Training](https://arxiv.org/pdf/2002.04010.pdf)

Work studying higher order Taylor series expansions of CNNs around their initialization, going all the way up to quartic approximations. This involves computing higher order directional derivatives of the forward pass, and learning a direction in weight space. We find that a quartic model using the 4th order derivatives of an untrained (finite width) resnet can achieve 79% on CIFAR-10.

Bai Y., Krause B., Wang H., Xiong C. & Socher, R. (2020). [Taylorized Training: Towards Better Approximation of Neural Network Training at Finite Width](https://arxiv.org/pdf/2002.04010.pdf). arXiv:2002.04010

####[Conversational AI](https://arxiv.org/abs/1709.09816)

During my time working on the Amazon Alexa prize, I developed data driven methods for building open domain conversation agents that combined retrieval and generative approaches, and contributed to the development of a new data collection technique called self-dialogues. Our conversation corpus collected from Amazon Mechanical Turk is publicly available [here](https://github.com/jfainberg/self_dialogue_corpus).

Krause, B., Damonte, M., Dobre, M., ... & Webber, B. (2017). [Edina: Building an Open Domain Socialbot with Self-dialogues](https://arxiv.org/abs/1709.09816). arXiv:1709.09816.

Joachim Fainberg, Ben Krause, Mihai Dobre, ... & Federico Fancellu (2018) [Talking to myself: self-dialogues as data for conversational agents](https://arxiv.org/abs/1809.06641)

####Optimization

My master's thesis and my early PhD work explored Hessian-free optimization in LSTMs

Krause, B. (2015). [Optimizing and Contrasting Recurrent Neural Network Architectures](https://arxiv.org/abs/1510.04953). arXiv:1510.04953.

Krause, B., Lu, L., Murray, I., & Renals, S. (2015). [On the Efficiency of Recurrent Neural Network Optimization Algorithms](http://opt-ml.org/papers/OPT2015_paper_25.pdf). NIPS Workshop on Optimization for Machine Learning, Montreal, Canada, 2015.

####Neuroimaging

I also have past neuroimaging research studying the role of neurotransmitters in brain blood flow and schizophrenia

Krause, B. W., Wijtenburg, S. A., Holcomb, H. H., Kochunov, P., Wang, D. J., Hong, L. E., & Rowland, L. M. (2014). [Anterior cingulate GABA levels predict whole-brain cerebral blood flow](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3963135/). Neuroscience letters, 561, 188-191.

Rowland, L. M., Krause, B. W., Wijtenburg, S. A., McMahon, R. P., Chiappelli, J., Nugent, K. L., ... & Hong, L. E. (2016). [Medial frontal GABA is lower in older schizophrenia: a MEGA-PRESS with macromolecule suppression study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4591074/). Molecular psychiatry, 21(2), 198-204.

Korenic, S. A., Nisonger, S. J., Krause, B. W., Wijtenburg, S. A., Hong, L. E., & Rowland, L. M. (2016). [Effectiveness of fast mapping to promote learning in schizophrenia. Schizophrenia Research: Cognition](https://www.sciencedirect.com/science/article/pii/S2215001316300099), 4, 24-31.

<body style = "background-image: url('../images/neurons2.jpg');background-repeat: no-repeat; background-position: right 50px ;background-size: 100% 140px;">
