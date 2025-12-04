# NLP-Sentiment-Analysis-of-fan-reactions-for-the-World-Cup-2022---with-RAG-and-UI
 The goal of the project is to apply NLP techniques, analyze various trends and to get insights in order to see the fans' expressions, emotions, sentiment analysis and in general how the anticipation for the competition was. So the project is divided into several parts, such as the preprocessing techniques that applied, the supervised and unsupervised learning parts including the EDA , the implementation of RAG and the User Interface.



 1. Data Collection & Preprocessing

Tweets related to World Cup teams, players, and events are cleaned and normalized.
This includes:

Removing URLs, emojis, and user mentions

Lowercasing and tokenization

Stopword removal

Lemmatization or stemming

Hashtag and emoji sentiment handling
These steps prepare the text for reliable analysis.

🔹 2. Sentiment Analysis

The cleaned tweets are analyzed using a sentiment classifier to determine whether reactions are:

Positive

Negative

Neutral

The model is applied to the full dataset to understand general fan mood and reaction patterns throughout the tournament.

🔹 3. Retrieval-Augmented Generation (RAG)

To enrich the experience, the project includes a RAG system that allows users to ask questions about:

Fan opinions

Trends in reactions

Sentiment toward teams or players

Specific match events

The RAG pipeline retrieves relevant tweets or summaries and then uses an LLM to produce context-aware answers.

🔹 4. Interactive UI

A lightweight UI lets users:

Enter prompts

See retrieved context

Visualize sentiment patterns

Explore example tweets and insights

Interact with the RAG system in real time

It turns the project into an intuitive tool rather than just a script.

🔹 5. Insights & Interpretation

The system provides:

Sentiment distribution plots

Trend insights before/after key matches

Context-aware generated explanations via RAG

A combined view of raw data + AI reasoning
