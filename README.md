# Text-Graph-Constructor
A tool that constructs a graph given text in a natural language as input, such that a node represents a sentence, and an edge exists from one sentence (node) to another if text similarity between the two is above a user-defined threshold.

# Description:
Text Graph Constructor is a Python-based tool that constructs a graph representation from text input. The tool analyzes the natural language text and generates a graph where each node represents a sentence. Edges exist between sentences that exhibit text similarity above a user-defined threshold. By visualizing the relationships between sentences in a graph, users can gain insights into the semantic structure and connections within the text.

# Tools Used:
1. Natural Language Toolkit (NLTK): NLTK is a powerful library for natural language processing tasks. It is used for sentence tokenization, stopwords removal, and word tokenization in this project.

2. Transformers: The Transformers library provides a wide range of pre-trained transformer models, including DistilBERT. It is utilized in this project for sentence similarity calculations and for generating contextualized word embeddings.

3. NetworkX: NetworkX is a Python library used for creating, manipulating, and analyzing complex networks or graphs. It is employed to construct and represent the graph structure in this project.

4. Matplotlib: Matplotlib is a popular plotting library in Python. It is used to visualize the constructed graph in a graphical form, enabling users to understand the relationships between sentences more intuitively.

# Python Notebook:
Text Graph Constructor.ipynb
