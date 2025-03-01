# Syntax 

| Function   | Description |
|----------- | ----------- |
| `Distinct` | gives unique entries |
| `count` | gives count of whatever specified |
| `length` (<column name>) | gives length of the length of that column name in integer |
| `order by` | orders <table name> by `aes` or `desc` |
| `limit` <n> | limits the output by n entries |
| `or` | is for or condition |
| `and` | is for and condition |
| `like` | is for pattern matching <br> ex: city like "a%"   <br> city which starts from a , <br> "%a%" contains a,<br> "%a" ends with a |
| `left (<column name>,<range>)` |  extracts from <column name> till <range> |
| `in` |  checks if the given string contains the speicifed set <br> ex : select Distinct city from station where left(city,1) in ('a','e','i','o','u') | 
| `not in` | check if the given string does not contain the specified set | 

