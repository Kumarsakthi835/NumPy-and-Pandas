# 🐍 Python DA Assignment 1 – NumPy and Pandas

## 📌 Project Overview

This assignment focuses on performing data analysis using NumPy and Pandas.
The objective is to work with NumPy arrays for numerical computations, use
Pandas Series and DataFrame for data manipulation and analysis, and apply
indexing, slicing, filtering, and aggregation techniques on real-world
temperature and transaction datasets.

---

## 🎯 Assignment Objectives

- Work with NumPy arrays for numerical computations
- Use Pandas Series and DataFrame for data manipulation
- Apply indexing, slicing, filtering, and aggregation techniques
- Understand real-world data handling through temperature and transaction datasets

---

## 📂 Assignment Information

| Item | Details |
|------|---------|
| **Assignment Name** | Python DA Assignment 1 – NumPy and Pandas |
| **Module** | Data Analytics (DA) – Module 5 |
| **Topic** | NumPy Array Operations & Pandas Data Analysis |
| **Tool Used** | Google Colab |
| **Language** | Python 3 |
| **Libraries** | NumPy, Pandas |

---

## 🛠 Tools & Technologies

- Python 3
- Google Colab
- NumPy
- Pandas

---

## 📝 Tasks Completed

### 🔢 NumPy Array Operations

#### Task 1 – Create 1D NumPy Array
- Created a 1D NumPy array named temperatures_w1 for Week 1
- Values: [22.5, 25.3, 20.8, 23.4, 26.1, 24.8, 21.9]

#### Task 2 – Array Inspection & Properties
- Inspected shape, data type, and number of elements
- Shape: (7,) | dtype: float64 | Size: 7

#### Task 3 – Array Operations
- Converted temperatures from Celsius to Fahrenheit
- Found maximum, minimum, and mean temperatures

#### Task 4 – Array Slicing & Indexing
- Extracted first 3 days temperatures
- Extracted weekend temperatures (last 2 days)
- Extracted middle 3 days temperatures

#### Task 5 – Create 2D NumPy Array
- Created a 2D array with Week 1 and Week 2 temperature data
- Shape: (2, 7)

#### Task 6 – Inspect & Slice 2D Array
- Inspected shape, dtype, and total elements
- Extracted temperatures for each week
- Extracted weekend temperatures for both weeks

---

### 📊 Pandas Series

#### Task 7 – Create Pandas Series
- Created a Pandas Series named marks
- 5 student marks with custom indices (Rank1 to Rank5)

#### Task 8 – Series Indexing & Slicing
- Accessed mark using integer index position
- Retrieved top 3 ranks using loc accessor
- Retrieved 3rd rank using iloc accessor
- Applied boolean mask to filter marks greater than 90

#### Task 9 – Manipulating Series
- Modified Rank1 mark to 100
- Removed Rank5 entry from Series
- Computed CGPA by dividing each mark by 10

---

### 📋 Pandas DataFrame

#### Task 10 – Create DataFrame
- Created transactions DataFrame with 10 records
- Columns: TransactionID, ProductCategory, Region, Amount

#### Task 11 – Data Exploration
- Displayed head, tail, shape, column names, and data types
- Displayed ProductCategory and Amount columns
- Retrieved last 3 columns using iloc
- Filtered rows where Region is North and Amount > 200
- Found value counts for ProductCategory
- Found unique values in Region column
- Grouped by Region and calculated mean amount

#### Task 12 – DataFrame Manipulation
- Modified Amount for TransactionID 102 to 165
- Added Discount column (10% of Amount)
- Removed row with TransactionID 109
- Deleted Discount column

---

## 📸 Screenshots

### Task 1 – Create 1D NumPy Array
<img width="457" height="116" alt="image" src="https://github.com/user-attachments/assets/2b4234e2-cc0c-430d-afa3-92150587efaa" />


### Task 2 – Array Inspection & Properties
<img width="693" height="126" alt="image" src="https://github.com/user-attachments/assets/58be12ce-d0c9-4926-be07-1d2ca45db541" />


### Task 3 – Array Operations
<img width="609" height="222" alt="image" src="https://github.com/user-attachments/assets/b5fa91c9-84ab-44e6-8bf1-79aa539c1d29" />


### Task 4 – Array Slicing and Indexing
<img width="573" height="207" alt="image" src="https://github.com/user-attachments/assets/b566bfa0-2106-4971-9e72-e00df4c8d10c" />


### Task 5 – Create 2D Array
<img width="580" height="166" alt="image" src="https://github.com/user-attachments/assets/4bc1fc35-450c-4d04-a1ad-48b8fe21be8f" />


