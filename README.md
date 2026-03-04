# Text Sentence Similarity Model Selection using TOPSIS

## Introduction
In this assignment, the TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) method is used to select the best pre-trained model for the task of **text sentence similarity**. The goal is to compare different sentence embedding models based on multiple criteria and rank them.

According to my roll number **102317253** (ending with 3), the assigned task category is **Text Sentence Similarity**.

## Models Compared
The following pre-trained models were compared:

- all-MiniLM-L6-v2  
- all-mpnet-base-v2  
- paraphrase-MiniLM-L6-v2  
- paraphrase-mpnet-base-v2  
- distilbert-base-nli-stsb  

These models are commonly used for generating sentence embeddings and measuring semantic similarity between sentences.

## Evaluation Criteria
The models were evaluated using the following criteria:

- **Accuracy (STS Score)** – Higher is better  
- **Inference Time** – Lower is better  
- **Model Size** – Lower is better  
- **Memory Usage** – Lower is better  

These criteria help balance performance and efficiency.

## Methodology
The TOPSIS method was applied in the following steps:

1. Create a decision matrix using model performance values.
2. Normalize the matrix.
3. Apply weights to each criterion.
4. Determine the ideal best and ideal worst solutions.
5. Calculate the distance of each model from these ideal points.
6. Compute the TOPSIS score and rank the models.

The model with the **highest TOPSIS score** is considered the best choice.

## Results
After applying the TOPSIS method, the models were ranked based on their scores. The results show which model provides the best balance between accuracy and efficiency for sentence similarity tasks.

A bar graph of the TOPSIS scores is included to visualize the ranking of the models.

## Conclusion
From the analysis, the model with the highest TOPSIS score can be considered the most suitable pre-trained model for text sentence similarity among the compared options. This approach helps in making a balanced decision by considering multiple performance factors rather than relying on a single metric.
