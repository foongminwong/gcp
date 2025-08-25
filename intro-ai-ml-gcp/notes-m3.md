## Google Cloud Platform (GCP)

[Introduction to AI and Machine Learning on Google Cloud](https://www.coursera.org/learn/introduction-to-ai-and-machine-learning-on-google-cloud/home/welcome)

Module 3: AI Development Options
- ML options, 
- AI Development Options: Preconfigured (Pretrained APIs), low code/ no-code (BigQuery ML,AutoML), DIY approach (Custom training)
    - Pre-trained APIs, BigQuery ML, AutoML, Custom Training
- Pretrained APIs
    - Offered as services
    - Example: Speech, text & language API, Image & Video API, Document & data API, Conversational AI API
    - Generative AI API
- VertexAI - Code or No-code Platform to build ML model
    - Born in 2021
    - Save data scientists time so they can focus on model configuration 
    - Data readiness -> Feature readiness -> Training & hyperparameter tuning ->  - Deployment & model monitoring 
    - Vertex AI = Predictive AI + Generative AI
    - Vertex AI - AutoML, Custom Training
    - 4S - Seamless, Scalable, Sustainable, Speedy

- AutoML on VertexAI - Low code or no code to automate ML development 
    -   - Automated ML
    -   - Automated feature engineering/ data processing -> Architecture search & tuning -> Bagging ensemble -> Prediction
    -   - Neural architecture search (find optimal models) & transfer learning (smaller datasets & less computational power)
    -   - Can use multiple models depends on the budget
    -   - Automated feature engineering, architecture search, hyperparameter tuning, model assembly

- Custom training via Keras/ TensorFlow
    - Prebuilt container or Custom container
    - Colab enterprise, Vertex AI Colab
    - ML libraries, such as TensorFlow contains multiple abstraction layers
    - Run TF at scale on VertexAI managed service 
        - CPU, GPU, TPU: Can run on different hardware
        - Core Tensorflow (C++, Python): Low-level TF API
        - tf.layers, tf.losses, tf.metrics..: TF model libraries
        - tf.keras, tf.data: High-level TF API
    - TF Keras
    - JAX - new framework for ML
- Lab: Natural Language APi
