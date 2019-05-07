
PatentCitation.txt

The patent citation data set contains citations from U.S. patents issued between 1975 and 1999.
It has more than 16 million rows and the first few lines resemble the following.
The data set is in the standard comma-separated values (CSV) format, with the first line a description of the columns.
The first column is the CITING patent and the second column is the CITED patent.
Each of the other lines record one particular citation. The file is sorted by the citing patent.



PatentDescription.txt

The other data set we use is the patent description data.
 It has the patent number, the patent application year, the patent grant year, the number of claims,
 and other meta- data about patents. Look at the first few lines of this data set.
 It’s similar to a table in a relational database, but in CSV format.
 This data set has more than 2.9 million records. As in many real-world data sets, it has many missing values.
 The first row contains the name of a couple dozen attributes, which are meaningful only to patent specialists.

"PATENT","GYEAR","GDATE","APPYEAR","COUNTRY","POSTATE","ASSIGNEE", "ASSCODE","CLAIMS","NCLASS","CAT",
"SUBCAT","CMADE","CRECEIVE", "RATIOCIT","GENERAL","ORIGINAL","FWDAPLAG","BCKGTLAG","SELFCTUB", "SELFCTLB",
"SECDUPBD","SECDLWBD"


  PATENT: Patent number
   GYEAR: Grant year
   GDATE: Grant date, given as the number of days elapsed since January 1, 1960
 APPYEAR: Application year (available only for patents granted since 1967)
 COUNTRY: Country of first inventor
 POSTATE: State of first inventory (if country is U.S.)
ASSIGNEE: Numeric identifier for assignee (i.e., patent owner)
 ASSCODE: One-digit (1-9) assignee type. (The assignee type includes U.S. individual, U.S. government, U.S. organization, non-U.S. individual, etc.)
  CLAIMS: Number of claims (available only for patents granted since 1975)
  NCLASS: 3-digit main patent class