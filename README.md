
# LLaMA-2 Blog Generator 🚀

This project demonstrates a simple web application built with Streamlit to generate blogs using the **LLaMA-2** model. Users can input a blog topic, choose a writing style, and specify the number of words, and the application will generate a blog post based on the provided parameters.

## Features

- Input a desired blog topic.
- Select the writing style for the blog (e.g., Researchers, Data Scientist, Common People).
- Specify the number of words for the generated blog.
- Generate a blog post with a single click.

## Requirements

To run this application, you need to have the following dependencies installed:

- Streamlit
- langchain
- langchain-community
- ctransformers

You can install the required packages using pip:

```bash
pip install streamlit langchain langchain-community ctransformers
Usage
Clone the repository or download the project files.

Make sure the LLaMA-2 model file (llama-2-7b-chat.ggmlv3.q8_0.bin) is located in the models directory.

Navigate to the project directory in your terminal.

Run the Streamlit application:

bash
Copy code
streamlit run app.py
Open your web browser and go to http://localhost:8501 to view the application.

Enter your desired blog topic, select the writing style, and specify the number of words, then click the "Generate" button to create your blog.

Directory Structure
php
Copy code
LLaMA-2-Blog-Generator/
│
├── app.py                 # Main Streamlit application file
├── models/                # Directory containing the LLaMA-2 model file
│   └── llama-2-7b-chat.ggmlv3.q8_0.bin
└── requirements.txt       # List of required packages
License
This project is licensed under the MIT License. See the LICENSE file for more information.

Acknowledgments
Thanks to the creators of the LLaMA-2 model and the Streamlit framework for making this project possible.

Contact
For questions or suggestions, feel free to reach out:

Email: sovit.nayak03@gmail.com
GitHub: sovitnayak123
