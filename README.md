1. Named Entity Recognition:

Named Entity Recognition (NER) is a natural language processing (NLP) technique that aims to identify and classify named entities in a text into predefined categories, such as names of individuals, locations, organisations, times, amounts, monetary values, percentages, and so on. Finding entities and their kinds is NER's primary goal when trying to extract structured data from unstructured text. This task is crucial for many NLP applications, such as response systems, information retrieval, and document summarization. The typical processes in NER entail tokenizing the input text into words or phrases and then classifying each token into predefined entity categories. Numerous deep learning and machine learning techniques are utilised for NER, including statistical models like Conditional Random Fields, neural network-based models like Bidirectional LSTMs, and rule-based techniques.

Python code to recognize the name entities in a document:

Named Entity Recognition (NER) is carried out on an input text document by this Python script. A text file with 200–300 words is the input. The identified named entities and their labels are sent to an output file by the script, which makes use of the spaCy library for NER. Make sure to obtain and install the English language model "en_core_web_sm" using pip install spacy and python -m spacy download en_core_web_sm. The input and output file paths were supplied in the code in order to use this script. Additionally, we have submitted the text files for the input and output to this repository.


2. Zachary's karate club network, available through NetworkX as karate.gml, examines fission and group conflicts. It consists of 34 nodes, which stand for club members, and edges, which indicate contacts outside of club events.

Using the graph analysis tool NetworkX, this Python script examines Zachary's karate club network from the "karate.gml" file. It carries out the following duties:

i. Constructs a graph using the "karate.gml" file, which shows the network's fundamental data.

ii. Preserves actor metadata inside the network.

iii. Determines the centrality values for a number of variables, including degree, betweenness, proximity, eigenvector, and pagerank centrality. Based on these values, an analysis is provided.

iv. Determines the network's potential k-components and calculates the clustering coefficient.

v. Uses the Louvain method and Girvan-Newman algorithm to identify communities.

After downloading and installing NetworkX (pip install networkx), make sure the "karate.gml" file is in the repository and update the file path appropriately.














