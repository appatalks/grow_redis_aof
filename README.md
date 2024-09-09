# grow_redis_aof
I need to simulate out-of-control Redis instance.


This script will continuously insert random 1KB strings into Redis. <br> It _should_ eventually cause Redis to exceed its memory limit and crash or refuse new connections.