### Task 6 – Inspect and Slice 2D Array
<img width="463" height="284" alt="image" src="https://github.com/user-attachments/assets/bc2caf94-0b86-459a-8b4c-9a1ebadbab13" />


### Task 7 – Create Pandas Series
<img width="608" height="250" alt="image" src="https://github.com/user-attachments/assets/7e745745-2667-4d30-bf45-a75a39204ff0" />


### Task 8 – Series Indexing and Slicing
<img width="723" height="263" alt="image" src="https://github.com/user-attachments/assets/8d1c2683-d129-43c3-b405-f5f094910155" />


### Task 9 – Manipulating Series
<img width="383" height="206" alt="image" src="https://github.com/user-attachments/assets/0e80c5fa-3df4-4025-a136-d8da4a2fdb04" />
<img width="346" height="254" alt="image" src="https://github.com/user-attachments/assets/077026cd-61bc-4ca9-ba9b-13650c15f54c" />


### Task 10 – Create DataFrame
<img width="498" height="174" alt="image" src="https://github.com/user-attachments/assets/66ba4a79-4eed-4987-ad1e-28c17502c4ad" />
<img width="407" height="161" alt="image" src="https://github.com/user-attachments/assets/501ec314-682b-40ce-ae15-7eed2b08bd93" />


### Task 11 – Data Exploration
<img width="470" height="284" alt="image" src="https://github.com/user-attachments/assets/975b0cad-104b-46d1-a17f-c346e00932d4" />
<img width="599" height="220" alt="image" src="https://github.com/user-attachments/assets/f374650f-3cb3-431b-8ce5-e06cc9816f50" />
<img width="595" height="284" alt="image" src="https://github.com/user-attachments/assets/0960c5d9-3aaa-4df7-863e-b95a272272be" />
<img width="440" height="266" alt="image" src="https://github.com/user-attachments/assets/3653c07c-9106-47e0-be96-7c323bad6e28" />
<img width="524" height="73" alt="image" src="https://github.com/user-attachments/assets/63a1c273-9d51-4397-a9d6-deac4ef62d93" />


### Task 12 – DataFrame Manipulation

<img width="533" height="254" alt="image" src="https://github.com/user-attachments/assets/f8bf6311-6df0-4648-bbe2-b92e731435cf" />
<img width="366" height="170" alt="image" src="https://github.com/user-attachments/assets/8eaaaf6b-411f-43c4-bcbc-fd3fe72263f3" />
<img width="394" height="158" alt="image" src="https://github.com/user-attachments/assets/8f7d4b14-c255-4eed-a006-51c222928c3f" />
<img width="394" height="145" alt="image" src="https://github.com/user-attachments/assets/ed06ca5d-950b-4c70-b2d5-778476ca7cc4" />
<img width="374" height="149" alt="image" src="https://github.com/user-attachments/assets/a8254798-9112-4d15-befc-d44e6c7273b0" />




---

## 🔍 Key Concepts Used

| Concept | Description |
|---------|-------------|
| **np.array()** | Created 1D and 2D NumPy arrays |
| **shape, dtype, size** | Inspected array properties |
| **Celsius to Fahrenheit** | Applied formula conversion |
| **np.max(), np.min(), np.mean()** | Statistical operations on arrays |
| **Array Slicing** | Extracted subsets using indexing |
| **pd.Series()** | Created labeled Pandas Series |
| **loc, iloc** | Label and integer based indexing |
| **Boolean Mask** | Filtered data using conditions |
| **pd.DataFrame()** | Created structured dataset |
| **head(), tail(), shape** | Explored DataFrame structure |
| **value_counts()** | Counted category frequencies |
| **groupby()** | Grouped and aggregated data |
| **drop()** | Removed rows and columns |

---

## 💡 Key Insights

- Week 1 maximum temperature was 26.1°C and minimum was 20.8°C
- Week 2 temperatures were generally lower than Week 1
- Electronics was the most purchased product category (4 transactions)
- East region had the highest mean transaction amount (375.0)
- West region had the lowest mean transaction amount (190.0)
- North region had the most transactions (4 transactions)

---

## 🎓 Skills Demonstrated

- NumPy Array Creation and Operations
- Array Slicing and Indexing
- Numerical Computations using NumPy
- Pandas Series Creation and Manipulation
- DataFrame Creation and Exploration
- Data Filtering and Conditional Selection
- Data Aggregation using groupby()
- DataFrame Modification and Cleaning

---

## 👨‍💻 Author

**Kumar S**
- Data Analyst
- Python DA Assignment 1 – NumPy and Pandas
