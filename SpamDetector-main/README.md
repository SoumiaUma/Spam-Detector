# CSCI 2020U - Assignment 1

Group Members: Maxwell McLaughlin and Soumia Umaputhiran 

Project Information

The purpose of this project is to create a spam detector that will train itself using some spam and not spam (ham) emails. The spam detector uses a dataset of E-Mails (spam or otherwise) to train the program to recognize whether or not new E-Mails are spam. The program will use a unigram approach, where each word is counted and associated with whether or not the message is spam. Our program calculates probabilities based on each word’s frequency. The accuracy and the precision of the spam detector are the statistics used in this project to determine the effectiveness of the spam detector. The Naive Bayes spam filtering and Bag-of-words model was used for training the spam detector.


This is a screenshot of the running application


<img width="499" alt="a3" src="https://user-images.githubusercontent.com/60481370/110410254-97f6aa80-8056-11eb-8afd-20748070413e.png">



How to run: Step-by-Step
1. Click on the green button that says "Code" which is located on the top right corner of the screen.
2. Copy the HTTPS url.
3. Choose a location you want to store your project.
4. Instiate git repository by typing _git init_
5. Then on your terminal type _git remote add origin "url"_
6. Then type _git fetch origin main_
7. This should clone the project onto your local repository 
8. Open IntelliJ or any other Java supported IDE.
Instructions for Intelli J:
- Go to _File/Open_
- Choose the _Assignment1_ folder that you cloned onto your computer.
- Go to Main.java which is located in _src/csci2040u.assignment1_
- Click on the little green hammar on the top right of the screen.
- Click on the little green play button to run the program
Now you will see the JavaFX application!


References

[1] https://docs.oracle.com/javafx/2/ui_controls/jfxpub-ui_controls.htm

[2] https://en.wikipedia.org/wiki/Bayesian_probability

[3] https://mkyong.com/java/java-files-walk-examples/
