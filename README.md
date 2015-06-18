# summarize_file
Python module with a function that takes various file formats within a directory and summarizes the included variables into one csv by providing filepath, dtype, range, std, etc.

The worker function is '''make_stats_dir()''' and it takes a directory name, the file type (including the'.' !!! like '.csv' ), and for .csv's it also takes an optional delimiter.

Requires pandas.
