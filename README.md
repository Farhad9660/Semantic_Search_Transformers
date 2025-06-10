# Semantic_Search_Transformers
This Repository includes codes and data used for fine-tuning transformer models to create better embeddings for semantic search in classic poetry.

## The repository now consists of three forms of data : 

 *1.Fine-tune data*
    The data used for fine-tuning sentence transformers to create better embeddings. 
    This data is divided into train and eval data to train and evaluate sentence transformer models. (ft_train_data , ft_val_data)
    
 *2. Test data:*
    This data set is used for evaluating the performance of semantic search pipeline that we build with each sentence transformer.
    It can be used with both original and fine-tuned sentnece transformers. (Test_Data_Aggregated_Mordad_1403)
    
 *3. Zero_shot test data:*
    This  data has not been given to the models during fine-tuning.
    We used this data to evaluate our fine-tuned models’ generalizability over unseen data. (Zero_shot_test_data_Mordad_1403)

## Also there are two jupyter notebooks to use: 
*1. The fine tuning code (sentence_transformers_fine_tuning_2.ipynb):*

This notebook takes any sentence transformer and fine tune it based on fine tune data. 
*2. Main semantic search pipeline (Semantic_Search_Pipeline_Version_3_with_NDCG.ipynb):*

This is the main pipeline that implements semantic search using any of the emebdding models and evaluate theperformance with different criteria.
The performance criteria are: Recall, Precision, and	NDCG
