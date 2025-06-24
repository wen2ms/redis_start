- **ADD**

    `SADD bar 1 2 3 4 5`

    `SMEMBERS bar`

    `SADD foo 3 4 5 6 7`

- **Operations**

    `SINTER foo bar`

    `SDIFF foo bar`

    `SUNION foo bar`

- **Remove**

    randomly remove

    `SPOP foo`

    `SPOP foo 2`

    specifically remove

    `SREM foo "3" "4"`

- **Get**

    `SISMEMBER bar 3`

    `SRANDMEBMER bar`

    `SRANDMEBMER bar 2`

- **Move**

    `SMOVE bar foo 3`

