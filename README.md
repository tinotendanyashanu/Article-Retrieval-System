# Article-Retrieval-System

## Project Overview

Hello! I'm excited to share the Article Retrieval System, a tool designed to leverage cutting-edge machine learning technologies to enhance our understanding of content from a vast array of articles. This system intelligently retrieves and generates insightful answers to user queries, combining the power of the transformers library and FAISS for efficient similarity searching.

## Installation

To get started with the Article Retrieval System on your local machine, follow these steps:

# Clone the repository to your local workspace

git clone https://github.com/tinotendanyashanu/Article-Retrieval-System.git
cd Article-Retrieval-System

# Install the necessary dependencies

pip install -r requirements.txt

## Configuration

Set up a couple of environment variables before you start querying. These variables ensure the system knows where to find the pre-trained models and index files:

```sh
export FAISS_INDEX='index.faiss'
export TRANSFORMERS_CACHE='./transformer_cache'
```

## Running the Code

Ready to explore the capabilities of the Article Retrieval System? Here’s how to start:

```sh
# Launch the application
python src/retivalsystemNotebook.ipynb

# Follow the on-screen prompts to enter your query
Enter your query: What are the latest trends in artificial intelligence?
```

The system will deliver responses generated from relevant articles in the dataset, providing a comprehensive and insightful answer.