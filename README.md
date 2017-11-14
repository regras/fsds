# FSDS
Fast Similarity Digest Search

The FSDS is a similarity digest search strategy aiming to perform queries efficiently with approximate matching tools, more especifically with TLSH (https://github.com/trendmicro/tlsh).

For more information about this strategy, see paper: Fast Similarity Digest Search: A new strategy for performing queries efficiently with approximate matching.

#Running FSDS (linux)

1. Install the TLSH tool.
2. Compile the source code provided here (soon).

#Performing queries

1. Create the TLSH digests from all reference list objects and store them in a file
2. Execute FSDS
3. Choose the option to insert the reference list.
4. Then, select the mode you want to query and type the object path you want to search for.
