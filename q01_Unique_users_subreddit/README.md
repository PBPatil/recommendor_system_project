# No. of unique users and subreddits

Hello folks, this assignment will be comprising of intial data exploration part as we move further we would gather much insights.

## Write a function `Unique_users_subreddit()` that:
* Computes the length of unique users and unique subreddits.
* First load the *zip* file from the **data** folder using the *read_csv* method of pandas. Use a parameter *compression = "zip"* for the same.
* Makes use of `unique` inbuilt function which extracts unique values of subreddits and users. 

### Parameters:

| Parameter | dtype | argument type | default value | description |
| --- | --- | --- | --- | --- | 
| path | str | compulsory |  | file path of the subreddit interaction dataset |


### Returns:

| Return | dtype | description |
| --- | --- | --- |
| data | pandas dataframe | subreddit dataset |
| variable1 | int | total no. of unique reddit users |
| variable2 | int | total no. of unique subreddits  |
