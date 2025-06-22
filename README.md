🧠 Handwritten Digit Generator Web App
This project demonstrates a complete workflow for building and deploying a web application that generates handwritten digits (0–9) using a Generative Adversarial Network (GAN) trained on the MNIST dataset.

🎯 Features
Users can select a digit from 0 to 9.

The app generates 5 different images of that digit.

Images are styled like MNIST (28×28 grayscale).

Fully trained from scratch using PyTorch on a T4 GPU in Google Colab.

No pre-trained weights used — complies with exam restrictions.

🚀 Live Demo
🔗 [Click here to launch the app](https://handwritten-digit-generation-web-app-spwz4vkjeaves9jfoqsag9.streamlit.app/)


🛠️ Tech Stack
Component	Tool
Model Training	PyTorch on Google Colab
Dataset	MNIST
Web App Framework	Streamlit
Deployment	Streamlit Cloud

📂 Files Included
File	Purpose
app.py	Streamlit web application script
generator.pth	Trained PyTorch generator model
requirements.txt	Required Python packages for deployment
train_gan_mnist.ipynb (optional)	Colab notebook used for training

🧪 How to Use
Train the GAN (already done)
The model was trained in Google Colab using the MNIST dataset for 20 epochs.

Run Locally (optional)

bash
Copy
Edit
pip install -r requirements.txt
streamlit run app.py
Deploy on Streamlit Cloud
Upload all files to a public GitHub repo and deploy via streamlit.io/cloud.

📌 Notes
This app satisfies the requirements for Problem 3 – Handwritten Digit Generator Web App in the LLM x AI Exam.

It uses a simple conditional GAN to produce class-specific digit images.

Accuracy was not prioritized; diversity across the 5 generated images was the key goal.

📧 Contact
For feedback or questions, feel free to open an issue or reach out.
