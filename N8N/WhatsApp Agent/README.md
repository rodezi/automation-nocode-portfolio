# This was a RAG Assistant conected to Twilio / WhatsApp.

This workflow was a whatsapp assistant ai agent for real estate. 

Documented code:

## For the first nodes (The ones above)

1. First two nodes work to retrieve the documents from Google Drive.
2. We load the documents in PDF
3. we load the documents into Pinecone vector store
4. We use Gemini Embeddings to get numerical representations of the text.

## For the second workflow 

1. It starts with a webhook
2. A delay next to avoid overload
3. AI Agent: The instruction was to be an assistant and close appointments.
4. Tools of the agent: Gemini as the LLM, websearch for the webpage of the business, Google Calendar to store the appointments.
5. Pinecone connected to retrieve the information about any specific enquirie.


<img width="958" height="427" alt="n8n 1" src="https://github.com/user-attachments/assets/b6aa67ee-7740-44cf-b211-a2823d7adfbf" />
