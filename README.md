# Gen AI HR Assistant
The idea is to create a Teams Bot that takes the language from user and understands the intent and generats meaningful response to user
## Design
Below is the high level overview of the solution
1) Used Azure storage account to store the documents
2) Created Azure Open AI service
3) Created GPT-4 deployment base model
4) Created AI Search and Text Embeddings in Deployment models to enable vector search for the agents
5) Created Teams bot to interact with user
## Advantages
Currently the HR team needs to analyze the 100s of documents to select the candidate for qualifying job. With this teams bot it summarizes the profile of the user and collectively gives a response to HR admin using NLP and analytics which will be easy for the admin to make a decision on next steps. 

# Pre-Requisites
It is required to have following
1) Azure Subscription
2) Azure AI Search
3) Azure Open AI Service
4) M365 Tenant (Dev or Prod)
