# DataStorm-3.0
Weekly Sales Predictions for DataStorm 3.0 Contest 2022

Data Sources
You are provided with the following data source files to develop a data analytics solution.
1. Training dataset – Historical item sales dataset consists of 194 items from 4 different categories with daily sales in quantity units collected through transactions for 5 months. (train-data.csv) 
      a. CategoryCode: The items are classified into 4 different categories; this column refers to its code.
      b. ItemCode: An identifier for each item
      c. DateID: The date for the respective sales value. The time period starts from 1st October 2021 to 13th February 2022.
      d. DailySales: Sales value in quantity units for the respective item on the given date.
2. Validation dataset – Similar to training dataset, for specific items with weekly sales in quantity units for the 4 weeks from 14th February to 13th March 2022 (validation_data.csv)
      a. CategoryCode: The items are classified into 4 different categories; this column refers to its code.
      b. ItemCode: An identifier for each item (only selected items are present in the validation_data.csv)
      c. Week: The time period starts from 14th February to 13th March (Monday to Sunday). The weeks are as follows:
          i. w1: 14th February 2022 – 20th February 2022
          ii. w2: 21st February 2022 – 27th February 2022
          iii. w3: 28th February 2022 – 6th March 2022
          iv. w4: 7th March 2022 – 13th March 2022
      d. WeeklySales: Sales value in quantity units for the respective item for the given week.
3. Testing dataset – You are required to test your solution using test_data.csv. Final weekly sales for the next 4 weeks should be submitted in a CSV format with 
columns.
      a. CategoryCode: The items are classified into 4 different categories; this column refers to its code.
      b. ItemCode: An identifier for each item (only selected items are present in the validation_data.csv)
      c. Week: The time period starts from 14th February to 13th March. The weeks are as follows:
            i. w1: 14th February 2022 – 20th February 2022
            ii. w2: 21st February 2022 – 27th February 2022
            iii. w3: 28th February 2022 – 6th March 2022
            iv. w4: 7th March 2022 – 13th March 2022
      d. PredictedSales: You are required to predict the sales value in this column, in quantity units
