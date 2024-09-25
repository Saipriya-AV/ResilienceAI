# Resilience AI

Resilience AI is a comprehensive medical translator and assistant, designed to enhance patient care by providing contextual translations, personalized healthcare support, emotional well-being advice, and lab report analysis. The project leverages artificial intelligence and machine learning to create an interactive system for patients and caregivers, offering real-time medical assistance in a user-friendly web application.

## Introduction

In complex medical environments like cancer care, patients and caregivers often struggle with understanding medical terminologies, diagnostic workups, and treatment options. **Resilience AI** addresses these challenges with an AI-driven system tailored to provide translation, guidance, and emotional support, primarily focused on oncology (e.g., breast cancer) patients and their caregivers.

This AI-based platform integrates multiple modules to provide real-time assistance, with features like medical translation, patient-specific healthcare guidance, and lab report analysis, all presented in a web-based interface powered by [Streamlit](https://streamlit.io/).

## Features

### Medical Translator
The **Medical Translator** allows users to translate text between multiple languages while providing detailed explanations for medical terminology, helping patients and caregivers understand complex terms.

- **Input:** Text (typed) or voice (recorded) input.
- **Output:** Translated text with explanations and audio playback.

**Workflow:**
1. User selects input method (text or voice).
2. Enter or record the text to be translated.
3. Choose source and target languages.
4. Translate, receive the text with explanations, and listen to the audio output.



### HealthBuddy
**HealthBuddy** is an intelligent assistant designed to answer patient queries related to medical conditions, treatments, and prescriptions. It processes medical documents (PDFs), extracts data, and creates a searchable knowledge base for accurate, contextual responses.

- **Input:** PDF files (e.g., medical reports, prescriptions) and text queries.
- **Output:** Contextualized responses generated from the document's content.

**Workflow:**
1. Upload a PDF document (e.g., medical report).
2. Enter a query regarding medications or treatment.
3. The AI searches the document and provides a relevant response.



### Emotional Support Bot
The **Emotional Support Bot** provides users with mental health guidance by processing PDFs related to emotional well-being and stress management. It generates empathetic and personalized responses to help users manage emotional challenges.

- **Input:** PDFs on emotional health, user queries related to mental well-being.
- **Output:** Emotional health tips, mental health strategies, and supportive responses.

**Workflow:**
1. Upload emotional well-being documents.
2. Ask questions related to stress or emotional health.
3. Receive supportive responses from the AI assistant.


### Lab Report Analyser
The **Lab Report Analyser** helps users understand their medical lab reports. By uploading reports (in PDF), users can receive detailed explanations of lab results, normal ranges, and potential health implications.

- **Input:** Lab report PDFs and user queries about the results.
- **Output:** Explanations about lab results and their significance.

**Workflow:**
1. Upload a lab report.
2. Ask specific questions about the results.
3. Receive detailed explanations in layman's terms.



### Medication Analyser
The **Medication Analyser** provides detailed information about medications based on prescription documents. Users can query the AI to get information on dosage, side effects, interactions, and necessary precautions.

- **Input:** Prescription PDFs and medication-related queries.
- **Output:** Medication details, including dosage instructions, side effects, and interactions.

**Workflow:**
1. Upload a prescription.
2. Enter queries about specific medications.
3. Get a comprehensive explanation regarding medication use and potential risks.



## Architecture

Resilience AI's architecture consists of multiple layers, combining data ingestion, natural language processing (NLP), machine learning, and a user-friendly interface.

- **Data Ingestion:** Input is taken in the form of text, speech, or PDF documents.
- **NLP Processing:** OpenAI’s GPT models handle translations, contextual responses, and personalized advice.
- **Searchable Vector Store:** Libraries like Faiss and SentenceTransformer process documents and create an efficient vector-based search mechanism for context retrieval.
- **User Interface:** Built using Streamlit, the application is simple to use, even for non-technical users.



## Tools and Libraries

Resilience AI utilizes several powerful tools and libraries to perform its tasks:
- **OpenAI GPT Models**: Provides the core of the translation and response generation capabilities.
- **Streamlit**: Used for creating the web interface.
- **Speech Recognition**: Converts voice input to text for translation.
- **gTTS**: Converts text to speech.
- **PyCountry**: Handles language codes for translations.
- **SentenceTransformer**: Used to create embeddings for similarity search.
- **Faiss**: Efficient similarity search and vector-based data processing.
- **PdfReader**: Extracts text from uploaded PDFs.
- **OS**: Handles file operations.
- **Tempfile**: Manages temporary files for audio storage.

## Usage

1. **Medical Translator:**
   - Select input type (text or voice).
   - Input the text to translate.
   - Choose source and target languages.
   - Click "Translate" to view the results and listen to the audio.

2. **HealthBuddy:**
   - Upload a PDF document containing medical information.
   - Enter a query related to the document.
   - Get a detailed response based on the document content.

3. **Emotional Support Bot:**
   - Upload emotional health-related PDFs.
   - Ask queries about emotional well-being or stress.
   - Receive practical and empathetic guidance.

4. **Lab Report Analyser:**
   - Upload a lab report PDF.
   - Ask about specific lab results.
   - Get a breakdown of the report's findings.

5. **Medication Analyser:**
   - Upload a prescription PDF.
   - Ask queries regarding medication.
   - Receive detailed information on dosage, side effects, and precautions.

This project was developed by:

- **Sayli Pankaj Bande**
- **Sakshi Archana**
- **Saipriya AV**
- **Sri Bharath Sharma P**

  
## License
This project is licensed under the MIT License.
