<h1 align="center">NLP</h1>
<h3>NLP: Natural language processing in particular is how toprogram computers to process and analyze large amounts of natural language data.</h3>
<h3>APPLICATONS OF NLP:</h3>
<h4> - Autocorrect & Autocomplete </h4>
<h4> - Voice Assistants </h4>
<h4> - Sentiment Analysis </h4>
<h4> - Text Extraction </h4>
<h4> - Text Summarization </h4>
<h4> - Speech Recognition </h4>

![img_1](https://github.com/lecaohao2101/Data-Summarization/assets/95235601/8248eae5-6c38-4a8d-9ad3-e1945d0ef804)

<h3>Transformers: The Hugging Face transformers package is an immensely popular Python library providing pre-trained models that are extraordinarily useful for a variety of natural language processing (NLP) tasks. Supports Pytorch and TensorFlow 2.0</h3>
<br/>
![img_2](https://github.com/lecaohao2101/Data-Summarization/assets/95235601/c67cbbc9-e368-434b-8682-481e65a2059a)
<br/>
![img_3](https://github.com/lecaohao2101/Data-Summarization/assets/95235601/8a0a7a0f-afd9-4d76-ac0d-ed5728ddda05)
<br/>

Say the following sentence is an input sentence we want to translate:

"The animal didn't cross the street because it was too tired"

What does "it" in this sentence refer to? Is it referring to the street or to the animal? It's a simple question to a human, but not as simple to an algorithm.

When the model is processing the word "it", self-attention allows it to associate "it" with "animal".

As the model processes each word (each position in the input sequence), self attention allows it to look at other positions in the input sequence for clues that can help lead to a better encoding for this word.

If your're familiar with RNNs, think of how maintaining a hidden state allows an RNN to incorporate it's representation of previous words/vectors it has processed with the current one it's processing. Self-attention is the method the Transformer uses to bake the "understanding" of other relevant words into the one we're currently processing.

<h3>The Difference</h3>
<h4> - Transformer: A Transformer is an algorithm that can transform one DataFrame into another DataFrame</h4>
<h4> - Estimator: An Estimator is an algorithm that can be fit on a DataFrame to produce a Transformer. E.g., a learning algorithm such as LogisticRegression is an Estimator, and calling fit() trains a LogisticRegressionModel, which is a Model and hence a Transformer.</h4>
<h4> - Pipeline: A Pipeline chains multiple Transformers and Estimators together to specify an ML workflow</h4>

<h3>Hugging Face - Pipelines: The pipelines are a great and easy way to use models for inference. These pipelines are objects that abstract most of the complex code from the library, offering a simple API dedicated to several tasks.</h3>
<h3>Training: Training refers to the process of creating a machine-learning algorithm</h3>
<h3>Inference: Inference refers to the process of using a trained machine-learning algorithm to make a prediction</h3>


<h1 align="center">Run The Program</h1>
- pip install -r requirements.txt
<br/>
- flask run
