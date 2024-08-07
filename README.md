# Medicine Recommendation System

![web application image](https://github.com/user-attachments/assets/d54daf2d-f93b-46cf-a101-ba0f6112f608)

Project Title = Medicine Recommendation System

## Project Description
### Medicine Recommendation System
The Medicine Recommendation System is a sophisticated tool designed to assist healthcare professionals and patients in selecting the most appropriate medications based on individual needs and preferences. By leveraging a comprehensive medicine dataset and advanced machine learning techniques, this system provides personalized recommendations, enhancing the decision-making process in healthcare.

This project utilizes Python for data processing and machine learning, Jupyter Notebook for development and analysis, and HTML for the user interface. The system integrates various features, such as filtering by symptoms, patient history, and medication interactions, to ensure safe and effective recommendations.

Dataset Description
Medicine Dataset
The dataset used in this project is a comprehensive collection of information about various medicines, including their properties, usage guidelines, potential side effects, and interactions with other medications. It includes the following key features:

Medicine Name: The name of the medication.
Active Ingredients: The main ingredients that make the medicine effective.
Dosage Forms: Available forms of the medication (e.g., tablet, capsule, liquid).
Dosage Guidelines: Recommended dosages for different age groups and conditions.
Indications: Medical conditions or symptoms that the medication is used to treat.
Contraindications: Situations or conditions where the medication should not be used.
Side Effects: Common and rare side effects associated with the medication.
Drug Interactions: Known interactions with other medications.


Technologies Used
Python
Python is the primary programming language used in this project. Its extensive libraries and frameworks, such as Pandas, NumPy, and Scikit-learn, facilitate efficient data processing, analysis, and machine learning model development.

Jupyter Notebook
Jupyter Notebook is used as the development environment for this project. It provides an interactive interface for writing and running Python code, making it easy to visualize data, test algorithms, and document the development process.

HTML
HTML is used to create the front-end interface of the medicine recommendation system. It enables the presentation of data and recommendations in a user-friendly format, allowing healthcare professionals and patients to interact with the system seamlessly.

Additional Libraries and Tools
Pandas: For data manipulation and analysis.
NumPy: For numerical computations.
Scikit-learn: For building and evaluating machine learning models.
Flask (if applicable): For developing a web application to host the recommendation system.
Matplotlib/Seaborn: For data visualization and exploratory data analysis.


Features

Key Features

Personalized Medicine Recommendations:
The system provides personalized medication suggestions based on individual patient profiles, including medical history, symptoms, and preferences.
Symptom-Based Filtering
Users can input symptoms, and the system will recommend appropriate medications that target those specific symptoms.

Drug Interaction Checker:
The system checks for potential interactions between prescribed medications, ensuring safe combinations and preventing adverse effects.
Detailed Medication Information
Each recommendation comes with comprehensive information about the medicine, including usage guidelines, dosage, potential side effects, and contraindications.

User-Friendly Interface:
The HTML-based interface offers an intuitive and easy-to-navigate platform for users to input data and receive recommendations.
Machine Learning Integration
Advanced machine learning algorithms analyze the data to enhance the accuracy and relevance of medication recommendations.

Search Functionality:
Users can search for specific medications to obtain detailed information or verify compatibility with other drugs.
Regular Updates
The system can be updated with the latest medical guidelines and newly approved medications to ensure current and relevant recommendations.


How to Run the Project
Prerequisites
Before running the project, ensure you have the following installed on your system:
Python 3.6 or higher
Jupyter Notebook
Required Python libraries (listed in requirements.txt)

Installation

1.Clone the Repository
Clone the repository to your local machine using the following command:
bash
Copy code
git clone https://github.com/amolnayakawadi/medicine-recommendation-system.git
Navigate to the project directory:
bash
Copy code
cd medicine-recommendation-system


2.Set Up a Virtual Environment
It's recommended to use a virtual environment to manage dependencies. Create and activate a virtual environment using the following commands:
bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`


3.Install Dependencies
Install the required Python libraries from the requirements.txt file:
bash
Copy code
pip install -r requirements.txt


4.Running the Jupyter Notebook
Start Jupyter Notebook
Launch Jupyter Notebook from the project directory:
bash
Copy code
jupyter notebook
This command will open the Jupyter Notebook interface in your web browser.

5.Open the Project Notebook
In the Jupyter Notebook interface, navigate to and open the main notebook file (medicine_recommendation_system.ipynb).

6.Run the Cells
Execute the cells in the notebook sequentially. This will load the dataset, preprocess the data, train the machine learning model, and display the results.


7.Running the Web Interface (if applicable)
Navigate to the Web Directory
If your project includes a web interface, navigate to the web directory:
bash
Copy code
cd web

8.Start the Flask Server
Start the Flask server to host the web application:
bash
Copy code
python main.py
Open your web browser and go to http://127.0.0.1:5000 to interact with the medicine recommendation system.
