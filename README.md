The Flight Fare Prediction App is a machine learning-powered tool that estimates airline ticket prices based on various travel parameters. Users can input details such as departure and arrival cities, travel date, and airline preference to receive a predicted fare, helping them make smarter and more informed booking decisions.

This app is ideal for travelers, hobbyists, or anyone curious about how airfare prediction works using real-world data.
Built With
- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- Flask
- DVC
- MLFlow


------------------Getting Started-------------------------

Follow the instructions below to set up and run the project locally.

1. Clone the Repository

git clone https://github.com/Nayeem114477/flight-fare-prediction.git

cd flight-fare-prediction

2. Set Up Virtual Environment (Recommended)

Using conda:

conda create -p venv python=3.10 -y

conda activate ./venv

Or using venv:

python -m venv venv

venv\Scripts\activate     # Windows

source venv/bin/activate  # macOS/Linux

3. Install Dependencies
   
pip install -r requirements.txt

4. Run the App

python app.py

5. Open in Browser
Visit http://localhost:5000 to access the app.


Project Structure

.

├── app.py

├── templates/

├── static/

├── models/

├── requirements.txt

├── dvc.yaml

└── README.md
