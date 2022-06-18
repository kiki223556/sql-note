# SQL Server Performance Essentials
## by [freeCodeCamp.org](https://www.youtube.com/watch?v=HvxmF0FUwrM&list=PLyJLOieA_Jh7Aru_SLX63Dqq_ig4obfQk)

---
### 2.Analyzing SQL statements for performance

~~~
1. Execution plan show how the sql server process the statement (not actually run).
2. Read plan from right to left, top to bottom (join).
3. Estimated operator cost in each individual operation.
4. Attention on high cost operation (consuming high resources and taking long time).
5. 'SET STATIDTICS IO ON'; 'SET STATISTICS TIME ON'.
6. 1 logical reads = 8 kb page of data. 
~~~

### 3.Building effective indexes
1. Clustered index : **Store** data for the table; **Organized** by the primary key; **Only** 1 allowed per table.
2. Non-clustered index : **Structure** used for all other indexes; **Data** organized by index key; **Contains** pointers to match rows; **Multiple** allowed per table.

- 11
- 15

`a`

![picture](https://img.freepik.com/free-vector/cute-ninja-working-laptop-cartoon-vector-icon-illustration-people-technology-icon-isolated-flat_138676-4801.jpg?w=200)

