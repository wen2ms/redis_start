- **Add**

    `LPUSH my_list a b c d`

    `RPUSH foo a b c d`

- **Traversal**

    `LRANGE my_list 0 -1`

    `LRANGE foo 0 3`

- **Insert**

    `LINSERT foo BEFORE b hello`

    `LINSERT foo AFTER b world`

- **Visit**

    `LINDEX foo 4`

- **Modify**

    `LLEN foo`

    `LSET foo 5 !`

- **Remove**

    0: remove all elements equals to "hello"

    `LREM foo 0 hello`

    \>0: remove left elements equals to "hello"

    `LREM foo 2 hello`

    \<0: remove right elements equals to "hello"

    `LREM foo -2 hello`