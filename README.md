# Pandas DataFrame Examples

This repository includes Python code snippets that demonstrate various methods for creating Pandas DataFrames. The examples cover different approaches for constructing DataFrames from lists, dictionaries, and series.

## Code Snippets

```python
import pandas as pd

# Creating a DataFrame from a List of Lists
list_data = [["Ahmet", 50], ["Ali", 60], ["Yagmur", 70], ["Cinar", 80]]
df_list = pd.DataFrame(list_data, columns=['Name', 'Grade'])
print(df_list)

# Creating a DataFrame from a Dictionary
dict_data = {"Name": ["Ahmet", "Ali", "Yagmur", "Cinar"], "Grade": [50, 60, 70, 80]}
df_dict = pd.DataFrame(dict_data)
print(df_dict)

# Creating a DataFrame from a List of Dictionaries
dict_list_data = [
    {"Name": "Ahmet", "Grade": 50},
    {"Name": "Ali", "Grade": 60},
    {"Name": "Yagmur", "Grade": 70},
    {"Name": "Cinar", "Grade": 80},
]
df_dict_list = pd.DataFrame(dict_list_data)
print(df_dict_list)

# Creating a DataFrame from Series
s1 = pd.Series([3, 2, 0, 1])
s2 = pd.Series([0, 3, 7, 2])
data = {"apples": s1, "oranges": s2}
df_series = pd.DataFrame(data)
print(df_series)
  
"Feel free to explore the code snippets and modify them according to your needs. If you have any questions or feedback, please don't hesitate to reach out.

Happy coding! 🚀"
