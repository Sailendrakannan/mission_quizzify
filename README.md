AI_QUIZZIFY

Overview : Quizzify is an AI-powered quiz generation tool designed to enhance the learning experience by dynamically creating quizzes from user-provided documents. This project aims to provide an accessible and effective means for students and learners to reinforce their understanding of various topics. By leveraging AI technology, Mission Quizzify offers instant feedback and detailed explanations, facilitating deeper comprehension and retention of knowledge.

Establish a project, activate the Vertex AI APIs, and administer the service account with owner permissions using Google Cloud Platform first. To use all required APIs, authenticate using the service account key (authentication.json) and configure using the project name. (Authentication SDK).

Install each and every package (streamlit, chromadb, langchain, langchain-google-vertexai, pypdf) from requirements.txt.

Tasks three through ten include the implementation of the full project. The repository contains the Python files containing the documentation and corresponding outputs.

Managing files with streamlit is the main emphasis of Task 3 - Document Ingestion. Using PyPDFLoader from the Langchain framework to process PDF files after uploading them. manages several PDF files.

Task 4: In this task, VertexAI and Langchain embeddings are initialized, and "Hello World" is input to test the embeddings.

Establishing a Data Pipeline with Chroma Database is Task 5. Processing of the document, including text segmentation and memory-based Chroma collection building.

Task 6 is the development of a clean user interface for data intake and AI-integrated quiz generation. uses Chroma collection to generate quiz questions.

Task 7: Using Google's "gemini-pro" paradigm, increase the inventiveness of the quiz questions. In order to obtain context-driven generation, configure the settings for controlled outputs and integrate with the vectorstore from the earlier jobs.

Creating the quiz algorithm is Task 8.

Create the quiz user interface (Task 9). enabling smooth transitions between the questions and using streamlighting to display the questions.

Session State Handling is Task 10. Simple navigation and setup for the quiz. Set the topic (as a prompt), the number of questions, and the initialization of the question bank using Streamlight widgets. You may also manage the quiz's creation and presentation. Lastly, using the program to test.

