# **End-to-End Question Answering (EQA) Project**  

📌 **Overview**  
This project contains Jupyter notebooks that leverage **DistilBERT**, **FAISS**, and various **pre-processing & post-processing** techniques to build an End-to-End Question Answering (EQA) system.

---

## 🚀 **Project Contents**  

The project includes the following key notebooks:  

- 📌 **[`Distillbert.ipynb`](./Distillbert.ipynb)**  
  - Demonstrates how to use the **`distilbert-base-uncased`** model for text processing.  
  - **Key parameters:**  
    - `MODEL_NAME`: The model checkpoint used.  
    - `MAX_LENGTH`: The maximum length of processed text segments.  
    - `STRIDE`: The step size between consecutive text segments.  

- 🔍 **[`Faiss_search.ipynb`](./Faiss_search.ipynb)**  
  - Contains code for performing **FAISS-based similarity search**.  
  - Helps with **efficient vector indexing and retrieval**.  

- ⚙️ **[`note_pre_post_processing_eqa.ipynb`](./note_pre_post_processing_eqa.ipynb)**  
  - Includes **pre-processing and post-processing steps** for EQA tasks.  

- 📝 **[`notes.txt`](./notes.txt)**  
  - Additional notes related to **model configurations and processing techniques**.  

---

## 📌 **Setup Instructions**  

To set up the environment and run the notebooks, follow these steps:  

### 1️⃣ **Install Dependencies**  
Run the following command to install required Python packages:  
1. Install package    
    ```sh
pip install -r requirements.txt

    ```

2. Open the notebooks in Jupyter:
    ```sh
    jupyter notebook
    ```


