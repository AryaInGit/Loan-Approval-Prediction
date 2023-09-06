# Loan Approval Prediction with ML Models 👨‍💼📊🤖

### Introduction 🚀
Welcome to our Loan Approval Prediction Project! 🎉 In this ambitious endeavor, we set out to revolutionize the loan qualification process. Our mission? To harness the power of machine learning and data analysis to predict loan approval based on customer information. Buckle up as we take you on a fascinating journey through our project's key steps and discoveries.

### Data Exploration 🧐📈
Our adventure began with a deep dive into the dataset 🌊. We wanted to understand its secrets and uncover the intricate relationships between various features and the enigmatic target variable, Loan_Status.

#### Numerical Variables 📊📈
We embarked on a quest to unveil the numerical variables' mysteries - ApplicantIncome, CoapplicantIncome, LoanAmount, and Loan_Amount_Term. Armed with histograms and violin plots 📊🎻, we sought to unmask any hidden patterns, skewness, or outliers lurking within the data.

#### Correlation Analysis 🔍🔗
To decipher the complex web of relationships among numerical variables, we summoned the Spearman correlation matrix and conjured a heatmap. These arcane artifacts illuminated the bonds between these features, revealing their hidden connections.

#### Categorical Intrigue 🧩📊
Our exploration extended to the realm of categorical variables, where we uncovered tales of intrigue. With the magic of bar plots and box plots 📊📉, we unveiled the secrets of categorical-categorical and categorical-numerical relationships, unraveling the influences shaping loan approval.

#### Pie Chart Enigma 🥧🔍
To comprehend the distribution of loan approval statuses (Loan_Status), we forged a pie chart. This enigmatic artifact provided a visual feast, shedding light on the balance - or lack thereof - within the dataset.

#### Pairplot Revelations 📈🌟
A pairplot unveiled mesmerizing visual revelations, exposing the intricate dance between numerical variables and the elusive target variable (Loan_Status). These insights ignited our quest for feature importance.

### Data Preprocessing 🧰🧹
Before we could wield the magic of machine learning, we embarked on the arduous path of data preprocessing, preparing the dataset for our grand endeavor.

- **Loan_ID Exorcism:** We exorcised the Loan_ID column, recognizing its lack of significance in our predictive rituals, simplifying our data sorcery.

- **Missing Value Remediation:** In our quest for completeness, we encountered missing values in several columns, including LoanAmount, Loan_Amount_Term, and Credit_History. To mend these gaps, we applied the art of imputation.

- **One-Hot Encoding Incantation:** Transforming categorical variables into numerical incantations, we ensured their compatibility with our machine learning spells.

- **Outlier Exorcism:** The Interquartile Range (IQR) method helped us vanquish outliers, ensuring the robustness of our models.

- **Skewness Alchemy:** Skewed numerical distributions (e.g., ApplicantIncome, CoapplicantIncome, LoanAmount) were tamed with the power of the square root transformation.

- **Class Imbalance Harmony:** To restore balance to the force, we enlisted the RandomOverSampler, ensuring equitable representation of approval and rejection classes in our training data.

- **Normalization Enchantment:** We sprinkled Min-Max scaling to normalize feature values within the sacred range [0, 1], enhancing the potential of our chosen machine learning disciples.

### Model Evaluation 🧪📋
With our dataset meticulously groomed, we divided it into the realms of training (80%) and testing (20%). The time had come to summon our machine learning champions and assess their mettle:

- Decision Tree 🌳
- Random Forest 🌲
- Logistic Regression 📈
- Support Vector Machine 🤖
- K-Nearest Neighbors 🏘️
- Naive Bayes 📜

### Model Performance 🏆📈
The stars aligned, and the models revealed their accuracy scores:

- **Random Forest**, our champion, emerged victorious with an accuracy score of 95.56%, showcasing its unrivaled predictive prowess.

- **Decision Tree** proved a stalwart ally, boasting an accuracy of 84.44%, a testament to its effectiveness.

- **Logistic Regression**, while humble, still contributed with an accuracy of 71.11%, serving as a valuable member of our ensemble.

### Model Comparison 📊🔍
We cast the models into an arena of competition, where a bar chart illuminated their strengths, helping us identify the unrivaled prowess of the Random Forest.

### Model Fine-Tuning ⚙️🔧
Our quest for perfection led us to the realm of hyperparameter tuning, a quest for the perfect balance of power and precision. Through the rituals of grid search, we uncovered the hidden configuration that crowned our Random Forest as the ultimate champion.

### Conclusion 📝🤝
With our mission accomplished, we reflect on a journey filled with discovery and innovation. Our machine learning models, led by the indomitable Random Forest, have conquered the realm of loan approval prediction with an accuracy score of 95.56%. This project not only demonstrates the potential of machine learning in financial decision-making but also imparts valuable lessons in feature importance and data preprocessing.

