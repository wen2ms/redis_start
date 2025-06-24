- **Create hash**

    `HSET lucy sex female age 23 id 001`

    deprecated: `HMSET lucy sex female age 23 id 001`

- **Get**

    `HGET lucy sex`

    `HMGET lucy sex age id`

    `HGETALL lucy`

    `HKEYS lucy`

    `HVALS lucy`

- **Remove**

    `HDEL lucy sex age`

    `HEXISTS lucy id`

    `HLEN lucy`