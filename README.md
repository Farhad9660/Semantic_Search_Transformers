# Semantic_Search_Transformers
This Repository includes codes and data used for fine-tuning transformer models to create better embeddings for semantic search in classic poetry
The repository now consists of three forms of data : 
 1.Fine-tune data
    The data used for fine-tuning sentence transformers to create better embeddings. 
    This data is divided into train and eval data to train and evaluate sentence transformer models.
 2. Test data: 
    This data set is used for evaluating the performance of semantic search pipeline that we build with each sentence transformer.
    It can be used with both original and fine-tuned sentnece transformers. 
 3. Zero_shut test data: 
    This  data has not been given to the models during fine-tuning.
    We used this data to evaluate our fine-tuned models’ generalizability over unseen data.
