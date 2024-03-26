[![omp-6.png](https://i.postimg.cc/ZKpGKngK/omp-6.png)](https://postimg.cc/QHN4f8hR)

Google Colab: [link](https://www.freecodecamp.org/certification/Knaus-Elias-Gustavo/data-analysis-with-python-v7)

**I recommend that the CSV files are located inside the drive folder**

**Project Description: Sales Analysis with Linear Regression in Python**

**Objective:**
This project aims to conduct a detailed analysis of sales using linear regression techniques and Machine Learning.

**Workflow:**

**Data Loading:**
   - psycopg2 library is used to connect to the Northwind database.
   - A function is developed to convert database tables into DataFrames.
   - Key tables such as "products", "orders", "customers", and "order details" are loaded into DataFrames.
   - DataFrames are saved as CSV files on Google Drive for easy access.

**Data Preprocessing:**
   - Saved CSV files are retrieved from Google Drive.
   - Tables are merged to obtain a comprehensive view of sales.
   - A column is added to identify the day of the week.
   - Missing value check is performed to maintain data integrity.

**Sales Analysis:**
   - Total sales and total revenue generated are calculated.

**Linear Regression with TensorFlow:**
   - The DataFrame is split into training and testing sets.
   - A function is created to build a simple linear regression model using TensorFlow.
   - The model is trained using the "index" feature (average income) and the "Income" label.
   - Loss curve is visualized to evaluate the model's performance.

**Linear Regression with scikit-learn:**
   - Data is divided into training and testing sets.
   - A linear regression model is built using scikit-learn.
   - The model is trained, and predictions are made on the test set.
   - Model performance is evaluated by calculating the mean squared error (MSE) and the coefficient of determination (R^2).

**Key Points:**

- The project utilizes both TensorFlow and scikit-learn to implement linear regression, providing a comparison between the two approaches.
- A basic sales analysis is conducted before applying linear regression models.
- Loss curves are used to visualize the model's performance in TensorFlow.
- Model accuracy is evaluated using metrics such as MSE and R^2.

**Improvements:**

- New features can be explored to enhance model accuracy.
- Trying out other Machine Learning algorithms could provide additional insights into sales predictions.
- Code optimization can be done to improve efficiency and scalability.


**Conclusion:**

In this project, we successfully conducted a comprehensive analysis of sales using linear regression techniques and Machine Learning in Python. By leveraging libraries like TensorFlow and scikit-learn, we were able to build and evaluate predictive models to understand sales patterns and forecast future revenues.

Through data preprocessing, we ensured the integrity of our data and prepared it for analysis. Exploring sales data allowed us to gain valuable insights into total sales and revenue generation.

Implementing linear regression models with TensorFlow and scikit-learn provided us with different perspectives on modeling sales data. We visualized model performance using loss curves and evaluated accuracy using metrics such as MSE and R^2.

Moving forward, there are opportunities to further enhance our models by exploring additional features and experimenting with different Machine Learning algorithms. Additionally, optimizing our code can improve efficiency and scalability for larger datasets or real-time applications.

Overall, this project serves as a valuable learning experience in applying data science techniques to real-world sales data, with the potential for future refinement and expansion.
