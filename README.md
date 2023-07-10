## Self Learning Chatbot using Python and NLTK
- A chatbot is a computer program designed to simulate conversation with human users, especially over the internet.
- A **self-learning chatbot**, also known as an AI or intelligent chatbot, is a type that uses machine learning algorithms to enhance its performance over time continuously. This indicates that the chatbot can acquire knowledge from user interactions and modify its responses accordingly.
- Why are chatbots important? <br>
 Organizations looking to increase sales or service productivity may adopt chatbots for time savings and efficiency, as artificial intelligence (AI) chatbots can converse with users and answer recurring questions. <br>
 As consumers move away from traditional forms of communication, many experts expect chat-based communication methods to rise. Organizations increasingly use chatbot-based virtual assistants to handle simple tasks, allowing human agents to focus on other responsibilities.
## Natural Language Tool Kit (NLTK) 
- NLTK is a leading platform for building Python programs to work with human language data. It provides easy to use interfaces to over 50 corpora and lexical resources such as WordNet, along with a suite of text processing libraries for classification, tokenization, stemming, tagging, parsing, and semantic reasoning, wrappers for industrial-strength NLP libraries, and an active discussion forum.
## Steps invovled in building chatbot
- **Importing libraries** <br>
 Necessary libraries are imported for model like numpy, nltk, string, random
 
- **Reading text corpus** <br>
  A corpus is the most critical and basic building block of any NLP related application. It provides us with quantitative data that is used to build NLP applications.<br>
  In this model, data.txt file is read in which text is store from which Chatbot will learn and give responses to user.
  
- **Tokenization, Stemming, Lemmatization** <br>

  **Tokenization** : Raw text data is converted into numerical form with the help of tokenization. <br>
  **Stemming** : Stemming is the process of finding similarities between words with the same root words. <br>
  **Lemmatization** : Lemmatization refers to returning the base word. <br>
  All these steps are performed on data.
  
- **Preprocessing (Stopwords, Removal, Lower case conversion etc)** <br>

**Stopwords** : Stop words are a set of commonly used words in any language. For example, in English, “the”, “is” and “and”, would easily qualify as stop words. In NLP and text mining applications, stop words are used to eliminate unimportant words, allowing applications to focus on the important words instead. <br>

**Removal** : Stop words removal is the data pre-processing step in the natural language processing (NLP) pipeline in which we remove all the highly frequent words from the text as it does not add any valuable information to understand the text better resulting in the NLP model dealing with less number of features. <br>

**Lower case conversion** : It is one of the most common text preprocessing Python steps where the text is converted into the same case preferably lower case. 

  
- **Defining greeting functions**
  
- **Response Generation by the Bot using TfidfVectorizer and cosine similarity** <br>

  **TfidfVectorizer** : It counts the number of times a word appears in a document (using a bag-of-words approach), it also takes into account not only how many times a word        appears in a document and also how important that word is to the whole corpus. <br>
  **Bag Of Words** : It turns arbitrary text into fixed-length vectors by counting how many times each word appears.
  **Cosine similarity** : It measures the similarity between two vectors of an inner product space. It determines whether two vectors are pointing in the same direction by         measuring the cosine of the angle between them. In text analysis, it is used to determine document similarity.
  
- **Defining the Chat Flow**
- **Chatbot Conversation** 
