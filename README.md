Name:Saurav Yadav Comapny: CODTECH IT SOLUTIONS ID:CT08DS590 Domain: Data Science Duration: 12Dec2024 - 12 Jan2025

Deploying Deep Learning Model using Flask API






<img width="711" alt="Screenshot 2025-01-03 at 6 51 29 PM" src="https://github.com/user-attachments/assets/8d434d97-fc40-4d14-b0e7-16af76f2000d" />





<img width="711" alt="Screenshot 2025-01-03 at 6 51 53 PM" src="https://github.com/user-attachments/assets/3e1962d7-4c9a-4b92-9962-b07227ded610" />







<img width="682" alt="Screenshot 2025-01-03 at 6 51 05 PM" src="https://github.com/user-attachments/assets/c55f6589-e8b6-4030-b9f2-d7416b633dd8" />


Introduction
we’ll see how we can take your work and show it to an audience by deploying your projects on the web. Machine Learning engineers should know the implementation of deployment to use their models on a global scale.


About the Model
I build a model to predict fruit categories. In this model, Have 3 classes which are Apple, Banan, and Orange. I used VGG pre-trained model to perform this classification problem.

Saving Trained Models
You can save your model by calling the save() function on the model and specifying the filename. But usually, we can save the model in 3 formats.

YAML
JSON
HDF5
We are going to save and use model weights so we take HDF5. Once build the model save the model using the save() function.

model.save('model.h5')
