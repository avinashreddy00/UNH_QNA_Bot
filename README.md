## UNH_QNA_Bot
## DSCI-6004-03-NLP-Project
## NLP Final Group Project on UNH_QNA bot using Google PaLM

Introducing the UNH Question and Answer Bot: Your All-Inclusive Guide to University of New Haven Queries
The UNH Question and Answer Bot stands as a purpose-built, closed-domain solution crafted explicitly to address a spectrum of inquiries related to the University of New Haven. Whether seeking information on registration processes, financial queries, transportation logistics, or more, this user-friendly tool emerges as a comprehensive resource. Seamlessly navigating the multifaceted landscape of university-related questions, this bot strives to simplify and expedite access to crucial information for students, staff, and faculty alike. By offering a centralized and intuitive interface, it aims to enhance the accessibility and convenience of obtaining precise and timely answers, streamlining the University of New Haven's information ecosystem for the benefit of all willing to know about the university.

![image](https://github.com/avinashreddy00/UNH_QNA_Bot/assets/54584829/ef341db7-20ec-41ba-94c9-96a26be8a70d)

### Objective
1.	Constructing a bot for UNH question answers using large language models like GPT2 and Google PaLM which are built of two different architectures Transformer based, path based respectively, compare their performance using intrinsic evaluation
2.	Identify the most effective model (GPT2 or Google PaLM) based on accuracy for accurate answer generation for the question.
3.	Implement the chosen model into a user-friendly Streamlit app, enabling a user-friendly tool to emerge as a comprehensive resource for the university.
4.	Analyze model results to understand performance disparities and reveal insights into the strengths and weaknesses of each method.

### Project Structure:
1. main.py: The main Streamlit application script.
2. langchain_helper.py: This has all the langchain code.
3. requirements.txt: A list of required Python packages for the project.
4. .env: Configuration file for storing your Google API key.

### Usage Instructions:
1. Clone UNH_QNA_project repository to your local machine
``` git clone https://github.com/avinashreddy00/UNH_QNA_Bot/tree/main/UNH_QNA_project ```
2. Create a virtual environment
``` python -m venv /path/to/new/virtual/environment ``` 
3. Install the required dependencies in the requirements file
```   pip install -r requirements.txt ```
4. Acquire an API key through makersuite.google.com and put it in .env file
```   GOOGLE_API_KEY="your_api_key_here" ```
5. Run the Streamlit app (streamlit run main.py)
``` streamlit run main.py ```
6. Use sample questions mentioned in the sample questions file or you can ask your questions regarding the University of New Haven
