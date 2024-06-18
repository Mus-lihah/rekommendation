# rekommendation
Recommendation model for the Bangkit 2024 Capstone Project 


# execute the IPYNB file
1. Download the IPYNB file
2. Download the storyy.csv file and save it in the local directory
3. Upload the IPYNB file to Google Colaboratory
4. Run the file

# deploy model
1. Download the files in the "model" folder: "rekomendasiByStoryID.h5" and "vectorizer.pkl" and save it
2. Download the requirements.txt file and save it
3. Create a virtual environment
4. Activate the virtual environment
5. Install the required packages "pip install -r requirements.txt"
6. enter "python app.py" to execute it.
7. open the postman app
8. click on the Body tab, select the raw format, and choose JSON format on the right side.
9. for example, enter the following JSON:
    {
    "story_id": 10,
    "top_n": 10
  }
10. send post request in the POSTMAN APP "http://127.0.0.1:5000/recommend"
