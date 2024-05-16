
# Python Script for AI-driven Data Retrieval and Analysis

## Description

This Python script leverages advanced AI techniques to facilitate data retrieval and analysis from a CSV dataset. It utilizes OpenAI's language models for generating embeddings and responses, Pinecone's services for vector storage and retrieval, and Gradio to create a user-friendly web interface. The script is equipped with functionalities for data loading, text processing, embedding generation, efficient searching, and interactive querying.

## Key Features

- **Data Loading**: Imports data from a CSV file for processing.
- **Text Processing and Embedding**: Utilizes OpenAI's models to create text embeddings.
- **Vector Storage and Retrieval**: Implements Pinecone for indexing and retrieving text embeddings.
- **Interactive Query Interface**: Uses Gradio for a web-based interface that allows users to enter queries and receive answers.
- **Data Visualization**: Provides PCA-based 2D visualization of query results and their nearest neighbors.

## Installation

Before running the script, you must install the required Python packages. Run the following command in your terminal:

```bash
pip install --upgrade --quiet langchain langchain-community langchain-openai langchain-pinecone gradio openai pinecone bs4 sklearn plotly
```

### Set Up Environment Variables

Configure the necessary API keys for Pinecone and OpenAI:

```bash
export PINECONE_API_KEY='your-pinecone-api-key'
export OPENAI_API_KEY='your-openai-api-key'
```

## Usage

To use this script, follow these steps:

1. **Prepare Your Data**: Ensure your CSV data file is in the expected format and located at a specified path.
2. **Run the Script**: Execute all cells in jupyter notebook
3. **Interact via Gradio**: Open the provided local URL in a web browser to access the Gradio interface.
4. **Enter Queries**: Use the interface to type queries and view the system's responses and source indices.

## Example Queries

- "What should be done if the tumor diameter is 2.5 cm?"
- "Details on treatment methods for specific conditions?"

## Visualization

This script also features a Plotly visualization of the query context and its closest data points in a 2-dimensional space, illustrating how the PCA has reduced the dimensionality for a clear, concise view.

## Contributing

Feel free to fork this project and contribute by submitting pull requests to enhance the functionalities.




