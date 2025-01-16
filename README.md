# Finding French Politicians at Scale - Utilizing Vector Search to Optimize Synthetic Data Generation

We utilize Mistral-Large to generate labels for web-data in the low-resource, high-cost-to-label task of fine-grained named entity recognition. Then, we use this synthetic dataset to fine-tune a Mistral 7B model.

To extend this problem, we define a new fine-grained entity type, French politicians, and utilize our framework to rapidly generate synthetic data and train a downstream model. Scanning across an unlabeled dataset, we are able to identify 2174 mentions of French politicians compared to just 7 mentions in the labeled dataset.
