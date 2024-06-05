# **Gemini Quiz Creator**

This program creates a quiz with generative AI using PDF files that the user provides. 


![Running Sample](https://github.com/dc90x/gemini-quiz-creator/assets/130667325/1d0f2815-2c89-42c1-9f07-08d1a7706f9d)






## **How It’s Made:**
Tech stack: ChromaDB, Streamlit, Google Gemini, Langchain

### Problem Statement: 
Test taking is an integral part of the learning process. It shows us how well we know the material. It also identifies areas where we can improve. At this point we would look into exercises/quizzes that focus on these problem areas. For more broad topics, this may be an easy task. For more specialized disciplines, it may be tough to find the right quizzes to meet our specific needs. This program offers a dynamic way of making quizzes that meet the needs of the user. 


### Program Overview:
-Loads the data (PDF files) provided by the user using document loaders

-Splits the documents into more manageable sections using text splitters

-Indexes the chunks and stores them using a vector store and embeddings model

-Generates an interface with which to interact with the user using streamlit

-Takes user input for quiz creation in the form of: PDF files, topic for the generated quiz, number of questions

-Uses LLMs/chat models and question template to output the results in the form of a quiz using streamlit for the user interface





## **Lessons Learned:**

> _“I’ve failed over and over and over again in my life. And that is why I succeed.”_
- Michael Jordan

This undertaking makes use of various different technologies working in unison to create a dynamic experience. As such, there are many possible points of failure. For someone who has always been a perfectionist, It was an opportunity to learn to readjust my expectations and reevaluate how I look at failure throughout the development process.






## **Acknowledgements:**

Mikhailocampo (https://github.com/radicalxdev) on github for the code template (https://github.com/radicalxdev/mission-quizify)

Mikhailocampo and Radical AI (https://ai.radicalai.app/) for guidance throughout program completion.

