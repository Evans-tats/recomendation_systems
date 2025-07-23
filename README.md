
# recomendation_systems
testing differenta recommendation sysytems

# OVERVIEW OF RECOMMENDATION ALGORITHMS

 | Name                                       | Description                            |
| ------------------------------------------ | -------------------------------------- |
| **Item-based CF**                          | Recommend similar items to those liked |
| **User-based CF**                          | Recommend items liked by similar users |
| **Cosine similarity / k-NN**               | Fast to implement, intuitive           |
| ✅ Best for: small datasets, explainability |                                        |


| Name                                                                     | Description                           |
| ------------------------------------------------------------------------ | ------------------------------------- |
| **Matrix Factorization (SVD, ALS)**                                      | Learns latent factors for users/items |
| **Neural Collaborative Filtering (NCF)**                                 | Non-linear MF using DNN               |
| ✅ Best for: capturing deeper user-item relationships, mid-scale datasets |                                       |



| Model                                                         | Use Case                                     |
| ------------------------------------------------------------- | -------------------------------------------- |
| **AutoRec**                                                   | Sparse data, unsupervised reconstruction     |
| **Wide & Deep**                                               | Metadata + high-dimensional input            |
| **DeepFM**                                                    | Combine FM with deep learning                |
| **GRU4Rec**                                                   | Session-based (sequential interactions)      |
| **BERT4Rec / SASRec**                                         | Transformer-based, sequential recommendation |
| ✅ Best for: scale, personalization, modeling complex behavior |                                              |

# TO DO LIST

🌱 getting started : Build item-based CF using cosine similarity   Dataset: MovieLens 100k     Tools: Python + Pandas + Scikit-learn
🌿 Intermediate:   Implement Matrix Factorization (SVD) or ALS       Try Neural Collaborative Filtering in PyTorch or TensorFlow
🌳 Advanced:  Train a Wide & Deep or Transformer-based model (e.g. SASRec)     Use TensorFlow Recommenders or NVIDIA Merlin
