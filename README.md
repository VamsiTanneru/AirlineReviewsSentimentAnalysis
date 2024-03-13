# AirlineReviewsSentimentAnalysis

### Table of Contents
- [Business Understanding](#business-understanding)
- [Data Understanding](#data-understanding)
- [Screenshots of Visualizations/Results](#screenshots-of-visualizationsresults)
- [Technologies](#technologies)
- [Setup](#setup)
- [Research Questions](#research-questions)
- [Approach](#approach)

## Business Understanding
The Airlines Reviews Sentiment Analysis project aims to analyze customer satisfaction across various aspects of airline services. By examining sentiment scores derived from customer reviews, the project seeks to identify areas of improvement for airlines to enhance passenger experience and satisfaction.

## Data Understanding
The project utilizes a large dataset of customer reviews encompassing different aspects of airline services such as seat comfort, in-flight entertainment, food and beverages, cabin staff service, Wi-Fi connectivity, and ground services.

## Screenshots of Visualizations/Results


## Technologies
This project leverages the following technologies:
- Tableau: Tableau is used for data visualization and analysis, providing interactive and insightful visualizations.
- Python: Python is used for data preprocessing, statistical analysis, and machine learning tasks.
- VADER: VADER (Valence Aware Dictionary and sEntiment Reasoner) is used for sentiment analysis of textual data.
- TextBlob: TextBlob is used for natural language processing tasks including sentiment analysis.
- Pandas
- Matplotlib
- Seaborn
- Statistical analysis tools (e.g., Welch's T-test)
- Machine learning libraries

## Setup
To set up the project locally, follow these steps:

1. **Tableau Installation**: 
   - If you don't have Tableau Desktop installed, you can download and install it from the official Tableau website: [Tableau Desktop](https://www.tableau.com/products/desktop/download).

2. **Python Environment Setup**:
   - Make sure you have Python installed on your system. You can download Python from the official Python website: [Python Downloads](https://www.python.org/downloads/).
   - It's recommended to use a virtual environment for Python dependencies. You can create a virtual environment using `venv` or `conda`.
   - Activate your virtual environment:
     ```bash
     # For venv
     source <virtual_env>/bin/activate
     # For conda
     conda activate <virtual_env>
     ```
   - Install the required Python packages using pip:
     ```bash
     pip install -r requirements.txt
     ```

3. **Clone the Repository**:
   - Clone this repository to your local machine using Git:
     ```bash
     git clone https://github.com/your_username/your_repository.git
     ```

4. **Run the Code**:
   - Open the Tableau workbook (.twb) file using Tableau Desktop to explore the visualizations.
   - Run the Python scripts for data preprocessing, analysis, or any other tasks as needed.

5. **Explore the Project**:
   - Explore the Tableau visualizations and Python scripts to understand the project's analysis and insights.

## Research Questions
1. How do the sentiment scores generated from Vader and TextBlob change over the years among domestic and international flights? What can we make out of it?
2. What are the airlines that have a low sentiment generated from Vader among the domestic and international airlines? How can they improve their customers' experience?
3. What are the airlines that have a low sentiment generated from TextBlob among the domestic and international airlines? How can they improve their customers' experience?
4. How are the flights performing according to the satisfaction score given by the travelers for the departments that are crucial during a flight?
5. How are the flights performing according to the satisfaction score given by the travelers for the Ground Service department?

## Approach

The Airlines Reviews Sentiment Analysis project follows a structured approach to analyze customer satisfaction across various aspects of airline services. The process involves the following steps:

1. **Data Collection**: 
   - Gather a comprehensive dataset of customer reviews covering different aspects of airline services, including seat comfort, in-flight entertainment, food and beverages, cabin staff service, Wi-Fi connectivity, and ground services.

2. **Data Preparation and Cleaning**: 
   - Preprocess the raw data to remove noise, handle missing values, and standardize the format. 
   - Conduct exploratory data analysis (EDA) to gain insights into the distribution and characteristics of the data.

3. **Sentiment Analysis**:
   - Utilize VADER (Valence Aware Dictionary and sEntiment Reasoner) and TextBlob for sentiment analysis of textual data.
   - Assign sentiment scores to each review to quantify the polarity (positive, negative, or neutral) of the sentiments expressed.

4. **Statistical Analysis**:
   - Apply statistical techniques such as Welch's T-test to identify significant differences in satisfaction levels between domestic and international flights and across various service aspects.
   - Test the hypotheses to determine if the observed differences are statistically significant.

5. **Visualization and Interpretation**:
   - Use Tableau for data visualization and analysis, creating interactive and insightful visualizations.
   - Generate visual representations of the sentiment scores and statistical findings to facilitate interpretation and understanding.

6. **Recommendation Formulation**:
   - Based on the analysis results, formulate recommendations to assist airlines in enhancing their services.
   - Tailor recommendations to address specific areas of improvement identified through the analysis, such as seat comfort, in-flight entertainment, cabin staff service, and ground services.

7. **Project Iteration**:
   - Iterate on the analysis process as needed, incorporating feedback and refining the approach to improve the accuracy and relevance of the findings.
   - Continuously update and refine the recommendations based on new data and insights.

By following this structured approach, the project aims to provide actionable insights to airlines, enabling them to enhance customer satisfaction and improve the overall passenger experience.

