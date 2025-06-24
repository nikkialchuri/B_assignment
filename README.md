# B_assignment
Name:alchuri nikhitha
Student id:700764794
Part 1: Question Answering with Transformers
 Overview
A simple question-answering system built using Hugging Face's transformers library. The system can answer questions based on a given context using pre-trained language models.

 Features
Use of default QA model (distilbert-base-uncased-distilled-squad)

Custom model: deepset/roberta-base-squad2

Answers questions with confidence scores and text span positions

 Tasks Performed
Basic QA Pipeline
Load default QA model and answer a question from a short context.

Use a Custom Pretrained Model
Switch to deepset/roberta-base-squad2 for improved accuracy and robustness.

Custom QA Example
Create your own context, ask two questions, and retrieve relevant answers with high confidence.

Part 2: Digit-Class Controlled Image Generation with Conditional GAN
 Objective
Generate MNIST digits (0–9) using a Conditional GAN, where the output is conditioned on the input digit label.

Model Architecture
Generator: Accepts random noise + digit label (embedded) and produces a 28×28 image.

Discriminator: Takes an image + label and outputs a real/fake score.

Labels are embedded and concatenated to both noise and image inputs.

 Key Steps
Modify GAN to condition on labels.

Train using MNIST dataset.

Generate images per digit class.

Visualize a row of digits from 0 to 9.

🖼 Expected Output
One row of 10 images: each image is a digit from 0 to 9.

Generator learns to control output class effectively over time.



