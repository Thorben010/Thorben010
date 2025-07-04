## 👋 Hi, I'm Thorben – a 3rd-year PhD at TUM, exploring the intersection of Machine Learning and Materials Discovery! 🚀  

I’m passionate about advancing materials science by integrating state of the art AI techniques. My contributions span from materials representation learning to NLP. 🌟  

---
### 🧪 **Materials Science**

**LLMForge: Language Models Enable Data-Augmented Synthesis Planning for Inorganic Materials**  
- Benchmarking of seven state-of-the-art LMs on precursor recommendation and synthesis-condition regression, achieving up to 53.8% Top-1 precursor accuracy and MAEs below 126 °C. Generated 28,548 synthetic solid-state recipes via OpenAI GPT-4.1, expanding current dataset size by 616 % over literature-mined protocols.    
- **Methods**: Large Language Models, Data Augmentation, Transformer Pretraining, Ensemble Modeling  
- **Repository**: [Project GitHub](https://github.com/Thorben010/llm_synthesis) & [Dataset](https://huggingface.co/datasets/thor1/LLMForge)  

<div align="center">
  <img src="https://github.com/Thorben010/SyntMTE/blob/master/figures/condition_regression.png" alt="Condition Regression Performance" width="600"/>
</div>



**MTENCODER: A Multi-task Pretrained Transformer Encoder for Materials Representation Learning**  
- Developed a transformer-based encoder co-trained across diverse materials properties and a denoising objective, resulting in robust and generalizable materials representations.
- **Methods**: Multi-task Learning, Transformer Architecture, Denoising Autoencoders
- **Paper**: [(NeurIPS AI4Mat) MTENCODER: A Multi-task Pretrained Transformer Encoder for Materials Representation Learning](https://openreview.net/pdf?id=wug7i3O7y1) 
  <div align="center">
    <img src="figures/mtencoder.jpg" alt="MTENCODER" width="600"/>
  </div>

**Reaction Graph Networks for Inorganic Synthesis Condition Prediction**  
- Combined a Deep Learned Material Encoder with Graph Networks to model precursor interactions in inorganic reactions, enabling the prediction of synthesis conditions for solid-state materials.
- **Methods**: Graph Neural Networks, Inorganic Reaction Modeling, Synthesis Condition Prediction
- **Paper**: [(NeurIPS AI4Mat) Reaction Graph Networks for Inorganic Synthesis Condition Prediction](https://openreview.net/forum?id=VGsXQOTs1E)

<div align="center">
  <img src="figures/rgn.jpg" alt="Reaction Graph Network" width="600"/>
</div>

**A Chemically-Guided Generative Diffusion Model for Materials Synthesis Planning**  
- Introduces a generative model utilizing diffusion processes to predict viable synthesis routes for zeolite materials, considering the complex one-to-many relationships between structure and synthesis.
- **Methods**: Diffusion Models, Generative Modeling, Materials Synthesis Prediction
- **Paper**: [(NeurIPS AI4Mat Spotlight) A Chemically-Guided Generative Diffusion Model for Materials Synthesis Planning](https://openreview.net/pdf?id=hy39qxU6CQ)
  
<div align="center">
  <img src="figures/denoising_diffusion.png" alt="Denoising Diffusion PNG" width="60%" style="margin-right: 5%;">
  <img src="figures/denoising_diffusion.gif" alt="Denoising Diffusion GIF" width="15%">
</div>
  
---
### 📖 **Natural Language Processing**

**Augmenting Scientific Creativity with Retrieval across Knowledge Domains**  
- Developed an exploratory search system enabling scientists to select core text from a paper abstract and retrieve cross-domain papers with high similarity, facilitating knowledge transfer across scientific domains.  
- **Methods**: Sentence Transformers, Clustering Techniques & Metrics  
- **Paper**: [(NAACL 2022) Augmenting Scientific Creativity with Retrieval across Knowledge Domains](https://arxiv.org/pdf/2206.01328)  
- **Code**: [GitHub Repository](https://github.com/olivettigroup/cross-domain-exploration)  
<div align="center">
  <img src="figures/scientific_creativity.jpg" alt="Scientific Creativity" width="400"/>
</div>

**Extracting a Database of Challenges and Mitigation Strategies for Sodium-ion Battery Development**  
- Created a detailed database highlighting performance and synthesis challenges in sodium-ion battery (SIB) cathode materials, alongside proposed mitigation strategies, to accelerate SIB research and development.
- **Methods**: Open Information Extraction, Named Entity Recognition, Coreference Resolution 
- **Paper**: [(NeurIPS AI4Mat) Extracting a Database of Challenges and Mitigation Strategies for Sodium-ion Battery Development](https://openreview.net/pdf?id=3GiwwOJ1be)  
- **Code**: [GitHub Repository](https://github.com/olivettigroup/NLP4SIB)  
  <div align="center">
    <img src="figures/sib_cluster.jpg" alt="SIB Challenges" width="600"/>
  </div> 

**Regress, Don't Guess – A Regression-like Loss on Number Tokens for Language Models**  
- Introduced a novel loss function that enhance language models' numerical reasoning by considering the proximity between number tokens, thereby improving arithmetic capabilities.  
- **Methods**: Autoregressive Transformers (T5) 
- **Paper**: [(NeurIPS MathAI) Regress, Don't Guess – A Regression-like Loss on Number Tokens for Language Models](https://arxiv.org/pdf/2411.02083)  
- **Code**: [GitHub Repository](https://github.com/tum-ai/number-token-loss)  
  <div align="center">
    <img src="figures/ntl.jpg" alt="Regression-like Loss on Number Tokens" width="400"/>
  </div>

---
