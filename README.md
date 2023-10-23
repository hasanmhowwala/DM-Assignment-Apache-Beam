1. Apache Beam : Composite tranformation : Input Dataset : Transactions.csv
   The output file represents data in following format. ------> (('UserID', 'Category'), total_amount)
   Colab Link : https://colab.research.google.com/drive/18HDGabFuejAgql_CbpSWryE34b2hC6ki?usp=sharing

2. Apache Beam : Pipeline IO : Input Dataset : fotball_mathes.csv
   The Apache Beam pipeline reads the match records from the input CSV file named football_matches.csv, processes them to count the number of matches played by each team, and writes the 
   results to an output CSV file 
   named team_match_counts.csv.
   The output CSV file contains the aggregated results of the number of matches played by each team. Each record in the output file has the following columns:

   TeamName: The name of the football team.
   MatchCount: The total number of matches played by the team (as a home team or away team).
   Colab link : https://colab.research.google.com/drive/1LKxd1et35uZqj9rs1KVLXCbXLaAI21pt?usp=sharing

3. Apache Beam : Pardo Function : Input Dataset: restaurant_orders.csv
   Apache Beam Pipeline: ParDo Transformation
   The Apache Beam pipeline performs a ParDo transformation to process the input dataset. The transformation involves the following steps:

   Read from CSV: The pipeline reads the restaurant orders from the CSV file.
   Extract and Format: Extracts necessary columns, formatting them into a dictionary for further processing.
   Extract MenuItem and TotalPrice: A custom DoFn function is used to extract the menu item and total price from each order.
   Sum by MenuItem: The total sales for each menu item are aggregated.
   Output: menu_item_sales
   The output consists of text files containing the aggregated results, where each record represents:

   MenuItem: The name of the menu item.
   TotalSales: The total sales for that menu item, calculated as the sum of the TotalPrice for each occurrence of the menu item in the orders.
   The output provides a summarized view of the total sales for each menu item, allowing for an analysis of the restaurant’s sales performance per menu item.
   Colab Link : https://colab.research.google.com/drive/1hOqlTe7_wnKNmDrWHq-BsSuLHzurMKyT?usp=sharing

5. 
   









