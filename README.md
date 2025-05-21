FEED THE DATA SCIENTISTS

(Cloud Solution)

JOE WILD

Objective of the Architecture
This architecture aims to collect and analyze opinions or sentiments in response to specific topics or events, such as public reactions to a presidential decision or the general sentiment toward a film release. The system leverages a machine learning model from Hugging Face, a French startup, implemented in Visual Studio Code. The model is containerized using a Dockerfile and deployed in the cloud via AWS ECS Fargate.

Using the API provided by the X application, the system extracts relevant data (e.g., responses to a post) and analyzes sentiments (positive, negative, or neutral) with the Hugging Face model. The processed data is stored in AWS S3 for persistence. Subsequently, Databricks is used for advanced sorting and analysis to support future investigations. 

The purpose of this architecture is to study actions and their corresponding reactions, fostering knowledge and learning. By analyzing sentiments, we aim to understand public responses to avoid repeating past mistakes and inform decision-making.
The entire infrastructure is orchestrated using Terraform, with all necessary configuration files included in the provided compressed .rar folder. I hope this explanation, along with the slides from the development phase, clearly conveys the instrument’s purpose and functionality.

Research:

https://huggingface.co/blog/sentiment-analysis-python

https://arxiv.org/abs/2106.09462

https://doi.org10.1609aaai.v34i01.5460

https://github.com/osome-iu/botometer-python?tab=readme-ov-file#dependencies
