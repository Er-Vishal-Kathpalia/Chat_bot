# Reply Bot
Smart reply bot implemented in Python for the simulation of project of Artificial Intelligence.
# What Does It Do?
A chatbot is an intelligent piece of software that is capable of communicating and performing actions similar to a human. Chatbots are used a lot in customer interaction, marketing on social network sites and instantly messaging the client. There are two basic types of chatbot models based on how they are built; Retrieval based and Generative based models.
From a high-level, there are two variants of chatbots, **rule-based** and **self-learning**:
* A **rule-based** bot responds via pattern matching and rules.
* A **self-learning** bot responds via using machine learning.
    * A **retrieval-based** chatbot replies by locating the best response from a database (corpus).
    * A **generative-based** chatbot use deep learning methods to respond and can generate a response it has never seen before.
    
In order to understand the tradeoffs between the different types of chatbots, I implemented a retrieval-based that takes the best response from a database.
## Built With

* Python
* [NLTK](https://www.nltk.org/)
* TensorFlow and TFLearn
* Pickle
* keras model
* Tkinter
## Usage

Execute the program
Firstly train the program by running file named as train_chatbot.py

``` 
python train_chatbot.py
```
It will reply you model created successfully. After this you can run second python file named as chatgui.py

```
python chatgui.py
```
A Gui will be open on your desktop screen and you can start the conversation with the bot.

```
Hii, hello, How can you help me etc.
```

To quit, just say thanks to the bot and close the Gui window.

## Thoughts

It's obvious that no one type of reply bot works best. A retrieval-based bot performs poorly for casual conversation and works better for factual queries. 
For casual conversation, a hybrid implementation (rule-based and machine-learning based) may work best.

## Author

**Vishal Kathpalia** 

## Acknowledgments

1. https://chatbotsmagazine.com/contextual-chat-bots-with-tensorflow-4391749d0077
2. https://in.pycon.org/cfp/2019/proposals/how-we-are-building-smart-reply-for-chat~eZMvd/


