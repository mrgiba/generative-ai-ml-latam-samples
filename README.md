# Generative AI/ML LATAM Samples

This repo provides Generative AI and AI/ML code samples, blueprints (end-to-end solutions) and proof of concepts oriented to the LATAM market

## Getting started

This repo is organized as follows:

### Blueprints

End-to-end solutions for a specific use case. 
  * They include [CloudFormation](https://aws.amazon.com/cloudformation/) templates to provision the solution to your account. 
  * They may include a demo UI.

Here is a list of available blueprints:

| Use Case                                                    | Industry                                | Description                    | Type        | Languages                                      |
|-------------------------------------------------------------|-----------------------------------------|--------------------------------|-------------|------------------------------------------------|
| [Multipage Document Analysis](blueprints/multipage-document-analysis/) | Financial Services/Legal/Cross-industry | Use this blueprint to extract key information from lengthy documents in highly regulated industries you can leveraging Amazon Bedrock and the Claude 3 family of LLMs. | Backend (Pyhton) + UI (React) | Spanish, English                               |
| [Contract Compliance Analysis](https://github.com/aws-samples/generative-ai-cdk-constructs-samples/tree/main/samples/contract-compliance-analysis) | Legal / Cross-industry                  | This project automates the analysis of contracts by splitting them into clauses, determining clause types, evaluating compliance against a customer's legal guidelines, and assessing overall contract risk based on the number of compliant clauses. This is achieved through a workflow that leverages Large Language Models via Amazon Bedrock. | Python for Backend, TypeScript (React) for Frontend | English (can be customized to other languages) |


### Samples
Code samples/notebooks that demonstrate a specific AI/ML functionality in AWS.

Here is a list of available samples:

| Use Case                                                    | Industry                                | Description                    | Type        | Languages        |
|-------------------------------------------------------------|-----------------------------------------|--------------------------------|-------------|------------------|
| [SQL Agent with Amazon Bedrock](samples/sql-bedrock-agent/README.md) | Cross Industry, Business Insights |Build and deploy a SQL Agent that lets users query databases using natural language instead of writing SQL code. The implementation combines enterprise features from Amazon Bedrock with LangChain's specialized SQL tools. | CDK Python| Multilanguage |
| [Whatsapp with Agents for Amazon Bedrock](samples/end-user-messaging-bedrock/README.md) | Cross Industry, Customer Experience | Implement a WhatsApp communication channel using AWS End User Messaging for social integration. Integrate your business logic with Amazon Bedrock Agents for AI-powered interactions. | CDK Python| Multilanguage |

### Proof of concepts:
  * Code samples/notebooks that aim to prove a concept in Generative AI or AIML.
  * Research paper techniques implementations
  * Novel tecniques implementations
  * May include Cloudformation / CDK

## Contributing

Please refer to the [CONTRIBUTING](CONTRIBUTING.md) document for further details on contributing to this repository. 
