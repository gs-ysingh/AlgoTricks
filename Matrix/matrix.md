**1. Iterate single dimensional matrix as two-dimensional matrix:**

    for (int i = 0; i < n; i++) {
	    for (int j = 0; j < m; j++) {
            System.out.println(grid[i*m+j]);
        }
    }
**2. Remove duplicates:** Put all the items in Hash Set

**3. Check if you are getting same result after applying a operation on every element on array:** Put the value after operation in Hash Set and check if hashSet.size() == 1 or you sum all the element and check if equal to 1 => sum == 1

**4. How to get left diagonal of element in matrix:** 

r = 0;
c = 0;

    if(row > col) {
    	r = col - row;
    }
	if(col > row) {
    	c = col - row;
    }
then you increase r and c

**5. How to get right diagonal of element in matrix:** 

    r =  0; 
    c = N - 1;
    
    if(row + col < N) {
    	c = Math.min(N - 1, row+col);
    }
    else {
    	r = row + col % N - 1;
    }
	
	then you increase row and decrease column;
