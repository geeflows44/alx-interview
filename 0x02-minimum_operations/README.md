# 0x02. Minimum Operations

## Requirements

### General

+ Allowed editors: `vi`, `vim`, `emacs`
+ All your files will be interpreted/compiled on Ubuntu 14.04 LTS using `python3` (version 3.4.3)
+ All your files should end with a new line
+ The first line of all your files should be exactly `#!/usr/bin/python3`
+ A `README.md` file, at the root of the folder of the project, is mandatory
+ Your code should be documented
+ Your code should use the `PEP 8` style (version 1.7.x)
+ All your files must be executable

## Flowchart of Solution

```
                    +------------------+
                    |  Start function  |
                    +------------------+
                             |
                             v
                    +--------------------+
                    | Set min_operations |
                    |      to zero       |
                    +--------------------+
                            |
                            v
                    +------------------+
                    | Check if n <= 1  |
                    +------------------+
                            |
                            v
            +--+<---+ If true, return 0
            |  |
            |  v
+-------------+-------------+
|   For i in range(2, n+1)  |
+---------------------------+
            |  |
            |  v
     +------+----------+
     | Check if n is   |
     | divisible by i  |
     +------+----------+
            |  |
            v  |
     +------+-----------+
     | Divide n by i    |
     | and add i to the |
     | total            |
     +------+-----------+
            |  |
            v  |
     +------+-----------+
     | Continue to      |
     | divide n by i    |
     | until n is no    |
     | longer divisible |
     | by i             |
     +------+-----------+
            |  |
            v  |
+-----------+--+-----------+
| Return min_operations    |
+--------------------------+
```
