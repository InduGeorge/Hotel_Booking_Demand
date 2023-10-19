# Hotel_Booking_Demand
Hotel Booking Demand : Prediction of booking cancellation

The hotel demand stems from business travelers and leisure tourists who travel frequently. With information on the hotel bookings, the main objective of this project is to predict the probability of booking cancellation. 
The business questions addresssed here : 
1) Would a customer cancel his/her booking? 
2) If yes, what are the driving factors of booking cancellations?
In addition to that, this report is a summary of a data analysis study completed for City and Resort hotels to assess customer retention, repeat customer behavior analysis, and assist Hotel Management in anticipating hotel reservations based on seasonality and room type preferences. Customers' meals and any additional specific demands.

# Data set
Domain: Tourism
The link to the dataset : https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand

The data used is the hotel demand dataset on Kaggle that contains information on two types of hotel, the resort and city hotel.  There are 1,19,390 rows and 32 characteristics in the dataset. Each observation represents a customer's hotel reservation. Customers who booked between July 1, 2015, and August 31, 2017, are included in the dataset, along with information on cancellation status. It also includes information on the stay, such as length of stay, number of adults, hotel amenities such as parking, and information about the country, market segment, and arrival date of the booking.


# Required Development Tools & Setup
1.Python environment like jupyter notebook or Google Colab.

2. Libraries including:
   
                       Numpy                             
                       Pandas                              
                       scikit-learn                       
                       Matplotlib                                   
                       Seaborn
                       folium
                       plotly

## Installation

Link to clone the repository:https://github.com/InduGeorge/Hotel_Booking_Demand.git

Instructions:

              1. Open your preferred Python environment (e.g., Jupyter Notebook, Spyder).

              2. Navigate to the Hotel Booking Demand - Prediction of booking cancellation.ipynb file within your project directory, which is located in the Hotel_Booking_Demand repository.

              3. Open the notebook by clicking on the Hotel Booking Demand - Prediction of booking cancellation.ipynb file.

              4. Execute the code cells in the notebook sequentially by clicking on each cell and either pressing Shift+Enter or using the "Run" button in the notebook interface. This notebook is designed for predicting booking cancellations in hotel reservations.


# Workflow 

### 1.Data Loading
### 2.Exploratory Data Analysis
       #re-run the code if the visualization is not available while loading the notebook.
### 3.Data Preprocessing
       1) Handling missing values
       2) Handling outliers
       3) Feature selection and feature engineering
       4) Feature reduction
       5) Encoding
       6) Feature scaling
       
### 4.Modeling and Hyper Parameter Tuning
We have tried out different models and the accuracy scores for each of the model are as follows :

Logistic Regression : 95%

kNN : 92% 

SVM (kernel - linear) : 96% 

SVM (kernel - rbf) : 96% 

Decision Tree Classifier : 95% 

Random Forest Classifier : 96%
              
We have also performed model fine tuning/hyperparameter tuning for the below models

1) kNN – using GridSearchCV

Best Parameters: Best leaf_size: 1 Best p: 1 Best n_neighbors: 3 Accuracy : 87%

2) Random Forest Classifier – using RandomizedSearchCV

Best parameters : 'bootstrap': True, 'max_depth': None, 'max_features': 'sqrt', 'min_samples_leaf': 1, 'min_samples_split': 2, 'n_estimators': 1000 Accuracy : 97%

Random Forest Classifier after hyperparameter tuning gives the highest accuarcy of 97% and it is chosen as the best model.

#re-run the code if the visualization is not available while loading the notebook.


   

                                          
                       


