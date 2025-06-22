tuples_list = [ (1, "a"), (2, "b"), (3, "c"), (1, "d") ]  
target_set = {1, 3}

filtered = [t for t in tuples_list if t[0] in target_set]
print(filtered)
