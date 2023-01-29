<h1 align="center">Skimlit: A NLP Model for Classifying Abstract Sentences</h1>

<p align="center">
  Skimlit is a machine learning model that can classify abstract sentences into different roles they play (e.g. objective, methods, results, etc.). It enables researchers to quickly skim through scientific literature and dive deeper into relevant details when necessary.
</p>

<h2 align="center">Tools and Technologies</h2>

<ul>
  <li>Tensorflow</li>
  <li>tensorflow_hub</li>
  <li>sklearn</li>
  <li>Matplotlib</li>
  <li>numpy</li>
  <li>pandas</li>
</ul>

<h2 align="center">Notebooks</h2>

<p align="center">
  All the notebooks used to train and evaluate Skimlit's models are available in this repository.
</p>

<h2 align="center">Models</h2>

<ul >
  <li>NaiveBiase Model: 72% Accuracy</li>
  <li>Conv1D Model: 78% Accuracy</li>
  <li>Model using Pretrained Token Embedding (Universal Sentence Embedding): 75% Accuracy</li>
  <li>Conv1D Model using Character Level Embedding: 73% Accuracy</li>
  <li>Model with both Token and Character Level Embedding: 76% Accuracy</li>
  <li>Model with Token, Character and Position Level Embedding (Reference: <a href="https://arxiv.org/pdf/1612.05251.pdf">https://arxiv.org/pdf/1612.05251.pdf</a>): 81% Accuracy</li>
</ul>
