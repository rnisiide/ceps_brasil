This is a small automation built in Python.

The challenge came from a transportation company that had to insert their rates according to ZIP code and neighbourhoods in Brazil. 
Their main issue is that neighbourhoods do not follow a linear pattern for their ZIP Codes, and their software would detect duplicates when adding the first and last codes for a specific neighbourhood.
So the script analyses each individual ZIP code in linear order and groups by range in each neighbourhood.
