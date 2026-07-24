# SQL injection

## Lab1: SQL injection vulnerability in WHERE clause
### Lab: Retrieve hidden data — Apprentice

- **Bug:** the category filter puts the data stright in the SQL WHERE clause
- **Where:** in the 'Gift' category of product-filder URL
- **What worked:** added `'+OR+1=1--` after the `Gift` category
- **Why:** input is concatenated into the query instead of parameterised, so my quote breaks out of the string.
- **What I'd have missed:** just `'--` comments the rest in that querry, so You see all products in Gift category, not all products




---

