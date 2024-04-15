# RAG-FOR-EDUCATIONAL-PURPOSES

This project utilizes the Gemma language model (7 billion parameters) developed by Google. To access its functionalities, you must log in to Hugging Face and add  your Hugging Face token in the `model.py` file.

### Installation

Install dependencies by running:
pip install -r requirements.txt

### Usage

Run the application using Streamlit:
streamlit run app.py


### GPU Support

For enhanced performance, GPU (cuda) usage is recommended, leveraging Nvidia hardware. If a compatible GPU is not available, simply adjust the device setting from "cuda" to "cpu" in the model, and remove the quantization configuration. Ensure that the NVIDIA Toolkit is installed prior to PyTorch.

### Additional Resources

- Presentation: [Link to Presentation](insert-link-here)
- Report: [Link to Report](insert-link-here)
- Demo Video: [Link to Demo Video](insert-link-here)
