#  Solution Accelerators
## Objectives
Copilot Studio is a native tool that can be extended with various Azure AI capabilities. Thanks to Microsoft’s accelerators, we can enhance its functionality and significantly improve performance. In this document, we’ll explore how each accelerator can support and complement Copilot Studio to achieve this goal.
## GPT-RAG
Copilot Studio provides native capabilities for generating answers and connecting basic queries to Azure AI Search. However, in many scenarios, this isn't sufficient. To deliver more accurate and context-rich responses, we need to implement Retrieval-Augmented Generation (RAG). This approach is especially valuable when customers need to index a large volume of documents and require high accuracy in the generative responses. By leveraging the [GPT RAG accelerator](https://github.com/Azure/gpt-rag?tab=readme-ov-file) alongside Copilot Studio, we can significantly accelerate the adoption of this advanced technology.
The [GPT-RAG](https://github.com/Azure/gpt-rag?tab=readme-ov-file) acceleration can significally helps in the data Ingestion service automates the processing of diverse document types—such as PDFs, images, spreadsheets, transcripts, and SharePoint files—preparing them for indexing in Azure AI Search. It uses intelligent chunking strategies tailored to each format, generates text and image embeddings, and enables rich, multimodal retrieval experies for agent-based RAG applications.

We use this accelerator speacially for blob storage and Sharepoint.

## Document procesing 

[Document procesing](https://github.com/Azure/doc-proc-solution-accelerator) is a comprehensive, enterprise-ready document processing solution built on Azure that enables organizations to rapidly deploy and scale document processing workflows. This accelerator combines the power of Azure AI services, cloud-native architecture, and modern development practices to provide a complete platform for document ingestion, processing, and analysis.

We will use this acceleratior specially when we use different storge than blob storage or Sharepoint
