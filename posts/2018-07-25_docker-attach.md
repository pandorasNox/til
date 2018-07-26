Today I learned

- docker attach
    - https://docs.docker.com/engine/reference/commandline/attach/
- mongoDb objectID
    - example: ObjectId("507f1f77bcf86cd799439011")
    - clue is: The 12-byte ObjectId value consists of:
        - a 4-byte value representing the seconds since the Unix epoch,
        - a 3-byte machine identifier,
        - a 2-byte process id, and
        - a 3-byte counter, starting with a random value.
