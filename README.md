# Data-Structures-and-Algorithms-Projects-Patika.DEV

# Project 1

    [22,27,16,2,18,6]

Answer a)

    Step 1: [22,27,16,2,18,6] //Since 22 is already lesser than 27 no sorting was done.
    Step 2: [22,16,27,2,18,6] // 27 to 16 places changed.
    Step 3: [16,22,27,2,18,6] // 22 to 16 places changed.
    Step 4: [16,22,2,27,18,6] // 27 to 2 places changed.
    Step 5: [16,2,22,27,18,6] // 22 to 2 places changed.
    Step 6: [2,16,22,27,18,6] // 16 to 2 places changed.
    Step 7: [2,16,22,18,27,6] // 27 to 18 places changed.
    Step 8: [2,16,18,22,27,6] // 22 to 18 places changed.
    Step 9: [2,16,18,22,6,27] // 27 to 6 places changed.
    Step 10: [2,16,18,6,22,27] // 22 to 6 places changed.
    Step 11: [2,16,6,18,22,27]  // 18 to 6 places changed.
    Step 12: [2,6,16,18,22,27]  // 16 to 6 places changed.


  Answer b)

    Step 1: 1
    Step 2: 2
    Step 3: 3
    .
    .
    Last Step: n

    Sum: (n*(n+1)/2) --> O(n^2)


 Answer c)
 
        Worst case


Second Question        

    [7,3,5,8,2,9,4,15,6]

   Answer 
      
      Step 1: min = 2 -> swap 2 and 7. [2, | 3,5,8,7,9,4,15,6]
      Step 2: min = 3 -> change nothing. [2,3, | 5,8,7,9,4,15,6]
      Step 3: min = 4 -> swap 5 and 4. [2,3,4, | 8,7,9,5,15,6]
      Step 4: min = 5 -> swap 5 and 8. [2,3,4,5, | 7,9,8,15,6]



# Project 2

Merge Sort

      [16,21,11,8,12,22]


Answer a) 

    Step 1:               [16,21,11]                             [8,12,22]
                         /           \                         /           \
    Step 2:          [16,21]    -    [11]                  [8,12]    -    [22]
                  /        \             \               /      \            \
    Step 3:      [16]    -    [21]    -    [11]        [8]     -    [12]    -    [22]   
                  \       /              /             \         /            /
    Step 4:          [16,21]    -    [11]                  [8,12]    -    [22]
                        \            /                        \           /
    Step 5:                [11,16,21]                            [8,12,22]
                                  
    Step 6:                               [8,11,12,16,21,22]


Answer b)
         
         O(nlogn)
         
    

    
# Project 3

Binary Search Tree

    [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]


           7
          / \
         5   8
        / \   \
       1   6   9
      / \     /
     0   3   9
        / \
       2   4
