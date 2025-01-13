
# 📧 Cold Mail Generator
A cold email generator for a services company, built with GROQ, LangChain, and Streamlit. Users can input the URL of a company's careers page, and the tool extracts job listings from the page. It then creates personalized cold emails tailored to each job description, including relevant portfolio links retrieved from a vector database.

# insipred by codebasics

## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `app/.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 


2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run app/main.py
   ```
   
