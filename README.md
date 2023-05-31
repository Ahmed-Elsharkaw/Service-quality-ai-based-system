# Service-quality-ai-based-system

##############################################
1mo • Edited •

The graduation project is one of the strongest projects I have worked on, which I am now using to publish in paper
This project is powerful because it gave me many experiences and made me more familiar with transformers, as it was divided into three very important parts:

(1) sentiment analysis
(2)topic classification
(3)recommended action

The project begins with the fact that the Egyptian citizen enters any organization and is exposed to a bad situation, so he wants to convey this complaint to the competent authorities.
Here we have created a site that takes complaints, and here we start the stages of the project, which is to take written words in colloquial Egyptian Arabic.
here the process of searching for the appropriate data for this project began, and we found it very difficult to find the appropriate data, so we did the process of web scraping with some other data that needed terrible work in preprocessing, in order to train the different models in the different stages to work the required purpose.
The text begins to enter the first stage, which is to identify the competent authority, and this was done using transformers, and in order to be accurate, we started to finetune the model (“UBC-NLP / MARBERT”) and made many experiments to improve the results, and here we start entering the second stage, which is (sentiment analysis) What is the feeling The citizen is from this organization, and we used the same model, but with the difference in the required consistency and the difference in the data, and here we move to the most difficult and important part, which is to solve the problem through the site in order to reduce the burden on the employee, and that is through training the model on problems and solving them, and that through data that contains 100,000,000 rows, and here the confusion began Is this a generating task, a Question Answer, a chatbot, or any? Here we started the experiments that are continuing to improve and now we are working in parallel on different models such as (“UBC-NLP/AraT5-tweet-base”) and also (“aubmindlab/aragpt2-large”) and also ("google/MT5")And we started the process of finetune, and it is possible to work on the process of transfare learning, by pumping much data is too big to help me convert to solve this problem
Here is the purpose of the project, which is to assist the citizen in finding solutions to his problems, as well as to reduce the work on the employee, and that is because he reaches him only the problems that are new of their kind, and thus we are starting to improve the organizations and move the country forward
MT5.PNG
