# YouTubeVideoSmmarizer
A streamlit web-app which provide you with concise summaries of any YouTube content. 
This feature is particularly useful for lengthy lectures, tutorials, and documentaries.

## Development 
1. Clone a repo using
   
   `git clone [github https url]`
3. Set up the Virtual Environment
   
   `conda create -p venv/ python==3.10`
5. Add requirements using
   
   `pip install -r requirements.txt`
7. Set up your `.env` file

   - Your `.env` file should look like this : 
   `GOOGLE_API_KEY = "<YOUR_GOOGLE_API_KEY>"`
   - Visit [Google AI for Developers](https://ai.google.dev/gemini-api/docs/ai-studio-quickstart?gad_source=1&gclid=CjwKCAjwi_exBhA8EiwA_kU1MsJAXeebfGHQ4_apjV6dkMecboAgsbgf_SshYhk69nwLdRxi7MPxzxoCMVYQAvD_BwE) to retrieve Google API key and insert into your `.env` file.
9. Run the Streamlit app

   `streamlit run app.py`
   
