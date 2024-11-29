# Top 50 Similar Document Pairs using TF-IDF and Cosine Similarity
Project Description
This project identifies the top 50 most similar document pairs out of 132 documents using TF-IDF (Term Frequency-Inverse Document Frequency) and Cosine Similarity. The implementation is done in Python and processes a set of documents stored in a folder. The project calculates similarity scores by:

Building TF-IDF vectors for each document.
Computing pairwise cosine similarity between these vectors.
Extracting the top 50 most similar document pairs.
Features
Document Preprocessing: Parses text files to extract terms for analysis.
TF-IDF Calculation: Assigns importance to terms based on their frequency in a document and across the dataset.
Cosine Similarity: Measures similarity between document vectors.
Efficient Pairwise Similarity: Calculates similarities for all document pairs and ranks them.
How It Works
Input: A folder containing 132 text files, each representing a document. Files must include:

<DOCNO>: Unique document identifier.
<TITLE>: Document title.
<TEXT>: Document content.
Steps:

Extract terms from documents.
Compute TF-IDF vectors for each document.
Calculate cosine similarity between all document pairs.
Rank and display the top 50 similar document pairs.
Output: The top 50 document pairs with the highest similarity scores are printed in the format:

Document1_ID --- Document2_ID --- Similarity_Percentage%
Requirements
Python 3.x
