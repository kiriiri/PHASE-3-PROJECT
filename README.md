## Predictive Insights for Reducing Customer Churn

## Project Overview<a name="project-overview"></a>
This a strategic initiative undertaken by SyriaTel, a prominent telecommunications company, to tackle the challenge of customer attrition. The main objective of this initiative is to uncover the intricate web of factors that contribute to customer churn and predict which subscribers are likely to discontinue their services. Armed with a wealth of customer data, ranging from demographics and subscription details to usage patterns and support interactions, SyriaTel is on a quest to unlock predictive insights. The ultimate goal is to empower SyriaTel with the ability to take proactive measures to retain at-risk customers and optimize their service offerings, thereby reducing revenue loss and enhancing overall customer satisfaction.

## Business Problem<a name="business-problem"></a>
### Stakeholder: SyriaTel Company
In a competitive telecom market, SyriaTel faces a critical business problem which is escalating customer churn rates, driven by undisclosed customer dissatisfaction and suboptimal service experiences. With an ever-expanding array of services and plans, the company is challenged to understand and predict why certain subscribers decide to leave. This surge in customer attrition not only impacts SyriaTel's revenue but also casts a shadow over its reputation. The business problem at hand is to proactively identify those customers at risk of churning by decoding the intricate blend of demographic, usage, and interaction data. SyriaTel aims to transform this challenge into an opportunity by deploying predictive insights to enhance customer retention, thereby securing a competitive edge in the telecommunications industry.

## Data Understanding<a name="data-understanding"></a>
The dataset for the SyriaTel customer retention project comprises an array of features that offer insight into customer behavior and its impact on churn. These features include geographic indicators like state and area code, historical account length, communication preferences such as voicemail messages, and usage patterns during different times of the day (day and evening minutes, calls, and charges). International and nighttime usage metrics are also recorded, along with customer service interactions and the crucial 'Churn' variable, which signifies customer disengagement. By delving into this dataset, SyriaTel aims to uncover predictive insights that will enable them to proactively address churn and enhance customer retention, ultimately strengthening their position in the telecommunications industry.


## Modeling<a name="modeling"></a>
In our telecom churn prediction project, we have harnessed a range of machine learning models which include:

1. Logistic Regression
2. DecisionTrees
3. Random Forest

## Conclusion<a name="conclusion"></a>
1. Key Churn Factors:

The analysis of the dataset columns reveals that several factors play a crucial role in understanding customer churn within SyriaTel.
"Number vmail messages" and "customer service calls" emerge as critical indicators of potential churn, suggesting that customer dissatisfaction and interactions with customer service significantly influence attrition.

2. Usage Patterns Impact Churn:

Features such as "total day minutes," "total day calls," and "total day charge" provide insights into customer usage patterns. High usage, especially in daytime, may lead to increased billing and dissatisfaction, contributing to churn.

3. Plan Choices Matter:

The availability of "international plan" and "voice mail plan" as binary features signifies that customers' plan choices can have a notable impact on churn.

## Recomendations<a name="recommendations"></a>
1. Customer-Centric Approach:

To mitigate the challenge of escalating churn rates, SyriaTel should adopt a customer-centric approach.
Focus on customer satisfaction, especially for those with a high number of "customer service calls." Provide prompt and effective solutions to address their concerns.

2. Transparency and Communication:

Enhance billing transparency and communication for customers with high "total day minutes," "total day calls," and "total day charge." This can help manage expectations and reduce dissatisfaction.

3. Plan Customization:

Enable customers to customize their plans, especially with respect to "international plan" and "voice mail plan." Providing flexibility can help align services with individual preferences, reducing the likelihood of churn.

4. Monitoring and Predictive Insights:

Continuously monitor the specified features and usage patterns to identify early signs of dissatisfaction and churn.
Implement predictive churn models based on these features. Machine learning models like logistic regression, decision trees, and Random Forest can help SyriaTel anticipate potential churn and take proactive measures to retain at-risk customers.

5. Feedback Mechanism:

Establish a feedback mechanism to collect input from customers who exhibit characteristics associated with churn. This feedback can be invaluable in pinpointing specific areas of dissatisfaction and driving targeted improvements.

5. Feedback Mechanism:

Establish a feedback mechanism to collect input from customers who exhibit characteristics associated with churn. This feedback can be invaluable in pinpointing specific areas of dissatisfaction and driving targeted improvements.

6. Strategic Decision-Making:

Use the insights from the dataset and predictive models to inform strategic decision-making. Optimize service offerings, align marketing strategies, and ensure SyriaTel remains competitive in the telecommunications industry.

## Dependecies<a name="dependecies"></a>
The analysis was conducted using Python with the following libraries:

1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. Sklearn
   
## Folder Structure<a name="folder-structure"></a>
|- ipynb_checkpoints

|- Data

     |-Telecom.csv

|- LICENSE

|- README.md
  
|- index.ipynb

## Installation<a name="installation"></a>

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/kiriiri/PHASE-3-PROJECT.git
   ```

2. Navigate to the project directory:

   ```bash
   cd PHASE-3-PROJECT
   ```

3. Install the required Python packages

## Usage<a name="usage"></a>

To use this project:

1. Open the Jupyter Notebook to explore the analysis, models, and visualizations.
2. Follow the instructions within the notebooks to run the code and generate predictions.

## License<a name="license"></a>

This project is licensed - see the [LICENSE](LICENSE) file for details.