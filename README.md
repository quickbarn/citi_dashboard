## READMe for tableau_challenge

### Data from: [Citi Bike Data](https://www.citibikenyc.com/system-data)

#### 2017-2020 (September)

- re-name columns from months Jan - Mar 2017 to match other columns from other years.
  - `df.columns`
- Concat all month files together. 
  - `pd.concat([df,df2])`
- Write the final to csv, do not push up. 
  - `df.to_csv('path', index=False)`
  - Keep locally for use in Tableau.
- Run Concat.ipynb for final CSV if needed

