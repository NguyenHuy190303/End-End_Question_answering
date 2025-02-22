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
0. Clone project    
```
    git clone https://github.com/NguyenHuy190303/End-End_Question_answering

```
1. Install package    
```
    pip install -r requirements.txt

```

2. Open the notebooks in Jupyter:
```sh
    jupyter notebook
```

## Usage

### DistilBERT Notebook

The [Distillbert.ipynb](http://_vscodecontentref_/1) notebook demonstrates how to use the `distilbert-base-uncased` model. Key parameters include:

- `MODEL_NAME`: The name of the model checkpoint.
- `MAX_LENGTH`: The maximum length for each text segment after processing.
- `STRIDE`: The stride between the start points of consecutive text segments.

### FAISS Search Notebook

The `Faiss_search.ipynb` notebook contains code for performing FAISS search. Follow the instructions within the notebook to understand how to use FAISS for efficient similarity search.

### EQA Pre/Post-Processing Notebook

The `note_pre_post_processing_eqa.ipynb` notebook includes steps for pre-processing and post-processing data for EQA tasks. Refer to the notebook for detailed instructions.

## License

This project is licensed under the MIT License. See the LICENSE file for details.