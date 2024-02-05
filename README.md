## Language Detection NLP
In this project, my main goal was to figure out the language of a given piece of text using NLP
Data Cleaning:
I kicked off the project by cleaning up the dataset. I wanted the computer to understand text better, so I removed unnecessary symbols and punctuation marks. To ensure consistency, I also converted all the letters to lowercase.

NLP Pipeline Construction:
Next, I set up a sophisticated system using Natural Language Processing (NLP). Imagine teaching the computer to recognize and categorize different languages. I used a powerful tool called TfidfVectorizer, which transformed the text into a numerical format that the computer could easily interpret. Then, I employed a Logistic Regression model to train the system to accurately identify languages.

Training and Accuracy:
The system underwent training with the pre-processed dataset, and the results were impressive. It achieved an accuracy rate of approximately 98%, meaning it could correctly identify the language most of the time. This high accuracy level indicated the effectiveness of the chosen NLP methods and the robustness of the system.

Confusion Matrix Analysis:
To gain a deeper understanding of the system's performance, I visualized a confusion matrix. This matrix provided insights into how well the system differentiated between the actual and predicted outcomes. It was a crucial step in evaluating and refining the model.

Model Persistence and Deployment:
To ensure the long-term usability of the trained model, I used the pickle library. This allowed me to save the model as a file using the pickle.dump() function. Now, the model is ready for deployment in various applications, making it versatile and accessible.

#Lesson Learn
This language detection project showcases not only technical skills in NLP and machine learning but also a methodical approach to data processing and model evaluation. The high accuracy achieved underscores a commitment to delivering reliable and effective solutions in the realm of Natural Language Processing.
