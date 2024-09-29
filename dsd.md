"ตาราง FUND"
| FIELD         | TYPE          | NULL  | KEY | Default | EXTRA           |
|---------------|---------------|-------|-----|---------|-----------------|
| fund_id       | int(11)       | NO    | PRI | NULL    | AUTO_INCREMENT  |
| title         | varchar(50)   | NO    |     | NULL    |                 |
| Description   | varchar(3500) | YES   |     | NULL    |                 |
| goal_amount   | int(11)       | NO    |     | NULL    |                 |
| raised_amount | int(11)       | NO    |     | 0       |                 |

"ตาราง Contributions"
| FIELD         | TYPE          | NULL  | KEY | Default | EXTRA           |
|---------------|---------------|-------|-----|---------|-----------------|
| contribution_id        | int(11)       | NO    | PRI | NULL    | AUTO_INCREMENT  |
| user_id         | int(11)   | NO    |MUL| NULL    |                 |
| fund_id   | int(11) | NO   |MUL| NULL    |                 |
| amount   | int(11)       | NO    |     | NULL    |                 |


![image](https://github.com/user-attachments/assets/a461290c-d312-4bcf-a5d4-799a539ef28c)
