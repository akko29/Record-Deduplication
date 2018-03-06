# Record-Deduplication

# Python Libraries used:

 Pandas
 
 RecordLinkage

The Python Record Linkage Toolkit is a library to link records in or between data sources. The toolkit provides most of the tools needed for record linkage and deduplication. The package contains indexing methods, functions to compare records and classifiers. The package is developed for research and the linking of small or medium sized files

The term record linkage is used to indicate the procedure of bringing together information from two or more records that are believed to belong to the same entity. Record linkage is used to link data from multiple data sources or to find duplicates in a single data source. In computer science, record linkage is also known as data matching or deduplication (in case of search duplicate records within a single file).

# Indexing Method
The Blocking indexing method is used to make the pair of similar records. To run the code on different dataset just replace the column names #block_class = rl.BlockIndex(on=["column names"]) in the following line of the code.

# Compare Records

The comparison between data and record pairs is done with the help of record linkage compare class. After comparing, the indexes of the matched data is return.

So, omit the indexed returned from the dataset provided and write the output in the file.

