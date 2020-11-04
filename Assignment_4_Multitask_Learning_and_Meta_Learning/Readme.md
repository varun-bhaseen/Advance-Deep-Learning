<h1>Multi-task Learning</h1>
<p>Here we will give a brief explanation of how Multi Task learning works. Multi task learning has an assumption that states that all tasks that is expected out of the Multi task model needs to have a shared characteristics. An example would be like: if our Neural network is predicting a text generation as one task then it needs to also predict sentiment analysis, topic modelling etc. in a shared enural network.<br><br> Below is the explanantion of the Neural Network that we have used for Multi Task learning: </p>
<p>For Multi-task learning we are using Transformer network for doing multiple NLP tasks</p>


<h1>Meta-Learning</h1>
<p>For meta Learning we used reptile algorithm. It was developed by OpenAI to perform model agnostic meta learning. Specifically, this algorithm was designed to quickly learn to perform new tasks with minimal training (few-shot learning). The algorithm works by performing Stochastic Gradient Descent using the difference between weights trained on a mini-batch of never before seen data and the model weights prior to training over a fixed number of meta-iterations.<br>The Dataset used is omniglot Dataset</p>