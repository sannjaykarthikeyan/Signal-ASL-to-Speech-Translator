# Signal-ASL-to-Speech-Translator

**WORK IN PROGRESS:** Signal was created with legacy, outdated libraries and packages that aren't supported by the latest Tensorflow V2. As a result, certain OpenCV libraries such as contrib were rendered unusable. Signal is actively being rewritten and worked on as of May 2022 to fix compatibility issues. 

View a quick demo of Signal:
[youtu.be/txIMOdQXTC8](youtu.be/txIMOdQXTC8)

Signal is a real-time American Sign Language to Speech translation program. It uses a point-of-view camera system to detect and translate sign language phrases to computer generated speech in real time. Signal can support multiple sign langauge words, as well as combinations of words and phrases to create sentences. 

A detailed writeup of instructions and resources used to create Signal, as well as how to run Signal on a Raspberry Pi Zero W can be found here:
[projectboard.world/ysc/project/real-time-conversion-of-sign-language-to-speech-using-ai-and-deep-learning](projectboard.world/ysc/project/real-time-conversion-of-sign-language-to-speech-using-ai-and-deep-learning)

Signal was created using the Google Tensorflow Object Detection API, as well as pre-trained models from the Google Tensorflow dataset. Transfer learning was also used in the creation of this project.

**Phrases Supported**
The following list contains all sign language phrases that were used to train Signal's dataset. These words can be translated seperately, or as a combination to form a phrase or sentence.

* "Hello"
* "Yes"
* "No"
* "Thank You"
* "I Love You"
* "How?"
* "You"
* "You Are"
* "Are You?"
* "I"
* "Fine"
* "Hungry"
* "Angry"
* "Help"
* "Name"


**Awards**
* [Toronto Science Fair - Regional Gold](https://www.torontosciencefair.ca/previous-fairs/2021-gold-medal-recipients#h.lr3yzoszwmvv)
* [Canada Wide Science Fair - National Silver](https://projectboard.world/ysc/project/real-time-conversion-of-sign-language-to-speech-using-ai-and-deep-learning)
* Candaa Wide Science Fair - WesternU Scholarship ($2000 Value)
* [Toronto Science Fair - Sigma Xi Book Award ($150 Value)](https://www.torontosciencefair.ca/previous-fairs/2021-special-award-recipients#h.c7cz7cmwg68u)
* [2020 BEST Lab STEM Entreprenurship Expereince - Bronze Finalist](https://www.instagram.com/p/CS9xKT3ra_Q/)


**References**
Brownlee, J. (2019, September 16). A Gentle Introduction to Transfer Learning for Deep Learning. Machine Learning Mastery. https://machinelearningmastery.com/transfer-learning-for-deep-learning/#:~:text=Transfer%20learning%20is%20a%20machine,model%20on%20a%20second%20task.&text=Common%20examples%20of%20transfer%20learning,your%20own%20predictive%20modeling%20problems.

Text-to-speech x-platform¶. pyttsx3. (n.d.). https://pyttsx3.readthedocs.io/en/latest/.

**Code from this documentation was used in this project**

Tzutalin. (n.d.). tzutalin/labelImg. GitHub. https://github.com/tzutalin/labelImg.

**The python program from this github repository was used in this project**



