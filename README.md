# Chat_Math 

A Graduation Project focused on building an AI-powered mathematics chatbot using **Retrieval-Augmented Generation (RAG)** and **Llama 3.2 3B** with a simple and interactive **Streamlit** interface.

The system is designed to help users solve mathematical problems, retrieve relevant information, and generate intelligent responses using modern NLP and AI technologies.

---


#  Features

- AI-powered mathematics question solving
- Retrieval-Augmented Generation (RAG) pipeline
- Powered by **Llama 3.2 3B**
- Interactive Streamlit web interface
- Mathematical text processing
- LaTeX support for equations
- Saved and reusable trained models
- Modular and scalable architecture

---

#  Technologies Used

- Python
- Streamlit
- Llama 3.2 3B
- NLP (Natural Language Processing)
- RAG Architecture
- LaTeX
- Pickle / Binary Models

---

#  Project Structure

```bash
Chat_Math/
│
├── .streamlit/             # Streamlit configuration files
├── __pycache__/            # Python cache files
├── model/                  # Saved models
├── preprocessing/          # Text preprocessing modules
├── rag/                    # Retrieval-Augmented Generation pipeline
│
├── Checker.py              # Answer checking module
├── Latex.py                # LaTeX processing utilities
├── Latex_to_pdf.py         # Convert LaTeX files to PDF
├── Math_Model.bin          # Trained model
├── app.py                  # Main Streamlit application
├── trained.py              # Model training script
├── translate.py            # Translation utilities
│
└── README.md
```

---

#  Installation

Clone the repository:

```bash
git clone https://github.com/MohamedMohy0/Chat_Math.git
```

Move to the project directory:

```bash
cd Chat_Math
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

#  Run the Application

Start the Streamlit application:

```bash
streamlit run app.py
```

---

#  About the Project

This graduation project aims to develop an intelligent educational assistant capable of solving and explaining mathematical problems using modern AI techniques.

The project combines:

- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- NLP techniques
- Mathematical text understanding

to create an efficient and user-friendly mathematics chatbot.






#  Future Improvements

- Improve mathematical reasoning accuracy
- Add voice input support
- Support more mathematical domains
- Deploy the application online
- Enhance UI/UX design
- Add multilingual support





