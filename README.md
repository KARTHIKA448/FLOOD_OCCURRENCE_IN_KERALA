The repository "FLOOD_OCCURENCE_IN_KERALA" contains 5 files:
         1. Kerala.csv: dataset used for analysis in Jupyter notebook
         2. KERALA_FLOOD: data set used for analysis in PowerBI
         3. FLOOD_OCCURENCES_IN_KERALA: analyzed Jupyter notebook
         4. FLOOD_OCCURENCES_IN_KERALA: analyzed visuals on power bi
         5. Screenshot of dashboard created in PowerBI
         6. Screen shot of models
         
The 'kerala.csv' dataset tells us about the monthly rainfall data from 1901 to 2018 for the Indian state of Kerala. Kerala is one of the few states that is usually badly hit by monsoons every year. The dataset comprises monthly rainfall measurements in millimeters for each year, enabling us to assess the variability and intensity of precipitation throughout the monsoon season. Furthermore, the annual rainfall summaries provide insights into the overall climatic conditions and potential deviations from the long-term average.

Problem statement: 
      The challenge of predicting floods using historical rainfall data. The importance of this task for disaster management and mitigationTaskGoal: Predict whether a flood will occur based on rainfall data.Keeping different conditions in rainfall scenarios (conditional probability) helps understand the rate of flooding.
      
Objective:
         Develop a predictive model using machine learning techniques.Evaluation Metric: Specify the evaluation metric (e.g., accuracy, precision, recall, F1-score) for assessing model performance.Flooding is a natural disaster that poses significant challenges to communities and regions worldwide. The ability to predict and anticipate floods is crucial for effective disaster management and mitigation efforts. Historical rainfall data serves as a valuable resource for developing predictive models that can help identify areas at risk of flooding. The state of Kerala, situated in the southwestern part of India, is known for its diverse landscape and rich biodiversity. However, Kerala also faces the recurring challenge of floods during the monsoon season, which often lead to significant human and economic losses. To address this issue, it is essential to understand historical rainfall patterns and their correlation with flood occurrences.
         
This project serves as a comprehensive exploration of Kerala's historical rainfall data with the help of the dataset "kerala.csv,"  aiming to uncover insights that contribute to more effective flood prediction and disaster preparedness strategies.

The data contains 32561 instances with the following attributes:
            'SUBDIVISION' : Represents the geographical subdivision associated with the data.
            'YEAR' : represents the calendar year for which the data is recorded.
            'JAN', 'FEB', 'MAR', 'APR', 'MAY', 'JUN', 'JUL','AUG', 'SEP', 'OCT', 'NOV', 'DEC' : Monthly rainfall data for each respective month.
            ' ANNUAL RAINFALL' : Represents the total annual rainfall for the given year.
            'FLOODS' : a binary variable indicating the occurrence of floods.
                        "YES" indicates that floods occurred.
                        "NO" indicates the absence of floods.
                        
Steps involved: In Jupyter's notebook:
                                    LOAD THE DATASET
                                    EXPLORE THE DATASET
                                    EDA 
                                    CONDITIONAL PROBABILITY 
                                    MODEL IMPLEMENTATION (HYPERPARAMETER TUNNING)
                                    EVALUATION
                                    CONCLUSION

IN POWER BI
            Load the data.
            Create visualisations.
            Arrange visualisations.3.Add filters.
            Add text and text boxes.
            Save the file (extension: "pbix").
            

Conclusion of the Analysis 

               Rainfall data plays a crucial role in flood prediction models, with models like Logistic Regression, Support Vector Machine (SVM), K Nearest Neighbors (KNN), and Random Forest demonstrating high accuracy, precision, recall, and F1 scores. These models can be used to calculate conditional probabilities of flooding, particularly for rainfall exceeding 500mm. The results can be visually presented, validated, and refined using historical flood events and observations. The insights can be used to support decision-making processes related to flood preparedness, response planning, and risk mitigation strategies. The analysis underscores the importance of rainfall data in flood prediction, as models trained on it can distinguish between flood and non-flood events. Future research should explore incorporating additional features, advanced modeling techniques, real-time data integration, and regional adaptation to account for geographical variations in flood dynamics and response strategies.
