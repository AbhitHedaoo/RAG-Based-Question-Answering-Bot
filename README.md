# RAG-Based-Question-Answering-Bot

A streamlined AI-powered document question-answering application designed to retrieve information from PDF documents with contextual relevance and accuracy, utilizing LangChain and FAISS for efficient document retrieval and processing.

**What is RAG**: RAG, or Retrieval Augmented Generation, is a technique that combines the capabilities of a pre-trained large language model with an external data source. This approach combines the generative power of LLMs like GPT-3 or GPT-4 with the precision of specialized data search mechanisms, resulting in a system that can offer nuanced responses.

**Project Description**: Document Q&A Bot is an intelligent system that processes PDF documents, enabling users to ask questions and receive responses derived directly from the document's content. It combines advanced language processing using LangChain’s document retrieval and embeddings capabilities, leveraging Google Generative AI and FAISS for high-speed vectorized document search. This project is designed for those seeking a scalable and accurate solution for document-based question answering.

**Key Features**:
- **Contextual Q&A**: Provides responses based on the exact context within the document.
- **Efficient Retrieval**: Uses FAISS for quick retrieval of relevant document chunks.
- **Dynamic Embedding and Chaining**: Integrates embeddings from Google Generative AI and Groq language models to enhance document understanding.
- **Scalable and Modular**: Easily adaptable for different document collections and contexts.
  
**Technology Stack**:
- **LangChain**: For seamless chaining and retrieval processes.
- **FAISS**: Optimized for efficient vector similarity searches.
- **Google Generative AI Embeddings**: For creating high-quality embeddings of document contents.
- **Streamlit**: Provides an interactive UI for user questions and document embedding.

**Challenges & Future Improvements**:
- **Fine-tuning Retrieval**: Improving answer accuracy by adjusting embeddings and vector search.
- **UI/UX Enhancement**: Adding more user-friendly components and customization options.
- **Additional Document Formats**: Expanding beyond PDF to include other document types.
  
**Installation**:

**Install Dependencies**: Run the following command to install necessary libraries: pip install langchain langchain-google-genai langchain-community faiss-cpu PyPDF2 pypdf dotenv

**Set Up API Keys**: Ensure your GROQ_API_KEY and GOOGLE_API_KEY are stored in a .env file or directly in your environment variables:
- GROQ_API_KEY=your_groq_api_key
- GOOGLE_API_KEY=your_google_api_key

**Start the Application**: Run the Streamlit application using streamlit run app.py

**Usage**:
- **Upload Documents**: Place your PDF documents in the us_census directory or adjust the path in the code to point to your own directory.
- **Embedding Documents**: Click the "Documents Embedding" button to create vector embeddings of your documents for search and retrieval.
- **Ask Questions**: Enter a question in the provided text input to retrieve an answer based on document content.

**Credits**:
This project is inspired by the work of **Krish Naik** who provided an insightful tutorial that helped in developing this Q&A application.
