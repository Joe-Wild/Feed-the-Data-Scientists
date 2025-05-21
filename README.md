FEED THE DATA SCIENTISTS
(Cloud Solution)
JOE WILD


The goal of this architecture is to create a collector of opinions or feelings in response to specific subjects.
For example, it may involve collecting reactions to a Presidential decision such as the general opinion on the release of a film. The code coming from “Hugging” Face (French Start-up) is established in Vscode and its image in a Docker Container (via Docker file) runs in the cloud using the AWS ECS fargate service.
Thanks to the API given from “X application” we should be able to select the data (responses to a post) to analyse (such as positive_negative_or neutral) with the Hugging codes model, to store them in Aws S3 and then, process in a third time to a sorting with Databricks (for future investigations).
For what? For the study of actions and their reactions. For knowledges. For learning.

To avoid repeating the same mistakes in the future for example:

All this architecture is orchestrated with Terraform, all the files needed are in the compressed .rar folder.
I hope I have been as clear as possible in the explanation and purpose of this instrument, especially in the slides of the development phase.

Research:
https://huggingface.co/blog/sentiment-analysis-python
https://arxiv.org/abs/2106.09462
httpsdoi.org10.1609aaai.v34i01.5460
https://github.com/osome-iu/botometer-python?tab=readme-ov-file#dependencies
