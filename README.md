## READMe for tableau_challenge

### Data from: [Citi Bike Data](https://www.citibikenyc.com/system-data)

#### 2017-2020 (September)

- re-name columns from months Jan - Mar 2017 to match other columns from other years.

  - `df.columns`

- Concat all month files together. 

  - `pd.concat([df,df2])`

- Write the csv, do not push

  - `df.to_csv('path', index=False)`
  - Run Concat.ipynb for combined CSV if needed 

- Reformat Dtypes as necessary

  - Read in concat CSV
  - Reformat years as necessary (if birth year analysis desired)

-  Write the final csv, do not push

  - `df.to_csv('path', index=False)`
  - Keep locally for use in Tableau.
  - Run dtypes.ipynb for Final1.0 csv 

- Utilize Final1.0.csv in Tableau

  

