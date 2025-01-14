# Papers

### Trajectory Planning for Surgical Robots using Reinforcement Learning
- __Path__: Masterthesis/... (NDA)  
- __Description__: Cataract is the leading cause of blindness worldwide, with an increasing number of patients due to changing demographics. During my thesis, I focused on training a Reinforcement Learning (RL) agent on a substep of cataract surgery, the Continuous Curvilinear Capsulorhexis (CCC). This was based on a physically realistic simulation that mimics the tearing behavior of soft tissue during CCC. This work covers the implementation, training, and evaluation of the trained policies. It also lays the groundwork for future sim-to-real transfer by integrating domain randomization techniques. The results contributed to a paper titled "Lens Capsule Tearing in Cataract Surgery using Reinforcement Learning", which has been accepted at ICRA 2024. 

<p align="center">
  <img width="400" height="300" src="images/MA.png">
</p>
Paper: https://events.infovaya.com/presentation?id=122252

### Multi-camera based Real-time Recognition and Tracking of Multiple Persons
- __Path__: Bachelorthesis/Chettaoui_BA_thesis  
- __Description__: In order to improve safety in human-robot collaboration, we created a real-time human pose recognition and tracking system. In this thesis we start by detecting people and localizing their keypoints, like the hands or the nose, in images using convolutional neural network based algorithms. The keypoint prediction algorithm will process data from two or more different cameras in real-time. With the 2D keypoints location from each perspective, we construct a human model in 3D space using triangulation, which is a process to determine points in 3D space given its projections onto at least two images. Finally, we implemented a multi-person tracking algorithm to recognize a specific person on two different images. We evaluated each property of our system using various tests. We compared the precision and the inference time of the keypoints prediction algorithms in 2D image plane. We then evaluated the precision of our triangulation algorithm and we analyzed its stability when switching camera pairs to perform 3D reconstruction.


<p align="center">
  <img width="800" height="300" src="images/BA.png">
</p>


### Generative models and inverse design
- __Path__: Seminar/Generative models and inverse design/Chettaoui_Paper_Generative_Models_And_Inverse_Design  
- __Description__: Identifying new molecules with desirable properties can lead to monumental scientific, technological
and biomedical advances. With the tremendous chemical space to explore, computational
molecular design is limited by the search strategy and is extremely costly. Recent
advances in machine learning produced powerful probabilistic generative models that are able
to produce realistic synthetic molecules. Generative models, based on autoencoders (AEs),
generative adversarial networks (GANs) or reinforcement learning (RL) have shown promising
results. Experiments proofed that the latent space is indeed capturing features relevant to
molecules. This leads to the generation of new molecules with desired properties discovered
through generative models and inverse molecule design.

<p align="center">
  <img width="550" height="180" src="images/GMID.png">
</p>

### Open-domain Question Answering
- __Path__: Seminar/Open-domain Question Answering/Chettaoui_Paper_Open-domain_Question_Answering  
- __Description__: Question answering (QA) is concerned with building systems that automatically answer
questions posed by humans in a natural language.
The retriever-reader architecture is dominating,
and the extractive reader is mostly chosen
over the generative reader, while there are
several advantages to generating answers even
when it is possible to extract them. Documents
with clues about the answer, but do not contain
the exact answer can still contribute towards a
correct answer being generated, which is not
possible with standard extractive approaches.
In this paper we will explore a generative approach,
namely Retrieval-Augmented Generation
(RAG), and show it can compete with
state-of-the-art approaches.

<p align="center">
  <img width="550" height="180" src="images/QA.png">
</p>

