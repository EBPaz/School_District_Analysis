# pandas-challenge
dvasquez - Learning Assistant, helped rectify an error in .value_counts that I couldn't resolve by googling. He shpowed me the difference between .unique and .unique() for my data type and helped me correct my answer for the count of unique schools: 

Liang, (lyam) on Slack, the Learning Assistant, helped me re-configure my code to be able to do math to get the budget per student. I was stuck with using the groupby function without any aggregation function on the end. He helped me develop the .max()["budget"] portion of my code.

Monali, monalipatel19 on Slack, the Learning Assistant, helped me go back and re-calculate my School Types code to find the types per school. originally, I had just counted them as in an array and when I got to making my dataframe, that obviously wouldn't work. She helped me switch from just a school type count to --school_type = school_data.set_index(["school_name"])["type"] --

Classmate, Tahseen, shared a change she had to make to her pd.cut code when creating the bins for the Scores by School Spending dataframe. She says she was helped via tutor with this as well. This was discussed in our own zoom study group we created. The data being input for had to come from a higher up data reference. I used "per_school_capita" as the data marker for the "Per Student Budget" column.