
def upper_triangle_with_for(n):
    for i in range(n, 0, -1):
        stars = " "
        for j in range(i):
            stars = stars +  "* "
    
        print(stars)
