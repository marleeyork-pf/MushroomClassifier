<!-- MushroomCNN README (HTML) -->

<h1>MushroomCNN</h1>
<p><strong>Classifying mushroom images by genus with CNN</strong></p>

<hr>

<h2>TLDR</h2>
<p>
  <strong>MushroomCNN</strong> uses a <strong>Convolutional Neural Network (CNN)<strong> to classify images of
    mushrooms by their genus. I preprocessed and trained the CNN on 10,000 raw images of various sizes.
</p>

<h2>Highlights</h2>
<ul>
  <li><strong>Image preprocessing</strong>: image reshaping and RGB normalization</li>
  <li><strong>Training and testing</strong>: trained and tested CNN model across genus categories </strong></li>
  <li><strong>Deep Leraning</strong>: Convolutional Neural Network (CNN), Feed-Forward Deep Neural Net (DNN)</li>
  <li><strong>Hyperparameter Tuning</strong>: depth, dropout, pooling, optimizers, criterion</li>
</ul>

<h2>Architecture</h2>
<p>
  The CNN is designed with 4 convolutional layers connected to 3 feed-forward DNN layers, each with an
  activation function (LeakyRelu for hidden, softmax for terminal). Pooling and dropout was included
  in each convolutional layer. Cross entropy loss was the selected criterion with a stochastic gradient
  descent as the optimizer. The CNN was batch trained for 75 epochs.
</p>

<h2>Skills</h2>
<ul>
  <li><strong>Languages</strong>: Python</li>
  <li><strong>Libraries</strong>: PyTorch, matplotlib, numpy</li>
  <li><strong>Compute</strong>: Jupyter Notebook</li>
  <li><strong>Data Source</strong>: <a href="https://www.kaggle.com/datasets/maysee/mushrooms-classification-common-genuss-images">AmeriFlux Network</a></li>
</ul>

<h2>Contact</h2>

<p>
  For questions or collaboration: <strong>marleeyork2025@gmail.com</strong><br>
<p>
  <img alt="License" src="https://img.shields.io/badge/license-MIT-blue.svg="badge/status-research--prototype-purple.svg
</p>
