# Intelligent Document Processing(IDP) with Generative AI models


## Lab1

This lab introduces the concept of Large Language Models (LLMs) and demonstrates how you can deploy one in SageMaker JumpStart. We discuss different types of models, look at the instances required to deploy them, and go through a few common use cases.

- [Zero-shot prompting for the Flan-T5 foundation model in Amazon SageMaker JumpStart](https://aws.amazon.com/blogs/machine-learning/zero-shot-prompting-for-the-flan-t5-foundation-model-in-amazon-sagemaker-jumpstart/)
- [Deploy FLAN-T5 XXL on Amazon SageMaker](https://www.philschmid.de/deploy-flan-t5-sagemaker)

## Lab2

We often see privacy and PII redaction come up in IDP conversations. It is critical to protect common PII such as names, phone numbers, and dates of birth during document processing. In this notebook, we will use Amazon Textract and Amazon Comprehend alongside our LLM to make our IDP workflow more secure.

- [Personally identifiable information (PII) with Amazon Comprehend](https://docs.aws.amazon.com/comprehend/latest/dg/pii.html)
- [Detecting and redacting PII using Amazon Comprehend](https://aws.amazon.com/blogs/machine-learning/detecting-and-redacting-pii-using-amazon-comprehend/)



## Note

Compute Instances

- Due to [Event Engine limitation](https://catalog.workshops.aws/docs/en-US/detailed-documentation/supported-aws-services/sagemaker-service-limits), only specific EC2 instances are available in the workshop. Please your own account for ml.g5.8xlarge or above instances.

Privacy and Security

- [AWS GDPR center](https://aws.amazon.com/compliance/gdpr-center/)
- [Introducing AWS AI Service Cards: A new resource to enhance transparency and advance responsible AI](https://aws.amazon.com/blogs/machine-learning/introducing-aws-ai-service-cards-a-new-resource-to-enhance-transparency-and-advance-responsible-ai/)
