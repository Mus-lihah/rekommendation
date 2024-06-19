# rekommendation
Recommendation model for the Bangkit 2024 Capstone Project 


# execute the IPYNB file
1. Download the IPYNB file
2. Download the storyy.csv file and save it in the local directory
3. Upload the IPYNB file to Google Colaboratory
4. Run the file

# Implementing the model
1. Download tha app.py file
2. Download the files in the "model" folder: "rekomendasiByStoryID.h5" and "vectorizer.pkl" and save it
3. Download the requirements.txt file and save it
4. For app.py, edit the "model_path" and "vectorizer_path" sections according to where you have saved your .h5 and .pkl files.
5. Create a virtual environment
6. Activate the virtual environment
7. Install the required packages "pip install -r requirements.txt"
8. enter "python app.py" to execute it, and make sure you are connected to the database.
9. open the postman app
10. In the header tab, set the key to "Content-Type" and the value to "application/json". 
11. Next, in the Body tab, select the raw format, and choose JSON format on the right side.
12. for example, enter the following JSON:
    {
    "story_id": 10,
    "top_n": 10
  }
13. send post request in the POSTMAN APP "http://127.0.0.1:5000/recommend"
