# APM_Doodle

Doodling Image Recognition
The Power of Deep Learning Models!
In this blog, we will describe how we built powerful deep learning models to predict doodle images based on the Kaggle doodle dataset. The process includes problem introduction, data description, data cleaning, predictive modeling, model comparison and our business insights/recommendations.
This project also has a blog written by us, checkout here: 
https://mshch96.medium.com/doodling-image-recognition-5ab25476a728

Problem Introduction
“Quick, Draw!” is an online game built with machine learning developed by Jonas Jongejan, Henry Rowley, Takashi Kawashima, Jongmin Kim, Nick Fox-Gieg, with friends at Google Creative Lab and Data Arts Team. It is the world’s largest doodling dataset, and is an experimental game to educate the public about how AI works. 
The game is very simple. It will ask the player to draw an image of a certain category, such as “key”, “mailbox”, “monkey”, etc. When the player is drawing, the machine learning tool will guess what that image depicts and also save the image that the user draws to the database.
You can try the game yourself through this link!
Our task is to build models with the existing dataset that could classify the doodles to the correct classes/labels. To be more specific, our models should predict the correct “word” of the drawing. Our models include CNN(Convolutional Neural Networks), MobileNet, ResNet. Since people around the world draw differently. Our project is important to reveal insights into how the drawings are different, yet the same. These models are extremely good to deal with image recognition.
