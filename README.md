# MatriksTT
## Tugas
1.Penambahan dua matriks

2.Perkalian dua matriks

3.Transpose dua matriks

Tugas anda membuat 3 program tsb tanpa library numpy

## 1.Penambahan dua matriks  
    mat1 = [
        [5, 0],
        [2, 6],
    ]
    
    mat2 = [
        [1, 0],
        [4, 2],
    ]
    
    mat3 = []
    
    for x in range(0, len(mat1)):
    for y in range(0, len(mat1[0])):
        print (mat1[x][y] + mat2[x][y], end=' ')
    print()
    
   ### Output
    6 0 
    6 8 
    
 ## 2.Perkalian dua matriks
      mat1 = [
          [5, 0],
          [2, 6],
      ]

      mat2 = [
          [1, 0],
          [4, 2],
      ]

      mat3 = []
      
      for x in range(0, len(mat1)):
        row = []
        for y in range(0, len(mat1[0])):
            total = 0
            for z in range(0, len(mat1)):
                total = total + (mat1[x][z] * mat2[z][y])
            row.append(total)
        mat3.append(row)
        
       for x in range(0, len(mat3)):
         for y in range(0, len(mat3[0])):
             print (mat3[x][y], end=' ')
         print ()
         
   ### Output
      5 0 
      26 12
      
## 3.Transpose dua matriks
    X = [[12,7],
    [4 ,5]]
    
    for i in range(len(X)):
     for j in range(len(X[0])):
         result[j][i] = X[i][j]
         
    for r in result:
      print(r)
      
  ### Output 
      [12, 4]
      [7, 5]
