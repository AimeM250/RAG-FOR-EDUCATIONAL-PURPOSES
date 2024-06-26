# RAG-FOR-EDUCATIONAL-PURPOSES

![EDUCATIONAL CHATBOT USING RAG]("images/demo_image.JPG")

This project aims to improve educational support through the use of a new capability in Large Language Models named "RAG ~ Retrieval Augmented Generation," alongside Vector Databases. In the project, we utilize the Gemma language model developed by Google, which features 7 billion parameters. To access its functionalities, you must log in to Hugging Face and add your Hugging Face token in the `model.py` file.

### Installation

Install dependencies by running:
pip install -r requirements.txt

### Usage

Run the application using Streamlit:
streamlit run app.py


### GPU Support

For enhanced performance, GPU (cuda) usage is recommended, leveraging Nvidia hardware. If a compatible GPU is not available, simply adjust the device setting from "cuda" to "cpu" in the model, and remove the quantization configuration. Ensure that the NVIDIA Toolkit is installed prior to PyTorch.

### Additional Resources

- **`Presentation:`** [Link to Presentation](https://docs.google.com/presentation/d/1FlJmCupQK827zWNo5LjzIVhH8-3AfJeC/edit?usp=drive_web&ouid=104339001137477334178&rtpof=true)
- **`Report:`** [Link to Report](https://docs.google.com/document/d/1UOCDnjlXDiy5vD-KRuhnjd5tcv8nlVgAIaR44bmaR-I/edit)
- **`Demo Video:`** [Link to Demo Video](https://drive.google.com/file/d/1dnXt9rFuqz4zA9tN1qHeXZZ9FBX6xmlF/view?usp=drive_link)

**`Contributors` :** Aime Munezero, Seth Abayo, Kevin Mucyo, Leonidas Mugema

