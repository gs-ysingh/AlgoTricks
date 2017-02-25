**1. Iterate single dimensional matrix as two-dimensional matrix:**

    for (int i = 0; i < n; i++) {
	    for (int j = 0; j < m; j++) {
            System.out.println(grid[i*m+j]);
        }
    }
**2. Remove duplicates:** Put all the items in Hash Set

**3. Check if you are getting same result after applying a operation on every element on array:** Put the value after operation in Hash Set and check if hashSet.size() == 1