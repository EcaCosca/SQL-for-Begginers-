# Codewars - SQL for Beginners

Exercises completed at https://www.codewars.com/collections/sql-for-beginners (15.07.2022)

### Adults only (SQL for Beginners #1)

```sql
SELECT * 
FROM users 
WHERE age >= 18;
```

### On the Canadian Border (SQL for Beginners #2)

```sql
SELECT * 
FROM travelers 
WHERE country 
NOT IN ('Mexico', 'USA', 'Canada')
```

### Register for the Party (SQL for Beginners #3)

```sql
INSERT INTO participants 
VALUES ('Eca', '33', true);

SELECT * 
FROM participants;
```

### Collect Tuition (SQL for Beginners #4)

```sql
SELECT * 
FROM students 
WHERE NOT tuition_received;
```

### Best-Selling Books (SQL for Beginners #5)

```sql
SELECT * 
FROM books 
ORDER BY copies_sold 
DESC LIMIT 5;
```

### Countries Capitals for Trivia Night (SQL for Beginners #6)

```sql
SELECT capital
FROM countries
WHERE continent IN ('Africa', 'Afrika') AND country LIKE 'E%'
ORDER BY capital ASC
LIMIT 3;
```
