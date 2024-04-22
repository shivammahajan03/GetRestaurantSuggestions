# GetRestaurantSuggestions
Extracting Student Survey Data regarding favorite restaurants
1. Data Source : Textual survey responses from students.
2. Extraction : Using a large language model (LLM), extract relevant information like student name, favorite food, favorite restaurant, and monthly spending on eating out.
3. Restaurant Recommendations : Based on student preferences, suggest restaurants with the help of LLM model.
4. Data Storage : Store the extracted data in a Pandas DataFramefor easy analysis and manipulation.

In this project, I am trying to first create a Dataframe out of the textual submissions of survey responses by the students where they mention about their favourite food, restaurant and total expenses on food over a period of a month in a particular city. Based on the textual responses, I am using OpenAI to extract the data in a structured format and adding it into a DataFrame of Pandas. Based on the extracted data, then I will try to create a suggestion for the restaurant in their city where their favourite dish is also served.

FlowChart Explanation of the Project output: 

![Project 1 Workflow](https://github.com/shivammahajan03/GetRestaurantSuggestions/assets/152625180/532af148-5ebc-4ea8-b516-3ccdced8f6ae)

