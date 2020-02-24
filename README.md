# Machine Learning Final Project: Kuzushiji Translation
![Kuzushiji](https://i.imgur.com/dhBM3BG.jpg)

### Background on the Kuzushiji Challenge

* 800-1900 CE: Japan used a writing system called Kuzushiji

* Cursive Japanese writing style comprising of Chinese characters and Japanese hiragana characters

* 99.99% of Japanese speakers cannot read texts which are more than 150 years old

* Three million books holding important information about Japanese culture and history remain inaccessible to the general public

* Due to lack of manpower, the National Institute of Japanese Literature (NIJL) has turned to the help of computers to translate these texts into Modern Japanese characters


### Goal
To use machine learning to automatically translate Kuzushiji to modern Japanese texts in order to unlock classical Japanese literature and Japanese history contained in these books.

![Kuzushiji with the contemporary traslations on the side](https://thegradient.pub/content/images/2019/11/image6.jpg)

### Solution
I used a 2-step solution where I first use CenterNet neural networks to detect characters within a page, followed by  Convoluted Neural Networks with a ResNet backbone to then classify each character to a modern Japanese character.

The kaggle competition can be found here:
https://www.kaggle.com/c/kuzushiji-recognition/overview
