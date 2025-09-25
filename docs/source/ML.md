# Basics of AI, ML, Gen AI

```{mermaid}
%%{init: {'theme': 'mc', 'layout': 'elk'}}%%

flowchart TD
    A["Artifical Intelligence"] --> B["Machine Learning"] & a1("Speech Recognition, Robotics, Self-Driving Cars")
    B --> C["Neural Networks"] & b1("Linear/Logistic Regression, Classification, Decision Tree, Random Forest, SVM, PCA, KMeans, DBScan, AdaBoost")
    C --> D["Deep Learning"] & c1("Perceptron, MLP, Backpropgation, Hopfield network, Boltzmann Machine, Self-Organizing Maps")
    D --> E["Generative AI"] & d1("CNN, RNN, LSTM, Auto-Encoders, Encoder-Decoder, Embeddings,Transformers, GPT, BERT")
    E --> g1@{ label: "Large Language Models, Foundational Models, Generative Adversarial Networks 'GANs', Prompt Tuning, RAG, Agents, QLoRA, Langchain, VectorDb, Vector Search" }
    g1@{ shape: rounded}

```

- [Lesson 01: Introduction to ML](L1_Introduction_to_ML.md)