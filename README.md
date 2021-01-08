# Fake-News-Detection
__What is Fake News?__<br>
A type of yellow journalism, fake news encapsulates pieces of news that may be hoaxes and is generally spread through social media and other online media. This is often done to further or impose certain ideas and is often achieved with political agendas. Such news items may contain false and/or exaggerated claims, and may end up being viralized by algorithms, and users may end up in a filter bubble.<br><br>

__What is a TfidfVectorizer?__<br>
TF (Term Frequency): The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms.<br><br>

__IDF (Inverse Document Frequency)__: Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.<br><br>

The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.<br><br>

__What is a PassiveAggressiveClassifier?__<br>
Passive Aggressive algorithms are online learning algorithms. Such an algorithm remains passive for a correct classification outcome, and turns aggressive in the event of a miscalculation, updating and adjusting. Unlike most other algorithms, it does not converge. Its purpose is to make updates that correct the loss, causing very little change in the norm of the weight vector.<br><br>
__Dataset used__: news.xlsb<br><br>
__Objective__<br>
To build a model to accurately classify a piece of news as REAL or FAKE.<br><br>
__Prerequisites__<br>
- Install Numpy<br>
- Install Pandas<br><br>


