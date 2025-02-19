![1](docs/logo-transparent.png)
An application to help teachers to generates quiz based on article

> 🏆🏅🏆 Winner of Starton 2021 “AI: Code Up the Future” 🏆🏅🏆

### 💡 About the App
As an elementary teacher for over 30 years in Indonesia, Lucy face changes in methods of teaching a lot of time in her life. COVID-19 changes how school operates, by putting an end to face-to-face teaching, in favor of online teaching. New challenges arise; forcing teachers to be tech-savvy by operating online class tools, and change their methods of teaching online.

Students were not too enthusiastic about the online learning experience, since there were no interactions during class. Teachers only read out their presentation, and the lack of physical presence blocks us from interacting as we used to in class. Lucy tried methods like live-online quiz game in class using Kahoot to solve this. Students liked it alot, but having to create new quizzes every meeting puts extra effort for Lucy.

So, we created Riddlr; an app that create Kahoot quizzes from your textbook article. Using OCR and question-answering AI, created using BERT (Bidirectional Encoder Representations from Transformer), T5 (Text-to-Text Transfer Transformer) trained with SQuAD (Stanford Question Answering Dataset) and WordNet, user can scan their textbook with their phone, and let our app transform it into a spreadsheet, filled with questions and multiple-choice answer (MCA) based that article, and can be imported to Kahoot to be played during online class


### 👀 Preview

###### Home and Navigation
![Home and Navigation View](docs/1.png)
When using the app, user can navigate through all of the quizzes they have created. User can search their quizzes by using the search bar and filter by its designated categories. User can click the quiz, and will be able to see the questions, answers and other options, generated by our app. User can delete and edit existing questions from this page. User can see the article that is used as the reference for the questions generated. Finally, user can download the spreadsheet generated from the questions, and can be imported to Kahoot to be played during class.

###### Generating New Quiz
![Generating New Quiz View](docs/2.png)
When user clicked the create new quiz button on the bottom right of the home page, user is prompted to take a picture or upload existing image on their gallery. Pick an image of the article you'd like to scan. Once picked, Riddlr will use OCR to translate the image into a text, which can be edited by the user manually, in case the OCR misspelled the text. Once verified, the app will pass the text to our AI model, based on BERT, T5 trained with SQuAD, and WordNet, to create a set of questions, answers and options to be in the multiple choice quiz. User can manually edit the result, if neceessary. Once done, user can save the quiz, and can be accessed in Riddlr home page.


### 👨🏻‍💻 Tech Stack
Riddlr is built with Flutter as a mobile app. Its backend is created using Jupyter Notebook, and its database uses Firebase. For more details, you can see the diagram below;
![Tech Stack](docs/3.png)

### 📚 Pitch Deck
Fancy reading the pitch deck used in our demo day? You can check them [here](https://github.com/vincentandreas/start_on_2021_competition/raw/master/docs/Riddlr%20Pitch%20Deck.pdf).





