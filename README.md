# Interview-Experience

## Andela
### Technical interview (1 hr)
- Two Coding questions based on numpy array and pandas dataframe (30 min)
    1. Mutate 2d numpy array inplace with cutoff wherever there is value less than cutoff value
       - Use boolean indexing to find elements less than cutoff and replace them; array = np.array([[], []), array[array < cutoff] = cutoff
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
### Client interview 

## Expedia
- R1: Coding, DS/Algo
- R2: Coding, ML/Data Problem Solving
- R3: System design, CI/CD, ML pipelines and Big Data
- R4: Team Fitment, Cultural Fitment, SDLC, Past Projects, Agile

## Nagarro
### Online assessment (Mettl)
- Aptitude Question (30 questions in 20 mins)
### Technical Round 1 (Face to Face in office)
- What challenges you have faced in a project and steps taken for it?
- Explain how transformers and llm works and what is the special about it?
- Explain different ways of word embedding and what's the difference between TFIDF and Word2VEC with it's working.
- What is p-value and it's significance.
- When to use Z-test and t-test?
- How linear regression works and which metric need to use in which case?
- How adjusted R2 square works and what is the purpose of using it?
- When to use Precision and Recall?
- There are four models - Linear Regression, Polynomial Regression, Random Forest. Target outcome lies between 0-5. Which model can generate prediction beyond 5?
- Write a SQL query and pandas code also to find the first and last purchase date on which customer made purchase. There are 3 columns in a table - Cust ID, Purchase date, Store ID. I wanted to have four columns in output like Cust ID Store ID combo as well as first transaction date and last purchase date customer has made.
