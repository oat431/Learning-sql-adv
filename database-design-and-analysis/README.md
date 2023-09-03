# Database design and analysis

- ER, EER Diagram
- Normalization
- Denormalization
- Optimizing
- Set Theory

## Normalization
- UNF: unnormalized form -> unique rows or no duplicate records)
- 1NF: first normal form -> columns cannot contain relations or composite values
- 2NF: sencond normal form -> attribute depend on the whole of every key
- 3NF: third normal form -> attribute depend only on cadidate keys
- EKNF: elementary key normal form -> every non-trivial functional dependency either begins with a superkey or ends with and elementary prime attribute
- BCNF: boyce-codd normal form -> every non-trivial funcational dependency begins with a superkey
- 4NF: fourth normal form -> every non-trival multivalued dependecy begins with a superkey
- ETNF: essential tuple normal form -> every join dependency has a superkey component
- 5NF: fifth normal form -> every join dependency has only superkey components
- DKNF: domain-key normal form -> every constraint is a consequence of domain constraints and key constraints 
- 6NF: sixth normal form -> every join dependency is trivial
