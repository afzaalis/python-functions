# python-functions
fungsi
#example


def avrg(first, *rests):
    return (first + sum(rests)) / (1 + len(rests))

# Sample use, Putting values

print (avrg(1, 2))
print (avrg(1, 2, 3))
print (avrg(1,2,3,4))


OUTPUT:

1.5
2.0
2.5
