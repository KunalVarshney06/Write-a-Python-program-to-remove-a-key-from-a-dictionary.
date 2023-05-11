# Write-a-Python-program-to-remove-a-key-from-a-dictionary.
my_dict = {"a": 1, "b": 2, "c": 3, "d": 4, "e": 5}
key_to_remove = "c"
if key_to_remove in my_dict:
del my_dict[key_to_remove]
print("The key", key_to_remove, "has been removed from the dictionary")
else:
print("The key", key_to_remove, "is not present in the dictionary")
print("The updated dictionary is:", my_dict)
