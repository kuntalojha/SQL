# **SQL NOTEBOOK**

> ## **IS NOT**

### **IS NOT SQL QUESTIONS AND ANSWERS**

**1. Q. Write a query to display ename,job,sal and comm, if employee does not earnning some commission.**

- **ANSWER:**

```sql
select ename,job,sal,comm
from emp
where comm is null;
```

**Q2. Write a query to display ename,job,sal and comm, if employee earnning some commission.**

- **ANSWER:**

```sql
select ename,job,sal,comm
from emp
where comm is not null;
```

> ## **LIKE**

- It is used for pattern mataching in the query.
- Syntax:
  `column_name like 'pattern'`
- `-` represents single character.
- `%` represents multiple characters.

### **Questions & Answers**

**1. Q. Write a query to display ename if employee name starts with character 'A'.**

- **ANSWER:**

```sql
select ename
from emp
where ename like 'A%';
```

> ## **NOT LIKE**

- > books hello goood
  > rftgyhjk
