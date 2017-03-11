**1. Check jth bit of i is set or not:**

    i & (1 << j) > 0


**2. Check if number is power of 2:**

    x && (x & -x) == x

    x && !(x & (1 - x))

**3. Count number of 1's:**


    while(n) {
        n = n & n - 1;
        count++;
    }
