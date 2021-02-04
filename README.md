# CS-587-DBImplem
Project Part-1:
We chose option-1 for the project
System-1: PostgreSQL
System-2: Big Query

As stated in the Wisconsin Benchmark paper, the original benchmark has tree relations: onkup, tenkup1, tenkup2. There differences are:
Onekup means there are 1000 tuples on the table.
Tenkup1 and tenkup2 have 10000 tuples respectively.
Where their schema in the table are as follows:
13 integer attributes.
3 52-byte string attribute
Onekup.csv, tenkup1.csv and tenkup2.csv are in the data folder and dataGenerator.py is the script to generate data

Loaded data into big query and postgres GCP.
