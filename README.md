# r-pir-distribution

Project to randomly select counties for students for public information requests (or whatever purpose.) Idea is each student would one of the most populous counties, then a a number of smaller counties selected randomly.

- `01_counties_get_data.Rmd` gets the county populations from the census.
- `02_counties_make_list.Rmd` makes to "top" and "small" counties list, based on the number of students.

## Published notebook

- [Get the data](https://utdata.github.io/r-pir-distribution/01_counties_get_data.html)
- [Make the list](https://utdata.github.io/r-pir-distribution/02_counties_make_list.html)

## Download the CSVs based on current settings

These will be split based on the most recent running and `numb_students` setting.

- [large_counties.csv](https://github.com/utdata/r-pir-distribution/blob/master/data/large_counties.csv?raw=true)
- [small_counties.csv](https://github.com/utdata/r-pir-distribution/blob/master/data/small_counties.csv?raw=true)
