```mermaid
flowchart TD
    LinearAlgebra --> Math
    DifferentialCalculus -->Math

    Probability --> Statistics
    Bayes'Teorem --> Statistics
    Likelihood --> Statistics

    Math --> DeepLearning
    Statistics --> DeepLearning

    Python --> Pytorch
    Conda --> Pytorch
    Pytorch --> DeepLearning

    DeepLearning --> CNN
    DeepLearning --> RNN
    DeepLearning --> LSTM
    DeepLearning --> Transformer
    DeepLearning --> GAN
    DeepLearning --> VAE
    DeepLearning --> DiffusionModel
    DeepL

    OD{ObjectDetection}
    LLM{LLM}
    IS{ImageSynthesis}
    IC{ImageClassification}
    SR{SpeechRecognition}

    CNN --> OD
    CNN --> IC
    LSTM --> SR
    Transformer --> LLM
    Transformer --> ViT
    ViT --> OD
    ViT --> IC
    GAN --> IS
    VAE --> IS
    VAE --> cVAE
    cVAE --> IS
    DiffusionModel --> IS

```