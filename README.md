# total_comprehension.py

my_numbers = [1, 2, 3, 4, 5, 6, 7]
my_numbers100 = []
print("--------------")
print("ORIGINAL LIST:", my_numbers)
print("--------------")
print("TOTAL COMPREHENSION...")
print("--------------")

for i in my_numbers:
    my_numbers100.append(i * 100)

print("MAPPED LIST: ", my_numbers100)
print("--------------")

filtered_list = []

for x in my_numbers:
    if x > 3:
        filtered_list.append(x)
print("FILTERED LIST W/ MATCHES:", filtered_list)

print("--------------")

filtered_list2 = []

for x in my_numbers:
    if x > 8:
        filtered_list.append(x)

print("FILTERED LIST W/O MATCHES: ", filtered_list2)
print("--------------")

mapped_and_filtered_list = []

mapped_and_filtered_list = [x * 100 for x in my_numbers if x > 3]

print("MAPPED AND FILTERED LIST: ", mapped_and_filtered_list)
print("--------------")

# TODO: write python code here

