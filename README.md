# Face Recognition System

This project implements a face recognition pipeline in Python that detects faces, extracts embeddings using the **face_recognition** module, and recognizes identities using a vector database (**Typesense**). It supports real-time or image-based recognition.

---

## Features

- Face detection using **face_recognition**  
- Face embedding extraction  
- Face recognition with **Typesense** vector search  
- Modular pipeline for detection, embedding, and recognition  

---

## Tech Stack

- **Python**  
- **face_recognition**  
- **OpenCV**  
- **Typesense** (vector database)  

---

## How It Works

1. Faces are detected in images or video using **face_recognition**.  
2. Embeddings are extracted for each face.  
3. Embeddings are stored in a **Typesense** vector collection.  
4. Recognition is performed by finding the closest match using vector similarity.  

---

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/your-username/Face_recognition.git
cd Face_recognition
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Set up **Typesense** and configure the connection.

4. Run the main script:

```bash
python main.py
```

---


## Applications

- Access control  
- Attendance systems  
- Identity verification  
- Surveillance and analytics
