def get_matrix (n, m, value):
 matrix = []
 for i in range(n):
 matrix.append([0] * m)
 for j in range(m):
 matrix[i][j] = value
 return (matrix)

n1 = int(input('Введите количество строк 1ой матрицы: '))
m1 = int(input('Введите количество столбцов 1ой матрицы: '))
value1 = int(input('Введите значение элементов 1ой матрицы: '))
print(get_matrix(n1, m1, value1))
n2 = int(input('Введите количество строк 2ой матрицы: '))
m2 = int(input('Введите количество столбцов 2ой матрицы: '))
value2 = int(input('Введите значение элементов 2ой матрицы: '))
print(get_matrix(n2, m2, value2))
n3 = int(input('Введите количество строк 3ей матрицы: '))
m3 = int(input('Введите количество столбцов 3ей матрицы: '))
value3 = int(input('Введите значение элементов 3ей матрицы: '))
print(get_matrix(n3, m3, value3))
