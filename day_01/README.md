Bài 1:Tạo bảng
```sql
create table Post(
title varchar(250), 
content text, 
created DATETIME, 
author varchar(100), 
category set('Sport','Politics','Health','Tourism','Economy','Education','Technology','Science'), 
is_published boolean 
);
```