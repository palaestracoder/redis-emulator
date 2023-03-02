# redis-emulator

The file in this project is a [Redis](https://redis.io/commands/) emulator.
Its main purpose is to facilitate small experiments, helping a developer
to write software with the real Redis client libraries, so that eventually an
application can be promoted into a real server environment, and seamlessly
integrate with a real Redis server.

The Redis emulator is platform-independent, while the real Redis only runs on
Linux. (This github project contains only the Windows build.)

The emulator supports many of the mainstream Redis commands, including:

* String keys
* Lists
* Hash Tables
* Sets

More exotic features are not supported.

Auth is not supported either.

The emulator persists data into a file per Redis database, making it
very easy to capture database snapshots and maintain separate data
file sets for different projects.

