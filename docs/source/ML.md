# Machine Learning Course

#### AI vs ML VS GenAI

```{mermaid}
%%{init: {'theme': 'neutral', 'layout': 'elk'}}%%

flowchart LR
    A["Artifical Intelligence"] --- a1("Speech Recognition, Robotics, Self-Driving Cars")
    B["Machine Learning"]
    C["Neural Networks"] 
    B --- b1("`Linear/Logistic Regression, \n Classification, \n Decision Tree, \n Random Forest, SVM, PCA, KMeans,\n  DBScan, AdaBoost`")
    D["Deep Learning"] 
    C --- c1("`Perceptron, MLP, \n Backpropgation, \n Hopfield network, \n Boltzmann Machine, \n Self-Organizing Maps`")
    E["Generative AI"] 
    D --- d1("`CNN, RNN, LSTM, Auto-Encoders, Encoder-Decoder, Embeddings,Transformers, GPT, BERT`")
    E --- e1("`Large Language Models, \n Foundational Models, \n Generative Adversarial Networks 'GANs', \n Prompt Tuning, RAG, Agents, \n QLoRA, Langchain, \n VectorDb, Vector Search`")

    

```

#### [Lesson 01: Introduction to ML](L1_Introduction_to_ML.md)