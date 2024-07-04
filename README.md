# **🚆 Train Passenger Data Analysis**</span>

##    📊 Data Cleaning and Identifying Patterns and Trends
          
###       Step-by-Step Process
-         Step 1: 📥 Data Reading
                Using the pandas module, I read the sample dataset which contains the train passenger report. This dataset includes various attributes such as age, sex,                   fare, etc.
-        Step 2: 🧹 Data Cleaning
                To ensure the dataset is clean and ready for analysis, I handled the null values using various functions in the pandas module:
                   ✏️ dropna(): Removed rows with null values.
                   ✏️ fillna(): Filled null values with specified values.
                   ✏️ median(): Replaced null values with the median of the column.
                   ✏️ bfill(): Used backward fill to replace null values.
-        Step 3: 📈 Line Chart Creation
                Using matplotlib, I created a line chart to visualize the relationship between age and fare values of the train tickets from the dataset.
-       Step 4: 📊 Bar Chart Creation
                Using matplotlib, I created a bar chart to visualize the relationship between sex and fare values of the train tickets from the dataset.
                
##     📈 Patterns and Trends Identified
From my analysis, I identified the following patterns and trends:
   - **💰 Age Group Spending**: The age group from 35 to 45 is spending significantly more on train fares.
   - **👨‍🦱 Gender Spending**: Males are using the train more frequently and paying higher fares than females.
            
##    🎯 Target Audience
Based on these insights, the male passengers in the 35 to 45 age group are identified as the target audience for train services. This group demonstrates             higher spending on train fares, making them a key demographic for marketing and service improvements.
