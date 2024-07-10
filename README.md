# Email-Classification-Using-NLP

This project focuses on classifying emails into job-related and academic-related categories using natural language processing (NLP) techniques. The classification is based on the content of the email body, making it more versatile and efficient compared to traditional rule-based filtering systems.

## Project Overview
Many email clients, such as Outlook, provide rule-based filtering systems where users can create rules to categorize emails based on sender addresses, subject lines, or other specific criteria. While effective, these systems require users to manually specify each rule, which can be time-consuming and difficult to manage, especially with large volumes of emails or changing sender addresses.
This project leverages machine learning and NLP to automatically classify emails based on the email body content, regardless of the sender or subject line. This approach eliminates the need to manually create and maintain complex rules for different senders, offering a more streamlined and adaptive solution for email management.

## Advantages Over Traditional Rule-Based Filtering
* Content-Based Filtering: The model classifies emails based on the content of the email body, making it more adaptable to various senders and subject lines without requiring explicit rules for each case.
* Reduced Maintenance: No need to constantly update and manage rules for different email addresses or subjects. The model adapts to new email formats and contents automatically.
* Scalability: Handles large volumes of emails efficiently without the need for manual intervention to create or update rules.
* Improved Accuracy: Utilizes advanced NLP techniques to understand the context and semantics of the email content, leading to more accurate classifications compared to simple keyword-based rules.
  
## Project Structure
* Data: The project uses a dataset of emails with labeled categories (job-related or academic-related). A messy and complex dataset is also used to simulate real-world scenarios and test the robustness of the models.
* Preprocessing: Data cleaning, tokenization, and vectorization are performed to prepare the email text for model training.
* Modeling: Several machine learning models, including Logistic Regression, SVM, Naive Bayes, Random Forest, and Gradient Boosting, are trained and evaluated.
* Evaluation: Model performance is assessed using accuracy, precision, recall, and F1-score. Cross-validation and holdout set testing are conducted to ensure the models generalize well to new data.
* Hyperparameter Tuning: Different hyperparameters are tested to optimize model performance.


  

