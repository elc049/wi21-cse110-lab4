The issue was that the values were taken in as strings and therefore concatenated instead of added. I fixed this by using the unary plus operator to convert the strings to numbers before they are added.

1. citylots.json
2. part2.js
3. 11.7MB
4. 17.74s
5. Chrome/88.0.4324.104
6. Apache
7. Last-Modified: Tue, 26 Jan 2021 22:14:13 GMT
8. Content-Type: application/json
9. fetchData()