# Interview-Experience

## Andela
### Technical interview (1 hr)
- Two Coding questions based on numpy array and pandas dataframe (30 min)
    1. Mutate 2d numpy array inplace with cutoff wherever there is value less than cutoff value
       - Use boolean indexing to find elements less than cutoff and replace them; array[array < cutoff] = cutoff
    2. We have a pandas dataframe with two column a and b. Return a new dataframe with those records where b = b_value alongwith other repeating value for column a.
       - filtered_df = df[df['b'] == b_value]
       - unique_a_values = filtered_df['a'].unique()
       - result_df = df[df['a'].isin(unique_a_values)]
- Explain projects and past experience in brief
- Theoretical questions on ML and DL fundamentals
  1. Difference between RNN and Feedforward neural network
  2. What does activation function do?
  3. What is stratified cross validation?
  4. What is SVM and it's working?
  5. Why ensembles have higher scores than individual models?
- Basics of database
  1. How to update big table/data in db?
  2. Disadvantages of indexes in db.
 
## Expedia
- R1: Coding, DS/Algo
- R2: Coding, ML/Data Problem Solving
- R3: System design, CI/CD, ML pipelines and Big Data
- R4: Team Fitment, Cultural Fitment, SDLC, Past Projects, Agile
