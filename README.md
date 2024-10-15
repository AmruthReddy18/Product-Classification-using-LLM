🛒 Product Classification using Language Models
📋 Overview
This project demonstrates the use of a language model to classify products into their respective departments based on the Instacart dataset. It leverages the Falcon-7B model to generate predictions from product names.

✨ Features
🔗 Dataset Merging: Combines product and department datasets for effective training.
🛠️ Model Training & Fine-tuning: Utilizes advanced libraries like Transformers and PEFT for model training and optimization.
🧾 Product Classification Pipeline: Implements a robust text generation pipeline to classify products.
📊 Model Evaluation: Assesses performance using a separate test dataset.
🛠️ Technologies Used
🐍 Python
🗃️ Pandas
🔄 Transformers
🎛️ PEFT
📂 Datasets
📂 Dataset
The datasets used were sourced from Kaggle's Instacart Market Basket Analysis. The key files include:

📦 orders.csv: Contains order-level information.
📋 products.csv: Includes product details like names and IDs.
🏷️ departments.csv: Lists department information associated with each product.
⚙️ Installation & Prerequisites
Ensure the following dependencies are installed before running the project:

🐍 Python 3.6 or higher
📦 Pip
To install required libraries, run:

bash
Copy code
pip install -r requirements.txt
🙌 Acknowledgments
Special thanks to:

🤗 Hugging Face for their Transformers library.
🛠️ PEFT for providing efficient fine-tuning options.
🏆 Kaggle for the Instacart Market Basket dataset.
