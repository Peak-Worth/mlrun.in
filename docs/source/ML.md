# Basics of AI, ML, Gen AI

```{mermaid}
graph TD
    subgraph A[Artifical Intelligence]
        a1(Speech Recognition, Robotics, Self-Driving Cars)
        subgraph B[Machine Learning]
            b1(Linear/Logistic Regression, Classification, Decision Tree, Random Forest, SVM, PCA, KMeans, DBScan, AdaBoost)
            subgraph C[Neural Networks]
                c1(Perceptron, MLP, Backpropgation, Hopfield network, Boltzmann Machine, Self-Organizing Maps)
                subgraph D[Deep Learning]
                    d1(CNN, RNN, LSTM, Auto-Encoders, Encoder-Decoder, Embeddings,Transformers, GPT, BERT)
                    subgraph E[Generative AI]
                        g1(Large Language Models, Foundational Models, Generative Adversarial Networks 'GANs', Prompt Tuning, RAG, Agents, QLoRA, Langchain, VectorDb, Vector Search)

                    end
                end
            end

        end
    end
```