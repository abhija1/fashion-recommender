# Visual Fashion Search System

A content-based fashion recommendation system built using Deep Learning and Computer Vision. The application recommends visually similar fashion products based on an uploaded image.

## Features

- Upload a fashion product image
- Extract image features using ResNet50
- Find visually similar products using K-Nearest Neighbors (KNN)
- Display top recommendations instantly
- Interactive web interface built with Streamlit

## Tech Stack

- Python
- Streamlit
- TensorFlow / Keras
- ResNet50
- Scikit-learn
- NumPy
- Pillow

## Project Structure

```text
fashion-recommender/
│
├── app.py
├── main.py
├── test.py
├── README.md
├── requirements.txt
│
├── images/           # Dataset (ignored from GitHub)
├── uploads/          # Uploaded images (ignored)
│
├── embeddings.pkl    # Feature vectors (ignored)
└── filenames.pkl     # Image paths (ignored)
```

## How It Works

1. User uploads an image.
2. ResNet50 extracts deep image features.
3. Feature vector is normalized.
4. KNN finds the most similar products.
5. Recommended products are displayed.

## Installation

Clone the repository:

```bash
git clone https://github.com/abhija1/fashion-recommender.git
cd fashion-recommender
```

Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run main.py
```

## Future Improvements

- Hybrid recommendation system
- User preferences and personalization
- Deployment on Streamlit Cloud
- Faster similarity search using FAISS

## Author

Abhijai Dagar
B.Tech Mathematics & Computing, DTU
