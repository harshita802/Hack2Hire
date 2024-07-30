# Model Performance
GPT and BERT were prone to overfitting and showed bad results because of using their smaller versions , upgrading to bigger pre-trained BERT could be effective ,T5 showed better results and optimization but the training time was higher because of hardware limitations.

# Noval Improvements
### Hybrid Approach
: Combining predictions from multiple models or architectures to improve overall performance. Ensembling techniques can help mitigate the weaknesses of individual models
### Using Larger Models:
Using the larger versions of Model's may improve the overall performance of the model and better fine tunning can reduce the run time and bring better precision and recall.

# Challenges and Constraints

## Model Size and Training Complexity

### Large Models

Training large models, such as BERT-Large or T5, is computationally intensive and requires substantial GPU resources. These models can be slow to train and may exceed available memory, leading to increased training times and costs.

### Overfitting in Smaller Models

Smaller models displayed overfit due to their limited capacity, resulting in poor generalization on unseen data. They may be capturing noise in the training set rather than learning meaningful patterns.

## Hardware Limitations

**GPU Availability**: Limited GPU resources on local machines and online platforms restricted the ability to train large models or use extensive hyperparameter searches. Training on smaller batches or using cloud-based solutions could  mitigate this issue but may incur additional costs and hinder the required results.

## Code and Training Constraints

**Incomplete Training**: Due to hardware constraints, the training process was not  completed, affecting the final performance of the model's. The structure and preliminary results can guide further experimentation when more resources are available.
