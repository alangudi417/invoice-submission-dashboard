# DAX Measures

## Total Invoice Amount
Description:
Calculates the total value of all submitted invoices.

```DAX
Total Amount =
SUM(Invoices[Total Invoice])
```


## Number of Invoices
Description:
Counts the total number of submitted invoices.

```DAX
Number of Invoices =
COUNT(Customers[Invoice])
```