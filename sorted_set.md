- **ADD**

    `ZADD bar 60 a 70 b 65 c 90 d`

    `ZRANGE bar 0 -1`

    `ZRANGE bar 0 -1 WITHSCORES`

    `ZREVRANGE bar 0 -1`

- **Remove**

    `ZREM bar a`

- **Get**

    `ZSCORE bar c`

- **Count**

    `ZCOUNT bar 60 100`

    `ZRANK bar d`

    `ZREVRANK bar d`