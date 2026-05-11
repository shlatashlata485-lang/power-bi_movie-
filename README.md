[اسم المشروع: Movie Industry Insights Dashboard]
Business Insights & Recommendations
Target Audience: R-rated (18+) movies show the highest engagement and voting rates. Recommendation: Prioritize the acquisition and promotion of mature-rated content to maintain current audience retention.
Duration vs. Quality: Highly-rated successful movies tend to be longer, with an average runtime of 2.5 hours.
Classic Revival: Movies from the 2000s hold the highest average ratings. Recommendation: Create "Classic Recommendations" lists to attract new subscribers who value quality cinema.
Marketing Strategy: Modern movies (Post-2010) show a 90% promotion success rate but require more intensive marketing campaigns to reach their full potential.
Technical Workflow
1. Data Cleaning (Power Query):
Handled missing values in "Revenue" and "Runtime" columns.
Filtered and standardized "Genres" and "Ratings" for consistency.
Created custom columns to categorize movies by decade (e.g., 2000s, 2010s).
2. Data Modeling & DAX:
Used advanced DAX measures to extract deep insights, such as:
Average Voting Rate: Average Voting = AVERAGE(Movies[Vote_Average])
Success Ratio: Created a measure to calculate the promotion success percentage (90% for modern movies).
Time-Based Analysis: Developed measures to compare performance across different eras.
