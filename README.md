# leibniz-py
Python script that approximates pi using the [Gregory-Leibniz Series](https://en.wikipedia.org/wiki/Leibniz_formula_for_%CF%80).
I wrote it to begin testing simple clustering using redis and someting that eats up CPU. 

## Requirements

* Python

* [redis](https://github.com/antirez/redis) - Redis is an in-memory database that persists on disk.

* [redis-py](https://github.com/andymccurdy/redis-py) - For communication between python and redis.

## First run

You must run `leibniz-reset` before running `leibniz`
