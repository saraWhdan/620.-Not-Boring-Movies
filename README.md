# 620- Not-Boring Movies
### Problem Description :  [Not Boring Movies](https://leetcode.com/problems/not-boring-movies/description/?envType=study-plan-v2&envId=top-sql-50)

## Solution
```sql
select id, movie ,description ,rating
from cinema
where id%2<>0
and description <> 'boring'
order by rating desc
