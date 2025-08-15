# stanford-open-policing-data-analysis

## AI Use

### Objective:

Learning how to use various polars and matplotlib functions and what their purpose was

### Examples

#### Polars
    
- understanding scan_parquet vs read_parquet and how to work with a lazyframe
- learning what a lazyframe is
- very early code was made with AI help such as:
    - lf.select(pl.col(col).unique()).collect()
    - search_true = temp.group_by('county_name').agg(pl.col('search_conducted_int').sum().alias('search_count'))
- as I went further into the analysis I understood what these complex functions were doing and how to efficiently use them so further code was written without any AI use
- questions such as:
    - "i have 2.6 gb of data, how do i only read in parts of it using polars"
    - "how much can i read in at a time without crashing my computer"
    - "how to collect only a certain number of rows"
    - "can i separate filters with commas"
    - "how can i say for all columns get rid of rows with null values"
    - "how do i sum all the true values of each county efficiently?"
#### Matplotlib:

- I didn't watch much AI, instead I watched a video to understand basic plots I could make
- when I got errors such as "array must be 2d" "bin must increase monotonically, when an array" I used AI to understand what they were saying and fixed my code accordingly

#### Report

- I used AI solely to fix any grammatical errors in my writing, however all of it was written without the use of AI.