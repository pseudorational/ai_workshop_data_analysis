# Baby Names

The dataset contains U.S. baby name counts from Social Security records, with one file per birth year from 1880–2025. The year is given in the filename (for example, yob2025.txt).

Each file is comma-separated with no header. Each row contains:

- **Name:** Given name.
- **Sex:** F = Female, M = Male.
- **Count:** Number of births recorded with that name and sex in that year.

Only names with at least 5 occurrences are included for privacy. Rows are sorted by sex, then by count from highest to lowest.
