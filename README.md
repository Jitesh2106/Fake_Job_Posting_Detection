# Fake_Job_Posting_Detection

This project aims to detect fake job postings using natural language processing (NLP) techniques. Two models, BERT (Bidirectional Encoder Representations from Transformers) and DistilBERT (distilled version of BERT), were employed to classify job postings as either genuine or fake based on the job descriptions provided.

## Files

The project folder in this GitHub repository contains the following files:

1. **Fake_Job_Posting_BERT.ipynb**: This Jupyter Notebook file contains the code for training and evaluating the BERT model for fake job posting detection.
2. **Fake_Job_Posting_DistillBERT.ipynb**: This Jupyter Notebook file contains the code for training and evaluating the DistilBERT model for fake job posting detection.
3. **fake_job_postings.csv**: This CSV file contains the dataset used for training and testing the models. It includes job postings along with labels indicating whether they are fake or genuine.

## Model Comparison

Both BERT and DistilBERT models were implemented and compared in this project. Here are the key points regarding the comparison:

- **BERT Model**: The first 6 encoder layers of BERT were frozen to reduce the training time. Additionally, the BERT fast tokenizer was utilized to enhance efficiency.
- **DistilBERT Model**: DistilBERT, a distilled version of BERT, was employed. It generally requires less computational resources and training time compared to the original BERT model.

## Performance

1. **Efficiency**: DistilBERT, being a distilled version of BERT, is more lightweight and computationally efficient while maintaining competitive performance.
2. **Training Time**: Due to its smaller size and fewer parameters, DistilBERT required less time for training, making it more suitable for large-scale applications.
3. **Resource Requirements**: DistilBERT consumes fewer computational resources, making it easier to deploy and utilize in resource-constrained environments.
4. **Generalization**: Despite its smaller size, DistilBERT demonstrated robust generalization capabilities, effectively capturing the nuances in job descriptions to detect fake postings.

## Conclusion

In conclusion, both the BERT and DistilBERT models demonstrated excellent performance in detecting fake job postings. Both models effectively captured the nuances in job descriptions and accurately classified postings as genuine or fake. The choice between the two models may depend on specific application requirements, but overall, both BERT and DistilBERT prove to be powerful tools for tackling the issue of fake job postings.


