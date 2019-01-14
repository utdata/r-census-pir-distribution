# r-census-pir-distribution

Project to randomly select counties for students for public information requests (or whatever purpose.) Idea is each student would one of the most populous counties, then a a number of smaller counties selected randomly.

- `01_get_data.Rmd` gets the county populations from the census.
- `02_make_list.Rmd` makes to "top" and "small" counties list, based on the number of students.