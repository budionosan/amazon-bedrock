## Amazon Bedrock Prompt Engineering

**promptEngineeringNova.ipynb** : prompt engineering using **Amazon Nova Lite**.

*NOTE* : Make sure you already enable Amazon Nova model in Amazon Bedrock console. If you want to try another Amazon Nova, you also can try **Nova Pro** or **Nova Premier** because can answer multimodal question, except Nova Micro can not answer.

## Amazon Bedrock Knowledge Base and Agent

*NOTE* : Before try this repository, get Pinecone host key to can connect to Amazon Bedrock, then store Pinecone host key to AWS Secret Manager.

**knowledgebaseAgent.ipynb** : RAG (Retrieval Augmented Generation) using **Amazon Bedrock** features such as **Bedrock Knowledge Base** and **Bedrock Agent**, **AWS Secret Manager** to store Pinecone host key, **Amazon Titan Embedding** to embedding, **Amazon S3** to store knowledge base and **Pinecone** to vector storage.