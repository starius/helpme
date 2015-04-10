# Lua metamethods

This table is based on the [e-mail][1] from Sean Conner, sean@conman.org.

[1]: http://lua.2524044.n2.nabble.com/Fast-metamethods-for-User

|  key        |  5.1  |  5.2  |  5.3  |  function  |  type          |
| ----------- | ----- | ----- | ----- | ---------- | -------------- |
| __add       |   *   |   *   |   *   |   a + b    |                |
| __sub       |   *   |   *   |   *   |   a - b    |                |
| __mul       |   *   |   *   |   *   |   a * b    |                |
| __div       |   *   |   *   |   *   |   a / b    |                |
| __mod       |   *   |   *   |   *   |   a % b    |                |
| __pow       |   *   |   *   |   *   |   a ^ b    |                |
| __umn       |   *   |   *   |   *   |   -a       |                |
| __idiv      |       |       |   *   |   a // b   |                |
| __band      |       |       |   *   |   a & b    |                |
| __bor       |       |       |   *   |   `a | b`  |                |
| __bxor      |       |       |   *   |   a ~ b    |                |
| __bnot      |       |       |   *   |   ~a       |                |
| __shl       |       |       |   *   |   a << b   |                |
| __shr       |       |       |   *   |   a >> b   |                |
| __concat    |   *   |   *   |   *   |   a .. b   |                |
| __len       |   *   |   *   |   *   |   #a       |                |
| __eq        |   *   |   *   |   *   |   a == b   |                |
| __lt        |   *   |   *   |   *   |   a < b    |                |
| __le        |   *   |   *   |   *   |   a <= b   |                |
| __index     |   *   |   *   |   *   |   a = b[i] |  can be table  |
| __newindex  |   *   |   *   |   *   |   a[i] = b |  can be table  |
| __call      |   *   |   *   |   *   |   a()      |                |
| __gc        |   *   |   *   |   *   |            |                |
| __mode      |   *   |   *   |   *   |            |  string        |
| __metatable |   *   |   *   |   *   |            |  table         |
| __tostring  |   *   |   *   |   *   |            |                |
| __ipairs    |       |   *   |       |            |                |
| __pairs     |       |   *   |   *   |            |                |
| __name      |       |       |   *   |            |  string        |
