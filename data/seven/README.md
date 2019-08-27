This is the data for graphs with seven vertices. There are many such graphs so we broke the computation down into steps.

1. Find all possible extensions of 6 vertex (2,2)-tight graphs (raw7.json)
2. Split this data into separate files according to the degree sequence. Each file has the degree sequence in the filename. For example, 10_3_3_2_2_2_2.json contains data for all possible extensions of 6 vertex graphs with that degree sequence
3. eliminate graph isomorphs from each file. So set10_3_3_2_2_2_2.json consists of all (2,2)-tight seven vertex graphs with that degree sequence and with no isomorphs
4. search for correpsonding ORS's one degree sequence at a time. So ors10_3_3_2_2_2_2.json contains the data for irreducible (2,2)-tight torus graphs having that degree sequence.
