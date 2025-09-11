## Score: 20/20

### Section 1: Using SQL and Python in Snowflake

All good. Just a note that you don't have to specify `use database MOVIES_5740` in each SQL cell.

### Section 2: Maniuplating Dataframes

* You used a design pattern where you created your manipulation function as a lambda and then applied it the data frame. That obviously works great, but I want to share another, more natural pattern in Pandas:

```python
df.loc[df["STORE_ID"] % 2 == 0], "EMAIL"] = "joe.person@wustl.edu"
```

This is preferred because the `.apply()` operator in Pandas is not vectorized whereas `.loc()` is. Here's an article that describes this in more detail. https://towardsdatascience.com/speed-up-pandas-code-with-numpy-fdee76210794/

### Section 3: Visualizations

These are good visualizations. Feel free to branch out and try using Streamlit's built-in visualization libraries and Seaborn, too.

### Section 4: Analysis

When I look at the values, the difference in rental rates seems to be very small if at all. I think most people would guage it the other way - they look roughly the same.

### Section 5: Analysis

Nice analysis here.
