```mermaid
flowchart TD
  id0[/Enter Program\] --> id1
  id1([Present Interface]) --- id5([Other/Exit])
  id1 --- id2([Student])
  id1 --- id3([Instructor])
  id1 --> id4([Admin])
  id3 --> id6([Print Course Teaching Schedule])
  id3 --- id8([Print/Search Course Rosters])
  id8 --> ida[\Print/]
  id8 --> idb[\Search/]
