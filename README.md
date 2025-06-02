# Cleaned data by removing nan values using df.dropna,replaces MALE and female with Male and Female respectively
# Removed duplicate customer id by using df.duplicates(subset = 'customer_id',keep='first') to keep first column and rekove rest duplicate rows
# Reset Index using df.reset_index(drop = True) 
# USED  df.columns.str.strip().str.lower().str.replace(' ', '_') to remove spaves in-between,lower the words and cut extra space after every word
# Handles the every time format to dd-mm-yy format using pd.to_date_time with .dt.str('%d-%m-%y')
# AT last convert their datatypes like age from float to int etc.
