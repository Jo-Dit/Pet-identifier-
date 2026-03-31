# Pet-identifier-
Beginner introduction project to ML, application to differentiate between my families different Cavalier King Charles Spanials

Project summary
- Problem: When guests come to my house they are unable to differentiate between our 5 different King Charles Spanials
- Solution: Create a simple computer vision web app which allows people to take a picture of the dog in front of them and identify which out of the 5 it is.

Page:
<img width="562.66" height="270" alt="image" src="https://github.com/user-attachments/assets/647ffff6-36b5-4f8e-8f88-52c089abdb7e" />


Usage
- People upload or take a picture of one of the 5 dogs and the model makes a prediction on which dog it is and then tells the person the name of the dog and the liklihood that it is correct
- Dogs= Lily, Henry, Wilbur, Charlottle, and Ivy

How it works
- Used MobileNetV2 which was pretrained on ImageNet then I used roughly 400 pictures of the dogs to "finetune"
- Used Data augmentation to increase the variety the model saw
- Finally used the Gradio inteface so people can easily use this project

Tech Stack 
- python
- Google Collab (environment used to run everything)
- TensorFlow / Keras (used to build/train the model)
- MobileNetV2 (pretrained model used as a base)

How to run
Open the notebook in Google Colab, run all cells, and click the Gradio link to launch the app
