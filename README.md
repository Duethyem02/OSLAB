## OSLAB EXPERIMENTS

#### Best fit implementation

```
Enter number of processes:4
Enter size of each process:
P[1]:212
P[2]:417
P[3]:112
P[4]:426
Enter number of blocks:5
Enter size of each block:
B[1]:100
B[2]:500
B[3]:200
B[4]:300
B[5]:600
Block   Size    Process Size    Status
B[1]    100     0       0       Not Allocated
B[2]    500     2       417     Allocated
B[3]    200     3       112     Allocated
B[4]    300     1       212     Allocated
B[5]    600     4       426     Allocated
```

#### First fit implementation

```
Enter number of processes:3
Enter size of each process:
P[1]:12
P[2]:10
P[3]:56
Enter number of blocks:3
Enter size of each block:
B[1]:8
B[2]:10
B[3]:12
Block Size Process Size  Status
B[1]   8    0       0  Not Allocated
B[2]  10    2      10  Allocated
B[3]  12    1      12  Allocated

```

#### Interprocess Communication implementation

```
Key of shared memory is 32780
Process is attached at 0x7f2dc8269000
search 4
Value shared is search 4
```
```
Key of shared memory is 32780
Process is attached at 0x7f4fa4ef5000
Value read from shared is search 4
```

#### Worst fit implementation

```
Enter number of processes:4
Enter size of each process:
P[1]:212
P[2]:417
P[3]:112
P[4]:426
Enter number of blocks:5
Enter size of each block:
B[1]:100
B[2]:500
B[3]:200
B[4]:300
B[5]:600
Block   Size    Process Size    Status
B[1]    100     0       0       Not Allocated
B[2]    500     2       417     Allocated
B[3]    200     0       0       Not Allocated
B[4]    300     3       112     Allocated
B[5]    600     1       212     Allocated
```

#### Banker's algorithm implementation

```
Enter number of processes:5
Enter number of resources:3
Enter max.number of resources required for each process:
P[1]:
        R[1]:7
        R[2]:5
        R[3]:3
P[2]:
        R[1]:3
        R[2]:2
        R[3]:2
P[3]:
        R[1]:9
        R[2]:0
        R[3]:2
P[4]:
        R[1]:2
        R[2]:2
        R[3]:2
P[5]:
        R[1]:4
        R[2]:3
        R[3]:3
Enter number of  resources allocated for each process:
P[1]:
        R[1]:0
        R[2]:1
        R[3]:0
P[2]:
        R[1]:2
        R[2]:0
        R[3]:0
P[3]:
        R[1]:3
        R[2]:0
        R[3]:2
P[4]:
        R[1]:2
        R[2]:1
        R[3]:1
P[5]:
        R[1]:0
        R[2]:0
        R[3]:2
Enter number of  available resources:
3
3
2
P[2]    P[4]    P[1]    P[3]    P[5]
Safe
```
```
Enter number of processes:5
Enter number of resources:3
Enter max.number of resources required for each process:
P[1]:
        R[1]:7
        R[2]:5
        R[3]:3
P[2]:
        R[1]:3
        R[2]:2
        R[3]:2
P[3]:
        R[1]:9
        R[2]:0
        R[3]:2
P[4]:
        R[1]:2
        R[2]:2
        R[3]:2
P[5]:
        R[1]:4
        R[2]:3
        R[3]:3
Enter number of  resources allocated for each process:
P[1]:
        R[1]:0
        R[2]:1
        R[3]:0
P[2]:
        R[1]:2
        R[2]:0
        R[3]:0
P[3]:
        R[1]:3
        R[2]:0
        R[3]:2
P[4]:
        R[1]:2
        R[2]:1
        R[3]:1
P[5]:
        R[1]:3
        R[2]:3
        R[3]:2
Enter number of  available resources:
0
0
2

 Not safe
```
