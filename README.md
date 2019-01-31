# Personal-Identifying-Information-Checker

Excel based tool to identify if certain types of Personal Identifying Information exists within Excel files (e.g. Name, DOB, Addresses)

On the front sheet, there is a set of option boxes for the different data types that can be included in the search.

If a data type is set to include, it will be searched for in the data. If it is set to exclude, it will not be searched for. 
This is to offer options for speed of processing, especially when looking at large data files.

It also offers the options to run the tool in batches on large files. When you run a new search, if there are already results in the sheet the user is prompted to choose to replace previous results or not. If you choose not to replace, you can continue to build up the results.

The tool has two main elements; a regex search and a corpus search. The regex search is used when there is a pattern to look for in the data – e.g. National Insurance Number. The corpus search is for data types that do not follow a pattern, but where a list of pre-defined possible outputs can be used as a search criteria – e.g. a person’s name. 

For further details, please see the word document (Notes)
