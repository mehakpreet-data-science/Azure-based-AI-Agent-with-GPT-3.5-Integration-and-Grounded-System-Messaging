Developed a conversational AI agent using Azure OpenAI GPT-3.5 API, capable of providing intelligent, context-aware responses. The agent was designed to operate within a controlled enterprise environment, ensuring factual reliability through grounded system messages based on custom internal data sources. Leveraged Azure Functions, Azure Cognitive Services, and Azure Blob Storage to manage user prompts, dynamic system messages, and response pipelines.

Language Model: GPT-3.5 deployed via Azure OpenAI Studio
Architecture: Integrated with a REST API using Python and Flask, hosted on Azure App Service
Grounding Mechanism: Supplied a custom system message (prompt engineering) to guide the model with contextual enterprise data (stored in Azure Blob/SQL)
Use Case: Answered customer support questions using internal knowledge base articles and SOPs
Security: Used Azure Role-Based Access Control (RBAC) and API key encryption
Outcome: Delivered accurate, consistent responses grounded in approved company documents
