 How the Titanic Survival Prediction Model Works
This Titanic Survival Prediction model is trained using historical passenger data from the Titanic disaster. It predicts whether a passenger would have survived or not based on several key factors.

The model follows these steps:

Input Processing: The user provides passenger details like class, age, gender, fare, etc.
Data Encoding: Categorical inputs like Sex and Fare are converted into numerical values.
Model Prediction: The trained machine learning model processes the inputs and predicts the survival outcome.
Output Interpretation: If the predicted result is 1, it means the passenger survived; otherwise, they did not survive.
 Explanation of Input Fields in Streamlit UI
Here’s what each input field means:

Field Name	Description	Impact on Survival

Pclass (Passenger Class)	Class of the ticket purchased (1st, 2nd, or 3rd)	Higher classes (1st) had a higher survival rate
Sex	Gender of the passenger (Male/Female)	Females had a higher survival rate than males
Age	Age of the passenger	Younger passengers had a better chance of survival
Fare	Ticket fare categorized as Low, Medium, High, or Very High	Higher fare amounts were associated with higher survival rates
Embarked (Port of Embarkation)	The port where the passenger boarded (C = Cherbourg, Q = Queenstown, S = Southampton)	Some ports had higher survival rates than others
Family Size	Total family members (siblings/spouses + parents/children)	Moderate family sizes had a better survival chance
 How the Model Predicts Survival
The model was trained using machine learning algorithms on the Titanic dataset. It considers patterns in historical survival data, such as:

Women and children having a higher survival rate.
First-class passengers having better access to lifeboats.
High fare and moderate family size increasing survival chances.
After processing the input, the model predicts survival based on these learned patterns.
