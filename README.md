# Handwritten-Digit-Recognition-using-MNIST-Dataset-Task-3

🔢 Number Recognition! 🚀

Thrilled to unveil my Handwritten Digit Recognition triumph, fueled by Bharat Intern's guidance! 🎉

_**🌟 What's New:**_
✅ Task 3 Achieved: Proudly completed Task 3 with Bharat Intern.
✅ MNIST Magic: Leveraged the renowned MNIST dataset for precision.
✅ Neural Networks: Designed an ingenious solution for deciphering digits.
✅ Tech meets Creativity: Merged innovation with tech for real-world AI impact.

_**Key Features:**_
1.	Data Preprocessing: The MNIST dataset is loaded and preprocessed. Images are scaled to have pixel values ranging from 0 to 1.
2.	Model Architecture: Two models are constructed. The first is a simple model with a single output layer of 10 neurons using the sigmoid activation function. The second includes an additional hidden layer of 100 neurons with ReLU activation before the output layer.
3.	Model Compilation: Both models are compiled using the 'adam' optimizer and the 'sparse_categorical_crossentropy' loss function for multiclass classification. Accuracy is chosen as the evaluation metric.
4.	Training: The models are trained on the flattened training data using the fit method. The number of training epochs is set to 5.
5.	Evaluation: The models' accuracy is evaluated using the flattened test data.
6.	Confusion Matrix: The confusion matrix is computed and visualized using seaborn. It shows how well the model predicted each class.
7.	Sample Predictions: Randomly selected test images are displayed alongside their true labels and predicted labels for the model with a hidden layer.

_**Key Insights and Analysis:**_
1.	Hidden Layer Benefit: The model with a hidden layer (ReLU activation) tends to perform better than the simple model with only an output layer (sigmoid activation). Adding a hidden layer allows the model to learn more complex features and patterns, resulting in improved accuracy.
2.	Confusion Matrix: The confusion matrix provides insights into how well the model performs for each class. It helps identify whether the model struggles with particular digits and the degree of confusion between different digits.
3.	Sample Predictions: The displayed sample images, along with their true labels and predicted labels, give a visual understanding of the model's performance. It allows you to see instances where the model succeeded or failed in making accurate predictions.
4.	Data Visualization: The code includes visualization components that enable a better understanding of the dataset, model performance, and predictions.
5.	Model Iterations: The code showcases iterative training with multiple epochs. Typically, models benefit from more training epochs, but there's a risk of overfitting if not monitored closely.


# Demo Video:
https://github.com/Elanchezhian2712/Handwritten-Digit-Recognition-using-MNIST-Dataset-Task-3-/assets/122656808/045fc139-6eab-4218-82f5-592ae032e329

