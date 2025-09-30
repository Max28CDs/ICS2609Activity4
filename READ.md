
INNER JOIN
Gets only the rows that match on both tables.  
Example: show only users that already have a role.

LEFT JOIN
Gets everything from the left table, and the matching rows from the right.  
If no match, the right side will just be `NULL`.

RIGHT JOIN 
Opposite of LEFT JOIN. Keeps everything from the right table even if the left has no match.

FULL OUTER JOIN in MySQL 
MySQL doesn’t support this directly.  
Workaround: combine a LEFT JOIN and a RIGHT JOIN using `UNION`.

CROSS JOIN
Makes all possible combinations of rows between two tables.  
Usually used for testing or when we need every pair.

SELF JOIN
Joins a table to itself.  
Example: showing who is the manager of who in the same employees table.

API Reports Endpoints

/api/reports/sales – shows sales data (like totals and transactions).  
/api/reports/users – shows user activity or how many signed up.  
/api/reports/orders – gives order statistics (finished, pending, canceled).  
/api/reports/items – shows item reports like inventory or which are popular.  
/api/reports/custom – for custom reports depending on the filters you send.

How to Run
- Clone the repository from github 
- Install all the dependencies with (npm i or npm intall
- Run the server and check for connectivity  
- Access the reports using the `/api/reports/*` endpoints
