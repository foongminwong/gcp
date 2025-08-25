## Google Cloud Platform (GCP)

[Introduction to AI and Machine Learning on Google Cloud](https://app.pluralsight.com/library/courses/introduction-ai-machine-learning-google-cloud/table-of-contents)

Module 1: Introduction
- AI Foundations
    - Cloud essentials e.g., compute, storage, network, and data tools such as data piplines & analytics
- AI Development
    - Predictive AI & Generative AI: Different options to build a machine learning project, including out‑of‑the‑box solutions, low code or no code, and DIY
- AI Development Workflow
    - Workflow to train & serve a ML model using Vertex AI (Google CLoud's AI Development Platform)
- Generative AI
    - How generative AI empowers the AI development and AI solutions layer (Vertical & horizontal solutions).

Module 2: AI Foundations - Cloud essentials & data tools, e.g., compute, storage, networking, etc. BigQuery
- Why AI?
    - Input -> Process -> Output
    - Multimodal -> Prediction & Generation -> Insights & Visualization
    - Multimodal Input:
        Various forms of data such as text, customer reviews, images, coffee and dessert pictures, and videos, real‑time street view
    - Prediction & generation:
        - Powered by (1) data analytics like customer segment analysis, (2) predictive AI like sales forecasting, route design, and (3) generative AI like marketing campaign automation, customer responses.
    - Insights & Visual Output:
        -  Insights & reports are presented visually, empowering businesses to make real‑time, data‑driven decisions and optimize their operations.
    - Tools:
        - Gemini multimodal: data Acquisition
        - BigQuery: Data Analytics
        - Vertex AI: ML Development
        Looker & google APIS: Data visualization & app creation
    - Architecture: 
        - Data acquisition -> AI/ analytics -> Visualization & activation
        - Data Ingestion (Data) -> Data Analytics (Data) -> Data Engineering (Data) -> Model Training (AI) -> Testing (AI) -> Deployment (AI)
        - Predictive AI: Predict trends & make classifications.
        - Generative AI: Generates content & perform tasks.

- AI/ ML on Google Cloud
    - History of Google data processing methods & contributions to AI advancements

- Google Cloud Infrastructure: 3 layers — networking & security -> Compute & Storage -> Data & AI ML/ Business products
Compute & Storage
    - Compute Engine: IaaS Offering, Compute, Storage, Network, Maximum Flexibility
    - Google Kubernetes Engine (GKE): Containerized applications, Cloud environment
    - App Engine: A fully managed PaaS offering, Binds code to libraries that provide access to the infrastructure app needs, Focus on app logic
    - Cloud Run: A fully managed platform to run requests or event-driven stateless workloads without worrying about servers, Let users focus on writing code, Automatically scales up & down, Charges only for resources you use
    - Cloud Run Functions: Code execution in response to events, Serverless execution environment, Functions as a service (Users don’t need to provision & manager servers)
    - Tensor Processing Unit (TPU) — Google’s custom-developed application-specific integrated circruits (ASICs) to accelerate ML workloads. TPUs > current GPUs & CPUs for AI &ML apps + more energy -efficient
    - Storage — Decoupled (cloud computing — compute & storage can scale separately) vs Coupled (desktop computing), Choose based on data type (e.g. unstructured vs structured) & business need
    - Classes of cloud storage for unstructured data: 
        - Standard storage: For frequently accessed / hot data, data stored for brief periods of time)     
        - Nearline storage: Infrequently accessed data e.g. data backups/ archiving. Once per month
        - Coldline storage: Low-cost option for storing infrequently accessed data. Once every 90 days
        - Archive storage: Lowest-cost option. Ideal for data archiving, online backup, disaster recovery. Only access data once year
    - Structured data: (Is your workload transactional or analytical?)
        - Transactional workloads: Online transaction processing systems. Fast data inserts & updates for row-based records. Maintain a system snapshot.
        - Transactional workload: Cloud Storage (SQL — Local/ regional scalability), Cloud SQL, Cloud Spanner (SQL — Global scalability), Firestore (NoSQL)
        - Analytical workloads: Online analytical processing systems. Used when entire datasets need to be read. Require complex queries e.g. aggregations
        - Analytical workload: BigQuery (SQL — Google data warehouse solution for petabyte-scale datasets analysis), Cloud Bigtable (NoSQL, real-time, high-throughput, milleseconds latency)

- Data & AI products
    - Data-to-AI workflows: Ingestion & process -> Storage -> Analytics (BigQuery) -> AI/ML (Vertex AI)
    - Ingestion & process: Digest real-time/ batch data, Pub-Sub, Dataflow, Dataproc, Cloud Data Fusion
    - Cloud Storage: See previous notes.
    - Analytics: BigQuery — analyze data via SQL commands, Looker (BI tools for data analysis & visualization)
    - AI/ ML with GenAI: Vertex AI — AutoML for predictive AI, Colab Enterprise, Vertex AI Studio, Model Garden for generative AI, Ai solutions (e.g. Document AI, Contact Center AI, Vertex AI Serach for Retail, Healthcare Data Engine)
    
- ML model categories
    - AI — Robots, self-driving cars
    - ML is a subset of AI
        - Supervised: Learn from labeled data, identify a goal. Classification (predict categorical variable — e.g., logistic regression) & Regression (predict numeric variable — e.g., linear regression)
        - Unsupervised: Learn from unlabeled data, identify pattern. Clustering (group data points together — e.g., k-means clustering), Association (Identify relationships- e.g., association rule learning), Dimensionality reduction (Reduce # of dimensions — e.g., principal component analysis)

- BigQuery ML: Storage & analytics (connected by Google’s high speed internal network which allows scaling compute & storage independently based on demand)
    - Fully managed storage for datasets + Fast SQL-based analytical engine
    - Manage tabular data & execute ML models in one place
    - MLOps:
        - Turn ML experiment to production, deploy, monitor & manage ML models
        - e.g., Import TensorFlow models for batch prediction, Export models from BigQuery ML for online predicition, Hyperparamter tuning using Vertex AI Vizier)