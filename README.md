# Assignment-7
Open In Colab

# Create a tuple
tup = (1, 2, 3, 4, 5)

# Length
print("Length:", len(tup))

# Concatenation
tup2 = (6, 7)
print("Concatenation:", tup + tup2)

# Repetition
print("Repetition:", tup * 2)

# Membership
print("Is 3 in tuple?", 3 in tup)

# Iteration
print("Elements:")
for i in tup:
    print(i)
     
Length: 5
Concatenation: (1, 2, 3, 4, 5, 6, 7)
Repetition: (1, 2, 3, 4, 5, 1, 2, 3, 4, 5)
Is 3 in tuple? True
Elements:
1
2
3
4
5

tup = ('spam', 'Spam', 'SPAM!')

# Indexing
print("tup[2]:", tup[2])

# Negative Indexing
print("tup[-2]:", tup[-2])

# Slicing
print("tup[1:]:", tup[1:])

# Iteration
print("Using loop:")
for i in tup:
    print(i)
     
tup[2]: SPAM!
tup[-2]: Spam
tup[1:]: ('Spam', 'SPAM!')
Using loop:
spam
Spam
SPAM!

tup = (10, 20, 30)

# Trying to change value (will give error)
# tup[0] = 100   ❌ Not allowed

print("Original tuple:", tup)

# Deleting entire tuple
del tup

# After deletion
print("Tuple deleted")
# print(tup) → This will give error
     
Original tuple: (10, 20, 30)
Tuple deleted

tup = (5, 2, 9, 1, 7)

# Length
print("Length:", len(tup))

# Maximum
print("Max value:", max(tup))

# Minimum
print("Min value:", min(tup))
     
Length: 5
Max value: 9
Min value: 1
