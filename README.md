# BOOCHI-RAG-App-with-Pathway-
Boochi is a cutting-edge application that leverages RAG technology to provide accurate, context-aware answers using up-to-date data. Powered by Pathway, Boochi efficiently ingests and indexes dynamic datasets, enabling seamless interaction with large language models (LLMs).
# -BOOCHI-Real-Time-Retrieval-Augmented-Generation-RAG-App-with-Pathway-
Boochi is a cutting-edge application that leverages  RAG technology to provide accurate, context-aware answers using up-to-date data. Powered by Pathway, Boochi efficiently ingests and indexes dynamic datasets, enabling seamless interaction with large language models (LLMs). 

![logo](****)




## Overview
**Boochi** is a state-of-the-art application that revolutionizes generative AI by enabling real-time, contextually updated answers. Built on **Pathway**, the world's fastest data processing engine, Boochi offers seamless integration with dynamic data sources, ensuring accurate and up-to-date responses. 

This repository provides the complete source code, setup instructions, and deployment guidelines for Boochi.

---

## Features
- **Real-Time Data Ingestion:** Connects to live data sources like Google Drive and SharePoint.
- **Advanced Indexing:** Uses vector and semantic indexing for efficient document retrieval.
- **RAG Pipeline:** Combines retrieved context with LLMs to generate precise answers.
- **REST API Deployment:** Exposes the pipeline via a REST endpoint for integration.
- **Interactive UI:** A user-friendly interface for querying and observing updates.

---

## Architecture

![ARCH]


### Key Components:
1. **Data Ingestion Layer:**
   - Fetches unstructured documents from sources like Google Drive, SharePoint, or PDFs.
2. **Indexing Pipeline:**
   - Extracts data using GPT-4o for table analysis and text parsing.
   - Stores parsed documents in a hybrid data index (vector + semantic).
3. **RAG Pipeline:**
   - Retrieves relevant documents and generates context-aware answers using GPT-4o.
4. **Deployment Layer:**
   - REST API endpoint for querying (`/question_answer`) and optional UI for interaction.

---

## Technologies Used
- **Pathway:** Real-time data processing framework.
- **Python:** Core programming language.
- **Vector DB:** FAISS or ChromaDB for indexing.
- **LangChain:** For RAG pipeline orchestration.
- **REST API:** Endpoint deployment.

---

## Installation

### Prerequisites
1. Python 3.8 or higher installed.
2. Docker installed for containerized deployment.
3. Access to Pathway SDK (refer to [Pathway documentation](https://pathway.com/docs)).

### Steps
1. Clone this repository:
git clone https://github.com/username/boochi.git
cd boochi

text
2. Install dependencies:
pip install -r requirements.txt

text
3. Set up environment variables:
- Create a `.env` file with your API keys and configurations.
4. Run the application:
python app.py

text

---

## Usage

### REST API Endpoint
The application exposes a REST API at `/question_answer`. You can send queries via POST requests:
{
"query": "Your question here"
}

text
The response will include contextually accurate answers based on real-time indexed data.

### User Interface (Optional)
A simple web UI is available for testing queries interactively. Run the UI server:
python ui_server.py

text
Access the interface at `http://localhost:5000`.

---

## Contribution Guidelines
We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
git checkout -b feature-name

text
3. Commit your changes and submit a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact Information
For questions or support, please reach out to:
- Email:rdvprasad36@gmail.com
- phone number: 738612327

---
