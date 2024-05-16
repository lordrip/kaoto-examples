
```sql
INSERT INTO transactions (timestamp, account, amount) VALUES (:#${headers.SQL_TIMESTAMP}, :#${headers.SQL_ACCOUNT}, :#${headers.SQL_AMOUNT});

SELECT COUNT(*) FROM transactions
```