# tech-test

Attached codes:
1. eda: The code to perform few initial exploratory database analyses like schema, histograms of table columns etc.
2. test: The code to perfom the analyses on BC patients given as questions for the tech test.

Note:
There were certain entries in the diagnosis table for which the dod was before the diagnosis dates and few in the biomarker table with dod before test dates. 
After removing such cases the modified tables have been written to a new database "techTest_mod.db" in the script "eda".
The analyses in "test" have been performed on "techTest_mod.db". 
