# Student Performance Analysis – Python & Pandas Project

## 🎯 What I Built
For my first Python project in the justIT Data Skills Bootcamp, I analysed a dataset of student performance. I used the pandas library to load, clean, and analyse the data to uncover insights about student marks, class performance, and gender distribution.

#### Table of average marks per class
<img width="731" height="641" alt="student-data-analysis-insight" src="https://github.com/user-attachments/assets/8704f307-6d58-478c-b66f-215bd6edaf2d" />

## 💡 Key Things I Learnt
- **Loading Data with Pandas**: I learned the fundamental skill of loading a `.csv` file into a pandas DataFrame using `pd.read_csv()`.
- **Data Inspection**: I practised using essential functions like `.head()`, `.info()`, and `.describe()` to get a first look at the dataset's structure and summary statistics.
- **Data Cleaning**: This was a major focus. I learned how to identify missing values using `.isnull().sum()` and then decide on a strategy to handle them.
- **Data Analysis with `.groupby()`**: I used the powerful `.groupby()` function to aggregate the data and calculate metrics like the average mark for each class.

## 🔍 Top Insights
| Insight | Evidence | Educational Takeaway |
|---|---|---|
| Data quality is a real-world issue | The initial data inspection revealed missing values in the 'class' and 'gender' columns. | This highlights the importance of data cleaning as the first step in any analysis; insights from messy data can't be trusted. |
| There is a performance gap between classes | The analysis showed that different classes have different average marks, with 'Six' and 'Seven' performing higher than 'Four'. | This could prompt further investigation into factors like teaching methods or curriculum differences between the classes. |

#### Code used to detect missing values in the dataset
<img width="731" height="641" alt="student-data-cleaning-code" src="https://github.com/user-attachments/assets/8bc7ff2f-cba3-49aa-8b02-539f117b7b74" />

## 🛠️ Python Skills Demonstrated
- **Libraries**: pandas
- **File I/O**: `pd.read_csv()`
- **Data Inspection**: `.head()`, `.info()`, `.shape`, `.describe()`
- **Data Cleaning**: `.isnull()`, `.sum()`
- **Data Analysis**: `.groupby()`, `.mean()`, `.value_counts()`

## 🚀 How to Explore
1.  Ensure you have Python and the pandas library installed.
2.  Download the `student_dataset_notebook.ipynb` and the `student.csv` file.
3.  Place them in the same directory.
4.  Open and run the Jupyter Notebook to see the analysis step-by-step.

## 📁 Project Files
- `student_dataset_notebook.ipynb` - The Jupyter Notebook containing all the Python code and analysis.
- `student.csv` - The raw dataset used in the project.
- `screenshots/` - The screenshots of the project
- `README.md` - This guide.

## 🎓 Part of My Bootcamp Journey

## 🤔 If I Had More Time
- I would use a data visualisation library like Matplotlib or Seaborn to create charts (e.g., a bar chart of average marks) to make the insights more impactful.
- I would explore different methods for handling the missing data, such as filling it with the mode ('most frequent' value) instead of dropping the rows, to see how it impacts the final results.

---
*Week 6 of 8 – justIT Data Skills Bootcamp*
